---
published: true
title: RGB2Grayscale Converter
layout: post
date: '2017-01-03 16:37'
tag: Grayscale
headerImage: false
projects: true
hidden: true
description: This is a simple gui java project for image manipulation
category: project
author: Himanshu Ray
externalLink: false
---
## RGB2Grayscale Converter

<p>A simple java project to convert a RGB image to its Grayscale version using Swing.

This Project was made using Eclipse Java Neon IDE. It is a very basic Java Gui application to Convert a RGB image to Grayscale version.

The User can choose one or more Files at a time and After successful Completion of code he can get the grayscale version of that image.

For Choosing the File Jfilechooser is used in Project.
</p>
<p>
There are many algorithms available for converting a RGB image to Grayscale image Like "The lightness method", "The Average Method", "The luminosity method" and many more.

The algorithm i have used in this project is the Average one.

What we have to do is to Simply Get the RGB values of each Pixel in the image and then calculate the average of these pixels. </p>

```
[ R(value)+G(value)+B(Blue)] / 3]

```
<p>Since we converted all the pixels of this Image to its Grayscale shade.

Now will have to just make a copy of the Grayscale version of the image and we have to store it.

This grayscale image of the verion will be simply shown as a output on user Screen using Jframe class.

This was all about the project.</p>

For the source code land to [Github Respo](https://github.com/iamrayofhope/RGB2grayscaleconverter)

<br>

To download the jar file [click here](https://github.com/iamrayofhope/RGB2grayscaleconverter/blob/master/RGB2Grayscale/RGB2Grayscale.jar)

Screenshots :
<br>
<img class="image" src="{{ site.url }}/assets/images/SS1.png" alt="SS 1">

<img class="image" src="{{ site.url }}/assets/images/SS2.png" alt="SS 2">

Thank you :)
