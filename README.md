# libsecp256k1-LazyBuilds
Basic repo with periodic Windows builds of libsecp256k1 (For use with Electrum when running directly from source) They have been built with the make_libsecp256k1.sh that comes bundled with Electrum which produces libsecp256k1-0.dll

These files have been tested to "just work" with Electrum when running from source. The are provided mostly for those who want them for recovery, testing or development.

_If you are not using a hardware wallet, or are using them for other security critical purposes, please consider building your own copies from soruce..._

## Installation:

Place the appropriate file in the /electrum folder within your Electrum source.

If you are running Windows 10, 64bit, with 64 bit python installed, the you want the file in the x64 folder. If you have a 32bit version of python installed, use the file from the x86 folder.

If you choose the wrong file, you will get an error that looks something like this:

`E | ecc_fast | libsecp256k1 library failed to load. exceptions: [OSError(8, '%1 is not a valid Win32 application', None, 193, None), OSError(8, '%1 is not a valid Win32 application', None, 193, None)]
Error: Failed to load libsecp256k1.`

## File Checkums:
**x64**
Name: libsecp256k1-0.dll
Size: 743813 bytes (726 KiB)
SHA256: 5B58FCE549E4CE492578477C479E118D4D809F65F7B53EB3868A4F5A2A6444A9

**x86**
Name: libsecp256k1-0.dll
Size: 724375 bytes (707 KiB)
SHA256: 97B91792DC97BCEFF7431BBD7D6F35108943751482A17F80462A702667C900C1




