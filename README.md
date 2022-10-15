# PySetup Installation Utility

PySetup is a setup program for Python scripts.

PySetup works by converting the `.py` script into one binary, containing libraries
(DLLs/Shared Libraries/Python Packages),

## Features

* Extensible via Python scripting. Themes will be added soon.
* Create custom pages.
* Apps are compiled into a single binary, so PySetup supports systems with or without Python.
* DLLs (Win32 libraries) and shared objects (Unix libraries) are packed automatically.
* Command-line installer is available to install programs on a server.
* Automatically packs your modules.

## Generation

Download the PySetup Toolkit via one of these methods:

* **GitHub Releases**: GitHub Releases is a GitHub functionallity that offers the ability to package
  software for any operating system. GitHub Releases is the main host for PySetup. It is recommended
  to download PySetup through GitHub Releases.
  
  [**Download through GHR...**](https://github.com/TylerMS887/pySetup/releases/latest)

* **GitHub Actions**: If you would like to test nightly builds of PySetup, download the PySetup toolkit through
  GitHub Actions. Just scroll to "Artifacts" and download the binary for your OS. (For FreeBSD, PySetup works
  through Linux binary support.) When reporting issues, always test on this version.
  
  > **Warning**: You need to be logged into GitHub to download through GitHub Actions.
  
  [**Login to GitHub...**](https://github.com/login)
  
  After logging in, download the binary:</br>
  [**Download through GHA...**](https://github.com/TylerMS887/pySetup/actions)

