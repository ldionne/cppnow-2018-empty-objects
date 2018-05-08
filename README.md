## Lightning talk on template errors @ C++Now 2018

This repository contains my [reveal.js][]-based lightning talk about template
errors for [C++Now 2018][].

## Usage
Go to https://ldionne.com/cppnow-2018-template-errors or open `index.html`
with your browser.

## Building the code samples
```sh
# Install the dependencies and get back the CMAKE_PREFIX_PATH to use
CMAKE_PREFIX_PATH="$(./code/dependencies/install.sh)"

# Usual CMake build, with a custom CMAKE_PREFIX_PATH for locally-installed dependencies
(mkdir build && cd build && cmake .. -GNinja -DCMAKE_PREFIX_PATH="${CMAKE_PREFIX_PATH}")
cmake --build build
```

<!-- Links -->
[C++Now 2018]: http://cppnow.org/history/2018
[reveal.js]: https://github.com/hakimel/reveal.js
