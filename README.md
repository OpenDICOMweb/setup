### [Open DICOMweb] ([ODW])
# Software Development Environment Setup

This document describes the standard software development environment
that is used by the development team for Open DICOMweb. It is also a
useful starting point for programmers wishing to build software based on
the ODW SDKs.

Open DICOMweb (ODW) software is developed using the [Dart] programming
language. Dart is an open-source, scalable programming language, with
robust libraries and runtime systems, for building web, server, and
mobile apps. See [dartlang.org] for more information.

The ODW project repositories are hosted on [GitHub] at [Open DICOMweb].

The ODW project uses the [GitHub Flow] workflow. is a lightweight,
branch-based workflow that supports teams and projects where deployments
are made regularly. This [guide] explains how and why GitHub Flow works.

If you are planning to do development using Open DICOMweb, We recommend
using JetBrain's [WebStorm] as your editor (IDE).

## Getting Started Overview

We recommend you do the following before getting started:

1. [Install Java](#install_java)
2. [Install Dart](#install_dart)
3. [Install Webstorm](#install_webstorm)
4. Download the [ODW Software Development Kit]
5. Download the [ODW Examples]
    
## Java Installation and Setup <a name="install_java"></a>

1. Download and install Jave software. See https://java.com/en/download. 
See https://java.com/en/download/help for help with installing Java.

2. Add Java bin director to the System (if possible) or User environment
"path" variable.

 For example, set the following user environment variables:
 
    JAVA_HOME : C:\Program Files\Java\jdk1.8.0_25
    JDK_HOME  : %JAVA_HOME%
    JRE_HOME  : %JAVA_HOME%\jre
    CLASSPATH : .;%JAVA_HOME%\lib;%JAVA_HOME%\jre\lib
    PATH      : your-unique-entries;%JAVA_HOME%\bin 
    
_Note: Make sure that the longish your-unique-entries does not contain
 any other references to another Java installation folder_.

## Dart Installation <a name="install_dart"></a>

1. [Create the standard ODW Dart directory structure](./dart_directory_structure.md)
2. Download the release (stable) or development (dev) versions of the 
Dart:
    - sdk: See https://www.dartlang.org/tools/sdk.
    - dartium: See https://www.dartlang.org/tools/dartium.
    - doc: (only need to download this if you want to access it offline or more quickly)
    
from https://www.dartlang.org/downloads/archive.  
    
1. Setup environment variables. See https://www.dartlang.org/tools/pub/installing.html. For example on Windows:

    set PATH=%PATH%;C:/tools/dart/stable/sdk/dart-sdk-1.17.0/bin
    set PUB_CACHE: C:/tools/dart/pub/cache

## [Install WebStorm]<a name="install_webstorm"></a>

1. TODO: Add WebStorm defaults. a. install software b. install setup files b.
   set environment variables

1. TODO: Add Environment variables setup

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[Open DICOMweb], [ODW]: https://github.com/OpenDICOMweb 

[Dart]: https://en.wikipedia.org/wiki/Dart_(programming_language)

[dartlang.org]: https://www.dartlang.org/    

[GitHub]: https://github.com/

[GitHub Flow], [guide]: https://guides.github.com/introduction/flow/

[WebStorm]: https://www.jetbrains.com/webstorm/ [ODW Examples]:

[tracker]: http://github.com/OpendDICOMweb/issues/replaceme

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/OpenDICOMweb/setup/issues
