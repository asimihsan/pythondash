# pythondash

Dash docsets for various Python modules

## How to generate the docsets

```
# You need pip. If you don't have it see:
# http://www.pip-installer.org/en/latest/installing.html

git clone git@github.com:asimihsan/pythondash.git
cd pythondash

# Create a new virtualenv using virtualenv (or use virtualenvwrapper's
# mkvirtualenv)
pip install virtualenv
virtualenv pythondash
source pythondash/bin/activate

# Install required modules into your virtualenv
pip install -r requirements.txt

# Create e.g. the Fabric docset
./fabric/build
```

## Feed URLs

-   [Fabric](http://docs.fabfile.org/): [http://files.asimihsan.com/dash/Fabric.xml](http://files.asimihsan.com/dash/Fabric.xml)

## License

Copyright 2013 Asim Ihsan

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
