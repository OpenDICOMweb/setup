### [Open DICOMweb][ODW] ([ODW][ODW])
# Software Development Environment Setup

This document describes the standard software development environment
that is used by the development team for Open DICOMweb. It is also a
useful starting point for programmers wishing to build software based on
the ODW SDKs.

Open DICOMweb (ODW) software is developed using the [Dart] programming
language. Dart is an open-source, scalable programming language, with
robust libraries and runtime systems, for building web, server, and
mobile apps. See [dartlang.org][dartlang] for more information.

The ODW project repositories are hosted on [GitHub][GitHub] at [Open DICOMweb][ODW].

The ODW project uses the [GitHub Flow][GitFlow] workflow. is a lightweight,
branch-based workflow that supports teams and projects where deployments
are made regularly. This [guide][GitFlow] explains how and why GitHub Flow works.

If you are planning to do development using Open DICOMweb, We recommend
using JetBrain's [WebStorm][WebStorm] as your editor (IDE).

## Getting Started Overview

We recommend you do the following before getting started:

1. [Install Java](#java-setup)
2. [Install Dart](#dart-setup)
3. [Install Webstorm](#webstorm-setup)
4. [Clone ODW Software Development Kit repository](#clone-sdk)
5. [Clone ODW Examples examples](#clone-examples)
    
## <a id="java-setup"></a>Java Installation and Setup

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

## <a id="dart-setup"></a>Dart Installation and Setup

1. Create the standard 
[ODW Dart directory structure](./dart_directory_structure.md)

2. Download the release (stable) or development (dev) versions of the 
Dart:
    - sdk: See https://www.dartlang.org/tools/sdk.
    - dartium: See https://www.dartlang.org/tools/dartium.
    - doc: (only need to download this if you want to access it offline or more quickly)
    
from https://www.dartlang.org/downloads/archive.  
    
1. Setup environment variables. See https://www.dartlang.org/tools/pub/installing.html. For example on Windows:

    set PATH=%PATH%;C:/tools/dart/stable/sdk/dart-sdk-1.17.0/bin
    set PUB_CACHE: C:/tools/dart/pub/cache

## <a id="webstorm-setup"></a>WebStorm Installation and Setup

1. TODO: Add WebStorm defaults. a. install software b. install setup files b.
   set environment variables

2. TODO: Add Environment variables setup

## <a id="clone-sdk"></a>Clone ODW SDK Repository)

TODO:

## <a id="clone-examples"></a> Clone ODW Examples

Clone the [ODW Examples Repository][Examples].

TODO:

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[ODW]: https://github.com/OpenDICOMweb 

[Dart]: https://en.wikipedia.org/wiki/Dart_(programming_language)

[dartlang]: https://www.dartlang.org   

[GitHub]: https://github.com

[GitFlow]: https://guides.github.com/introduction/flow

[WebStorm]: https://www.jetbrains.com/webstorm/ 

[Examples]: https://github.com/OpenDICOMweb/examples

[tracker]: http://github.com/OpendDICOMweb/issues/replaceme

