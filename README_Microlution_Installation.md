More documentation to come.....


# Install Methods

## Standalone 
If you don't have MATLAB.

First-time users should run the `Installer.exe` file, it will walk you through downloading the MATLAB Runtime and install the needed app components. Admin rights are required to install it the first time. 

If you can't get admin access, there is a workaround on the [MATLAB documentation website](https://www.mathworks.com/help/compiler/install-the-matlab-runtime.html) if needed. The pre-installed file can be downloaded from the General section of the publishing location, called MATLAB Runtime v912. Currently, it must match version 9.12 to support R2022a. Future versions may require a later version of the runtime. The readme.txt file in the installed file location says which version is required.

Updates can run the installer again or just drop the files in the `for_redistribution_files_only.zip` into the original installation directory.
Updates to Job Wizard should be careful not to overwrite your `settings.mat` file or any `Starting Points`

All needed files will be created and live within the install directory in %appdata%.


## App Package
If you have MATLAB.

Download the `.mlappinstall` file from the latest release. Run it to install the app within MATLAB.

It will appear in the "My Apps" toolbar in MATLAB.

All needed files will be created and live within the working directory.


## Run From Source

Clone the repository, or pull to update to the latest.

Run the main .mlapp file for the project.

Needed files will be created in the working directory, such as settings, logs, and output folder.


