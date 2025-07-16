# Hammer Build Tool

A template repo that you can use to compile all dependencies for our tools.

## Overview
Some tools created by Poly Hammer have dependencies on other libraries or software's code that we can not re-distribute, however you are allowed to compile these dependencies for your own productions. This build tool can be purchased as a convenient way to help you or your company build the dependencies for yourself. However, the user/company is solely responsible for ensuring that they are not violating any software licensing by using this tool.

## How to Use
To get started with the Hammer Build Tool, please watch the following tutorial video:

[![Hammer Build Tool Tutorial](./media/thumbnail-1.png)](https://www.youtube.com/watch?v=BAyCV8GwmCM)

For more detailed instructions, refer to the documentation:
https://docs.polyhammer.com/hammer-build-tool/setup/


## Platform Support
This is the most stream-lined way for us to help support the users of our tools. Here are the environments that we currently support.

| Platform      |  Architecture  |
|---------------|----------------|
| `Windows`     |    `amd64`     |
| `Linux`       |    `x86_64`    |
| `MacOS`       |    `arm64`     |


## Tools Support
The hammer build tool will download the needed source code then compile it to produce the libraries needed. Here are the tools it currently supports, and where it is downloading the respective source code to create the compiled dependencies.

* `Meta-Human DNA Addon`:
    1. `RigLogic`
        * [License](https://www.unrealengine.com/en-US/eula/unreal)
        * [Source](https://github.com/EpicGames/UnrealEngine)
