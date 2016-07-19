[<strong>Open DICOM<em>web</em></strong>][ODW] ([<strong>ODW</strong>][ODW])
#### Dart Directory Structure

- [/odw]
    - [/sdk](#sdk)
        - [/odwsdk](#odwsdk) soon to be named "core"
            - [/bin](#bin)
            - [/lib](#lib)
                - [/src](#src)
                    - [/attribute](#attribute)
                    - [/dataset](#dataset)
                    - [/date_time](#date_time)
                    - [/element](#element)
                    - ...
            - [/test](#test)
        - [/bytebuf](#bytebuf)
        - [/convert](#convert)
        - [/deidentification](#deidentification)
        - [/integer](#integer)
        - [/io](#io)
        - [/logger](#logger)
        - [/timestamp](#timestamp)
        - [/utils](#utils)
        - [/uuid](#uuid)
    - [/examples](#examples)
    - [/setup](#setup)

<dl>
 <dt><a id="sdk"></a> **/odw/sdk**</dt>
 <dd>This directory is the root of the software development kit (SDK).  It's subdirectories contain libraries that provide related functionality.<dd>

<dt> <a id="odwsdk"></a>/odw/sdk/odwsdk</dt>
<dd> This directory contains the core functionality of
the Open DICOM<em>web</em> toolkit.

<em>Note</em>: This
directory will soon be renamed **core**.</dd>

<dt>  <a id="bin"></a>/odw/sdk/odwsdk/bin</dt>
<dd>Executable programs that are based on the SDK</dd>

<dt>  <a id="lib"></a>/odw/sdk/odwsdk/lib</dt>
<dd>Definitions of the different core libraries. </dd>

<dt>  <a id="src"></a>/odw/sdk/odwsdk/lib/src</dt>
<dd>Source files related to the libraries define one level up</dd>

<dt>  <a id="attribute"></a>/odw/sdk/odwsdk/lib/src/attribute</dt>
<dd>Source files for the Attribute library. </dd>

<dt>  <a id="date_time"></a>/odw/sdk/odwsdk/lib/src/data_time</dt>
<dd>This library handles DICOM Dates, DateTimes, and Times.</dd>

<dt>  <a id="element"></a>/odw/sdk/odwsdk/lib/src/dataset</dt>
<dd>Source files that define DICOM Date Elements. </dd>

<dt>  <a id="dataset"></a>/odw/sdk/odwsdk/lib/src/dataset</dt>
<dd>Source files for the Dataset library. </dd>

<dt>  <a id="test"></a>/odw/sdk/odwsdk/test</dt>
<dd>Unit tests for the ODWSDK libraries.</dd>

<dt>  <a id="bytebuf"></a>/odw/sdk/bytebuf</dt>
<dd>This library that provides buffered input and output.</dd>

<dt>  <a id="convert"></a>/odw/sdk/convert</dt>
<dd>This library provides functionality for converting (encoding/decoding)
 DICOM data structures such as Study, Series, Instance
 into different media types.</dd>

<dt>  <a id="deidentification"></a>/odw/sdk/deidentification</dt>
<dd>A library that handles de-identification of DICOM objects.</dd>

<dt>  <a href="integer"></a>/odw/sdk/integer</dt>
  <dd>Integer utilities.</dd>

<dt>  <a id="io"></a>/odw/sdk/io</dt>
<dd>A library that handles file and network io.</dd>

<dt>  <a id="logger"></a>/odw/sdk/logger</dt>
<dd>A library for logging errors, warnings, info, etc.</dd>

<dt>  <a id="timestamp"></a>/odw/sdk/logger</dt>
<dd>A library that handlers timestamps.</dd>

<dt>  <a id="utils"></a>/odw/sdk/logger</dt>
<dd>A library of useful utility functions.</dd>

<dt>  <a id="uuid"></a>/odw/sdk/uuid</dt>
<dd>A library that implements Version 4 UUIDs.</dd>

<dt>  <a id="examples"></a>/odw/sdk/setup</dt>
<dd>A directory that in the future will contain example ODW programs</dd>

<dt>  <a id="setup"></a>/odw/sdk/setup</dt>
<dd>A directory that describes the standard ODW and Dart setup for
software developers.</dd>

<dt>  <a id="setup"></a>/odw/sdk/setup</dt>
<dd>A directory that describes the standard ODW and Dart setup for
software developers.</dd>



[ODW]: https://github.com/OpenDICOMweb

