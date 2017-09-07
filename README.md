heroku-buildpack-ortools
=====================

A helper buildpack to get google ortools working on Heroku.

Usage
-----

First set your `BUILDPACK_URL` to `https://github.com/ddollar/heroku-buildpack-multi.git`:

```bash
$ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git
```

Create the `.buildpacks` config for buildpack-multi:

```bash
$ cat .buildpacks
https://github.com/heroku/heroku-buildpack-python
https://github.com/sharonyogev/heroku-buildpack-ortools
```


License
-------

Copyright 2014, Noah Kantrowitz

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
