## Project name

uz-get

## Description

uz-get is a Perl script intended to download packages from Unreal Tournament redirect servers and clear the cache. The script was written as an analog to apt-get and can retrieve files and dependencies from redirect servers for Unreal Tournament servers that have a file list. Additionally it can move packages downloaded from Unreal Tournament servers from the Cache to their respective directories.

The script can be considered beta. No documantation is available but a little help text on how to use the script can be displayed. Some options can be configured in an ini.

The script has been used and seems to perform well. Further development is not intended.

## Installation

Download [upkg](https://github.com/cterveen/upkg) and [uIni](https://github.com/cterveen/uini) and save them in any Perl module directory.

Save all files into a directory.

Configure uz-get.ini with the correct paths for your Unreal Tournament installation and one or more repositories.

## Use

`uz-get -i CTF-2on2-Crates.unr` 

For additional options see  
`uz-get -h`

## Credits

Depends on:

- upkg https://github.com/cterveen/upkg
- uIni https://github.com/cterveen/uini

## License

To be decided, but consider it free to use, modify and distribute.
