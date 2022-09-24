### Overview
gdrive is a command line utility for interacting with Google Drive. Based on [gdrive](https://github.com/prasmussen/gdrive)

### Installation
- Download the latest gdrive binary file according to your **Architecture / OS** from [Here](https://github.com/usmanmughalji/gdriveupload/releases)
- Rename file first:
  - Example: **gdrive-linux-x64** to **gdrive**
```
mv gdrive-linux-x64 gdrive
```
- Add permission to the file:
```
chmod +x gdrive
```
- Install in following folder:
  - **Note:** sudo is not necessary, but if you feel it's required for your **os**, then you should use it.
```
sudo install gdrive /usr/local/bin/gdrive
```
- Run the following command to authenticate with your **Google Drive / Team Drive** account:
```
gdrive list
```
### To Uninstall / Remove any Previous Version
- For current version (**Latest**):
  - Removing file:
```
sudo rm -rf /usr/local/bin/gdrive
```
- Locating token file, follow:
```
ls -a ~
cd ~
cd .config
cd gdrive
or
cd ~/.config/gdrive/
```
- Removing token file:
```
rm -rf ~/.config/gdrive/token_v2.json
```
- For previous version (**Old**):
  - Removing file:
```
sudo rm -rf /usr/local/bin/gdrive
```
- Locating token file, follow:
```
ls -a ~
cd ~
cd .gdrive
or
cd ~/.gdrive/
```
- Removing token file:
```
rm -rf ~/.gdrive/token_v2.json
```
### Usage
- Recommended to use the **```gdrive help```** command to learn more about the tool and to use it properly.
- To upload a file directly to the root of the drive:
```
gdrive upload "file.zip"
```
- To upload a single file to a specific folder or directory:
  - **Note:** Below commands works for both **gdrive** and **team-drive** as well
```
gdrive upload -p 0ABCA123456789 "file.zip"
```
- To upload a whole folder or directory:
```
gdrive upload -r -p 0ABCA123456789 "folder-name"
```
### For ROM Developers
```
wget https://raw.githubusercontent.com/usmanmughalji/gdriveupload/master/gdrive && chmod +x gdrive && sudo install gdrive /usr/local/bin/gdrive && gdrive list
```
### Notes:
- I don't own the code or the tool, and I am thankful to all the developers and contributors who have made this wonderful tool.
- In the repository, I have uploaded the **gdrive-linux-x64** which is rename to gdrive.
- If you want to read about the documentation of the tool completely, please visit their [official repository](https://github.com/prasmussen/gdrive).
- I am using the following [source code](https://github.com/msfjarvis/gdrive) for compiling the binaries.
- I am thankful to [hashhackers](https://t.me/HashHackers) and their team, which always bring the best quality of services to their users.

### Credits
- [prasmussen](https://github.com/prasmussen)
- [msfjarvis](https://github.com/msfjarvis)
- [API](https://gitlab.com/GoogleDriveIndex/Google-Drive-Index)