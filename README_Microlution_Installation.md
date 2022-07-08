More documentation to come.....


# Install Methods

## Standalone 
If you don't have MATLAB.

First-time users should run the `Installer.exe` file, it will walk you through downloading the MATLAB Runtime and install the needed app components. Admin rights are required to install it the first time. There is a workaround on the [MATLAB documentation website](https://www.mathworks.com/help/compiler/install-the-matlab-runtime.html) if needed.

Updates can run the installer again or just drop the files in the `for_redistribution_files_only.zip` into the original installation directory.

All needed files will be created and live within the install directory in %appdata%.


## App Packager
If you have MATLAB.

Download the `.mlappinstall` file from the latest release. Run it to install the app within MATLAB.

It will appear in the "My Apps" toolbar in MATLAB.

All needed files will be created and live within the working directory.


## Run From Source

Clone the repository, or pull to update to the latest.

Run `GUI_JobWizard.m`

Needed files will be created in the working directory, such as settings, logs, and output folder.


