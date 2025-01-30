# CMake GoogleTest Template
This repository provides a minimal and reusable CMake template for setting up unit tests with GoogleTest. It simplifies the integration of GoogleTest into C++ projects, ensuring a clean and modular structure.

## Features

* **CMake-based build system** – Easily configurable and portable.
* **GoogleTest integration** – Preconfigured for unit testing.
* **Minimal setup** – Ready-to-use template with a simple example test.
* **Cross-platform compatibility** – Works on Windows, Linux, and macOS.

## Usage

1. Clone the repository:

```
git clone https://github.com/yourusername/cmake-gtest-template.git
cd cmake-gtest-template
```

2. Create a build directory and configure the project:

```
cmake -S . -B build
```

3. Build and run the tests:

```
cmake --build build -j 12 
ctest --test-dir build
```

This template serves as a starting point for C++ projects that require unit testing with GoogleTest while maintaining a clean and organized project structure.