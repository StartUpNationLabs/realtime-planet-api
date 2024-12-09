# realtime-planet-api
API used to get realtime info on Planet's

## About The Project
This project provides a comprehensive API to calculate and retrieve information about planets. 

### Built With

* [Go](https://golang.org/)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Go
    ```sh
    go install
    ```

* Protoc (for protobuf)
  * If you are on a Mac, you can install it using Homebrew
      ```sh
      brew install protobuf
      ```
  * If you are a Windows user, you can download the latest binaries from [GitHub Releases](https://github.com/protocolbuffers/protobuf/releases/)

* Buf (for protobuf)
  * If you are on a Mac, you can install it using Homebrew
      ```sh
      brew tap bufbuild/buf
      brew install buf
      ```
  * If you are a Windows user, you can download the latest binaries from [GitHub Releases](https://github.com/bufbuild/buf/releases/)

* Buf generate (To regenerate the protobuf file)
    ```shell
      buf generate
    ```
