# AR_ImgDetect

Image detection combined with AR.

It was a bonus for [AR_DOA](https://github.com/BLKKKBVSIK/AR_DOA) School Project at Bonch-Bruevich Saint Petersburg State University of Telecommunications (SPBSUT) . 

Russian: Санкт-Петербургский государственный университет телекоммуникаций (СПбГУТ) . 

## Goal

The goal was to provide a bonus to our school project and, also test other function from ViroAR Library.


## Examples

Demo of the fonctionnal application:

Personnal conclusion:
The image fetched was made by myself, the library has some trouble to find the picture if it's upside down or if the picture is mainly of 1 color.

![ARDemo](https://thumbs.gfycat.com/IdioticFailingGenet-size_restricted.gif)

## Install

Libraries used:
[ViroAR by ViroMedia](https://viromedia.com/viroar)

Prerequisites:

Android -> An ARCore supported device .

iOS -> iOS Device with A9 chip or higher and running iOS 11 or higher . 


Make sure to have npm and node installed on your pc . 

MACOS:
https://blog.teamtreehouse.com/install-node-js-npm-mac

LINUX:
https://blog.teamtreehouse.com/install-node-js-npm-linux

WINDOWS:
https://blog.teamtreehouse.com/install-node-js-npm-windows

--------------------------------------------------------

Register into ViroMedia and generate a new API Key
Edit `App.js` under your project.

You can also change the image detected by the application by switching `logo.png` to another picture in the `js/res/` folder.


Download the ViroMedia testbed app:

iOS:
https://itunes.apple.com/us/app/viro-media/id1163100576?mt=8

Android:
https://play.google.com/store/apps/details?id=com.viromedia.viromedia

Now, make sure ngrok is also installed and run the command `npm install` .

After the installation is completed you can run `npm start`, the ngrok link should appear in the console.
You just have to copy it to the ViroMedia testbed app.

