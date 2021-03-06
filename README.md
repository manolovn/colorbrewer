# ColorBrewer
[![Build Status](https://travis-ci.org/manolovn/colorbrewer.svg?branch=master)](https://travis-ci.org/manolovn/colorbrewer)
[![Maven Central](https://img.shields.io/maven-central/v/com.manolovn/colorbrewer.svg)](https://maven-badges.herokuapp.com/maven-central/com.manolovn/colorbrewer)

Color palettes for your projects

# Usage

Add the dependency

```groovy
dependencies {
    compile 'com.manolovn:colorbrewer:1.0.0'
}
```

There are a lot of different palettes, choose one and explore the API.
For example, to generate a 20 steps interpolation of Greys palette:

```java
int[] colors = ColorBrewer.Greys.getColorPalette(20);
```

# License

    Copyright 2015 Manuel Vera Nieto

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
