# **About The Tool** : 
Quite simply, this tool extracts the EXIF ​​file from the image 
and displays the information inside it if it exists or if it does not exist, 
the tool is useless.
The tool also scans the EXIF ​​file, which contains a lot of information.

# **Get Started:** 

`git clone https://github.com/Mohaned2023/ImageInfo.git`

`cd ImageInfo`

`pip install -r requirements.txt`

`python main.pyc -h`  or  `python3 main.pyc -h`

# **usage :**
1) -h or --help to see the help.
2) -p or --path to set path image.
3) -i or --info to to see image info.
4) -d or --delete to delete image info.
5) -pe or --path-exit to set the exit path for new image from which the EXIF file has been deleted.

## **For Example :**
help - `python main.pyc -h`

info - `python main.pyc -p "./myFolder/myImage.png" -i`

delete and save to main path - `python main.pyc -p "./myFolder/myImage.png -d`

delete and save to your path - `python main.pyc -p "./myFolder/myImage.png" -d -pe "./myFolder" `


# **Written by** :
> ___Mohaned Sherhan ~ 2023___

# **My accounts on :**
>[X](https://twitter.com/MrX2023M)

>[instagram](https://instagram.com/mr.lxzl)

>[Github](https://github.com/Mohaned2023)
