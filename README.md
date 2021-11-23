Inno Setup script for installing otvdm

This installer installs otvdm\winevdm at a specified folder and adds
an registry key which points to the installation directory.

This was primarily made for having a more straightforward way to add wow16 support in [ReactOS](https://github.com/reactos/reactos).

The otvdm files are from the [winevdm](https://github.com/otya128/winevdm) repository.

Note use Inno Setup 5 if you want to build an installer that will run in ReactOS.
