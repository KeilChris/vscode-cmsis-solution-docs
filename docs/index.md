# CMSIS Solution extension

The **CMSIS Solution** extension available for VS Code allows to create projects and build embedded applications that use [CMSIS *software packs*](https://www.keil.arm.com/packs/). 
It is a user interface for the [CMSIS-Toolbox](https://open-cmsis-pack.github.io/cmsis-toolbox/) that supports various compilation tools including Arm Compiler 6, GCC, IAR, and LLVM.

## Contents

- [**Setup**](installation.md) explains how to install the CMSIS Solution extension along with a build environment for
  embedded applications that are based on Arm Cortex-M processors

- [**Quick start**](quickstart.md) shows the main features available in the CMSIS Solution extension GUI

- [**Create an embedded project**](create_app.md) explains how to start a project from scratch

- [**Manage software components**](./manage_components.md) shows how to add or remove software components in a solution

- [**Manage solution settings**](./manage_settings.md) explains how to configure a *csolution project* for run and debug

- [**Build a project**](build.md) describes how to build a project

- [**Run the application**](./flash.md) explains how to run an application on your hardware

- [**Debug a project**](debug.md) explains how to debug a project

- [**Configuration**](configuration.md) explains how to manage the extension settings and some specific configuration options

- [**Import µVision project**](./importuv.md) explains how to convert uvprojx-based files to the CMSIS Solution format

- [**Configure run and debug**](./conf_debug.md) describes the integration of the CMSIS-Toolbox Run and Debug Management

- [**Run external tools**](./runexternal.md) describes how to use external tools, such as debuggers and flash programmers

- [**Tips and tricks**](./tipsandtricks.md) provides tips and tricks to help you solve specific issues

## Revision history

Version            | Description
:------------------|:-------------------------
1.54.0             | Added CMSIS-Toolbox Run and Debug Management
1.48.0             | Initial release for the CMSIS Solution extension version 1.48.0
