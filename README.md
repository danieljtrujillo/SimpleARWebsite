# SimpleARWebsite
 Simple repo for quickly building a website that implements Google Model Viewer for viewing GLB and USDZ models on the web, and in AR

### INSTRUCTIONS

1) Pull/download codebase

2) Add the models you want to display to the 'assets' folder in GLB format (optimally less than 10MB per file) 

3) Create your model icons and replace the images in the 'images' folder

4) Open index.html and change the 'NAME OF YOUR WEBSITE' to reflect your site name

5) Change the names of the item icon files from "images/portfolio/item1.png" to whatever you named your files (or just name your icon images 'item1.png' etc)

6) Change '< h 3 >ITEM 1< / h 3 >' to reflect whatever name you want to appear on your website

7) Enter a BRIEF description of your item, if it is too long, you might have to reformat in the CSS

8) Change 'item1.html' to reflect the name of your item if you wish (if you change this, you have to change the name of the associated html file to exactly match this change)

9) In 'item1.html' edit 'src="./assets/item1.glb"' to reflect the name of your file (or rename your file to item1.glb)

10) Change 'ios-src="./assets/ios/item1.usdz"' to match your usdz file (or leave it the same, and change your files name) - NOTE: there is an auto conversion option in model viewer, but the auto converted USDZ files don't support transparency, so manually converting them is preferred for items with transparency

11)  Change 'alt="ITEM 1"' to whatever name you want associated with your model

12) Upload entire folder to the root of your domain through CPANEL or whatever

### FILES MUST BE GLB AND/OR USDZ OR THEY WILL NOT WORK - NO FBX OR OBJ 

### MODEL VIEWER DOES SUPPORT ANIMATED GLB, I WILL ADD THOSE INSTRUCTIONS UPON UPDATE