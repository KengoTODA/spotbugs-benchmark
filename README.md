
[![Build Status](https://travis-ci.com/KengoTODA/spotbugs-benchmark.svg?branch=master)](https://travis-ci.com/KengoTODA/spotbugs-benchmark)

## How to run benchmark

```sh
$ pip3 install virtualenv
$ virtualenv .python3
$ source .python3/bin/activate
$ pip3 install -r requirements.txt
$ export ANSIBLE_HOST_KEY_CHECKING=False
$ ansible-playbook playbook.yml -i hosts.yml
```

## License

Copyright 2018 Kengo TODA

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
