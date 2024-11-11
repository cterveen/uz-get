## Project name

uz-get

## Description

uz-get is a Perl script intended to download packages from Unreal Tournament redirect servers and clear the cache. The script was written as an analog to apt-get and can retrieve files and dependencies from redirect servers for Unreal Tournament servers that have a file list. Additionally it can move packages downloaded from Unreal Tournament servers from the Cache to their respective directories.

The script can be considered beta. The script has been used and seems to perform well. No documantation is available but a little help text on how to use the script can be displayed. Some options can be configured in an ini.

No further development is intended.

## Installation

Download [upkg](https://github.com/cterveen/upkg) and [uIni](https://github.com/cterveen/uini) and save them in any Perl module directory.

Save all files into a directory.

Configure uz-get.ini with the correct paths for your Unreal Tournament installation and one or more repositories.

## Use

`uz-get -i CTF-2on2-Crates.unr` 

For additional options see  
`uz-get -h`

## Credits

Written by Christiaan ter Veen <https://www.rork.nl/>

Depends on:

- upkg https://github.com/cterveen/upkg
- uIni https://github.com/cterveen/uini

## License

Copyright (c) 2008-2011 Christiaan ter Veen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software with the restrictions of the Unreal(r) Engine End User License Agreement but no restrictions otherwise.

The Unreal(r) Engine End User License Agreement states the following: You may Distribute an integration of a programming language other than C++ for the Licensed Technology, but if you do, the integration must be Distributed free of charge to all Engine Licensees, must be available in source code form (including, but not limited to, any compiler, linker, toolchain, and runtime), and must permit Distribution free of charge, on all platforms, in any Product.

Otherwise, the software can be dealt with without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, and/or sublicense copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
