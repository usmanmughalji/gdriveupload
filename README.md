# Update

Compiled with latest go (1.14.2.)/nAdded approved Google API huge thanks to this man https://github.com/ParveenBhadooOfficial for providing approved api.


# About This Tool

Gdrive is a command line utility for interacting with Google Drive.

This is orginally project by https://github.com/gdrive-org/gdrive check this out for more information about this cli based tool.

That tool which i have uploaded and using it's from https://github.com/petrpulc/gdrive/ because this user added the support of Shared Team Drive.

For using this tool on other platforms visit below link.

https://drive.google.com/drive/folders/12GSQhLLdKDdKzq_a-7WOrip5HnFmm1v9 


# Follow Steps To Use This Tool


git clone https://github.com/usmanmughalji/gdriveupload

chmod +x gdrive

sudo install gdrive /usr/local/bin/gdrive

gdrive list

Than do authenication by clicking on link and enter code

-p means parent directory

# For Uploading to Shared Team Drive

gdrive upload -p File ID Of Shared Drive or Folder ID ./image.png

Example

gdrive upload -p 0AAlxxxxxxxxxxxxx ./image.png

# For Uploading Directly to G-Drive

gdrive upload ./file.txt

# For Uploading to G-Drive Directory

gdrive upload -p 0AAlxxxxxxxxxxxxx ./file.txt

# Only For ROM Developers

wget https://raw.githubusercontent.com/usmanmughalji/gdriveupload/master/gdrive && chmod +x gdrive && sudo install gdrive /usr/local/bin/gdrive && gdrive list

