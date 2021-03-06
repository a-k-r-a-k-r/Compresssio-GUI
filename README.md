<p align="center">
  <img src="https://user-images.githubusercontent.com/72680045/102008832-56a57600-3d59-11eb-821a-98b8adabbbc9.png">
  <h2 align="center" style="margin-top: -4px !important;">Streamline/Optimize your Images to save storage space...</h2>
  <p align="center">
    <a href="https://github.com/dhhruv/Compresssio/blob/master/LICENSE">
      <img src="https://img.shields.io/github/license/dhhruv/Compresssio-GUI?color=informational">
    </a>
    <a href="https://www.python.org/">
    	<img src="https://img.shields.io/badge/python-v3.8-informational">
    </a>
    <a href="https://github.com/dhhruv/Compresssio-GUI">
    	<img src="https://img.shields.io/github/v/release/dhhruv/Compresssio-GUI">
    </a>
    <img src="https://img.shields.io/github/downloads/dhhruv/Compresssio-GUI/total?color=important">
  </p>
</p>

# Compresssio:

The above script uses TinyPNG's savvy lossy compression methods to reduce the document size of your JPG/PNG files. This is achieved by specifically decreasing the number of colors in the image, therefore lesser number of bytes are required to store the information. The impact of the script is nearly invisible but it makes an exceptionally enormous effect in file size of the image.

## Image Comparison:

<p align="center">
	<h4 align="left" style="margin-top: -4px !important;">Image 1:</h4>
	<img src="https://user-images.githubusercontent.com/72680045/102686740-9c59b700-420f-11eb-9a83-f88b9e060abb.png">
</p>

<p align="center">
	<h4 align="left" style="margin-top: -4px !important;">Image 2:</h4>
	<img src="https://user-images.githubusercontent.com/72680045/102686743-9d8ae400-420f-11eb-9501-12c42aa4268d.png">
</p>

## Setup (Windows):

1. Install Python
2. Clone this repository
```
git clone https://github.com/dhhruv/Compresssio-GUI.git
```

3. Install, create and activate virtual environment.
For instance we create a virtual environment named 'venv'.
```
pip install virtualenv
python -m virtualenv venv
venv\Scripts\activate.bat
```

4. Install dependencies
```
pip install -r requirements.txt
```

<p align="center">
	<img src="https://user-images.githubusercontent.com/72680045/102932031-8d039380-44c5-11eb-8640-3c0dd9e2ae23.PNG">
</p>
<br>

## How to Get Your API Key !

You can Find your API Key from the Website [https://tinypng.com/developers](https://tinypng.com/developers) after Signing Up and save it somewhere on your PC/Laptop.


## How To Use !
1.	Click SELECT INPUT FOLDER Button to select the INPUT FOLDER which contains all the Images to be Compressed/Optimized.
2.	Click SELECT OUTPUT FOLDER Button to select the OUTPUT FOLDER which will contain all the the Compressed/Optimized Images. (After Compression)
3.	Enter Your API Key from TINYPNG Website. If you don't have one in possession then you can find on this website https://tinypng.com/developers .
4.	Hit the COMPRESS Button and the INPUT FOLDER containing Supported Image Formats will be Compressed and saved in the OUTPUT FOLDER.
5.	Click CLEAR Button to reset the input fields and status bar. (If needed)

## Important Note:

-	**The limit you'll have at first is of 500 images per month on the Free plan. You can change this according to your requirement at [https://tinypng.com/developers](https://tinypng.com/developers)**
-	**Recommended to keep INPUT and OUTPUT Folder different for your ease to differentiate between Optimized and Unoptimized Images.**
-	**This Script is just a Prototype so Metadata is not stored in the Compressed Images from the Original Images.**
-	**Directory Structure in INPUT and OUTPUT Folders may differ but all Supported Images will be saved according to their directories.**
-	**The Authors will not be responsible for any kind of loss of data so it is essential to have a Backup of Original Data placed in the Input Folder. Read the [LICENSE](https://github.com/dhhruv/Compresssio-GUI/blob/master/LICENSE) for more information.**

## Contributors:

<a href="https://github.com/dhhruv/Compresssio-GUI/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=dhhruv/Compresssio-GUI" />
</a>

## Image Credits:
- [Unsplash](https://unsplash.com/)

