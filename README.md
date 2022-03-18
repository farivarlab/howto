# howto

## Setup UbuntuFL wsl
- get UbuntuFL.tar file (e.g. to ```C:\wsl\UbuntuFL```)
- based on https://docs.microsoft.com/en-us/windows/wsl/use-custom-distro#import-the-tar-file-into-wsl
  - import it (the .tar file does not have to be in InstallLocation)  
    ```
    wsl --import <Distro> <InstallLocation> <FileName>
    wsl --import UbuntuFL C:\wsl\UbuntuFL C:\wsl\UbuntuFL\ubuntu16.04.tar
    ```
  - verify
    ```wsl -l -v```
    should give you something like this  
    <img src="https://user-images.githubusercontent.com/68520323/158100281-77edee78-a14b-4b92-bfe0-783491a8f8d6.png" width=33% height=33%>

- create new user
- 

http://christopher5106.github.io/admin/2018/02/02/configure-windows-10-for-ubuntu.html



## Installation notes
### Ubuntu-20.04
#### simNIBS
##### extra packages to install
- libqt5opengl5
- libqt5opengl5-dev
#### FSL
https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation/Windows#Windows_Subsystem_for_Linux

### UbuntuFL-0.1
#### Packages installed
- simNIBS
- freesurfer
