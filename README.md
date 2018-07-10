# Maven Archetype for SpotBugs Plugin project

[![Build Status](https://travis-ci.org/spotbugs/spotbugs-archetype.svg?branch=master)](https://travis-ci.org/spotbugs/spotbugs-archetype)

## How to use

Simply execute following commands, to create new Maven project in current directory:

```sh
$ mvn archetype:generate \
    -DarchetypeArtifactId=spotbugs-archetype \
    -DarchetypeGroupId=com.github.spotbugs \
    -DarchetypeVersion=0.2.0
```

You can also set the version of SpotBugs via system property `spotBugsVersion`:

```sh
$ mvn archetype:generate \
    -DarchetypeArtifactId=spotbugs-archetype \
    -DarchetypeGroupId=com.github.spotbugs \
    -DarchetypeVersion=0.3.0-SNAPSHOT \
    -DspotBugsVersion=3.1.5
```

## License

Copyright 2017 SpotBugs team

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
