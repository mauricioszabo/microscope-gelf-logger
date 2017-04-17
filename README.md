# Microscope's GELF logger
[![Build Status](https://travis-ci.org/acessocard/microscope-gelf-logger.svg?branch=master)](https://travis-ci.org/acessocard/microscope-gelf-logger)
[![Clojars Project](https://img.shields.io/clojars/v/microscope/gelf-logger.svg)](https://clojars.org/microscope/gelf-logger)
[![Dependencies Status](https://jarkeeper.com/acessocard/microscope-gelf-logger/status.svg)](https://jarkeeper.com/acessocard/microscope-gelf-logger)

A simple logger for GELF format

## Usage

Simply use:

```clojure
(subscribe-with :logger gelf/logger)
```

And everything will work. This logger is configured by `GELF_HOST` environment variable,
and will publish to port `12201`, UDP.

## License

## MIT License

Copyright 2017 AcessoCard

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
