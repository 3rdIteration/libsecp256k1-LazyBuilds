# libsecp256k1-LazyBuilds
Basic repo with periodic Windows builds on libsecp256k1 (For use with Electrum)

These files have been tested to "just work" with Electrum when running from source.

Place the appropriate file in the /electrum folder within your Electrum source.

If you are running Windows 10, 64bit, with 64 bit python installed, the you want the file in the x64 folder. If you have a 32bit version of python installed, use the file from the x86 folder.

If you choose the wrong file, you will get an error that looks something like this:

E | ecc_fast | libsecp256k1 library failed to load. exceptions: [OSError(8, '%1 is not a valid Win32 application', None, 193, None), OSError(8, '%1 is not a valid Win32 application', None, 193, None)]
Error: Failed to load libsecp256k1.
