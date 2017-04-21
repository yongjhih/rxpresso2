# RxExpresso2

[![CircleCI](https://circleci.com/gh/yongjhih/rxpresso2.svg?style=shield)](https://circleci.com/gh/yongjhih/rxpresso2)
[![codecov](https://codecov.io/gh/yongjhih/rxpresso2/branch/master/graph/badge.svg)](https://codecov.io/gh/yongjhih/rxpresso2)

## Usage

```java
RxIdlingResource rxIdlingResource = new RxIdlingResource();
Espresso.registerIdlingResources(rxIdlingResource);
RxJavaPlugins.setScheduleHandler(rxIdlingResource);
```

## Installation

```gradle
compile 'com.github.yongjhih.rxpresso2:rxpresso2:-SNAPSHOT'
compile 'com.github.yongjhih.rxpresso2:rxpresso2-kotlin:-SNAPSHOT' // optional
```

## Credit

* Andreas Ahlenstorf

## See also

* https://github.com/stablekernel/RxEspresso
* https://gist.github.com/aahlenst/8d3958ceceb971465873e5818ba6fd1f
* https://github.com/novoda/rxpresso
* https://github.com/ReactiveX/RxAndroid/issues/149

## License

```
The MIT License

Copyright (c) 2016 Andrew Chen
Copyright (c) 2016 Andreas Ahlenstorf

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
