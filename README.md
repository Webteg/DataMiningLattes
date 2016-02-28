# DataMiningLattes
# Introduction
DataMining Lattes is a python App to extract and parse Curriculum lattes pages.

#How it works
Since 2015, Lattes platform started to use captchas, therefore massive extraction of Curriculum Lattes are not more allowed.
In this small project, I used selenium to enter and get captcha image. After that, I trained tesseract-ocr, and now it is possible to break captchas easily to extract any lattes info as it was before 2015.

#Installing Tesseract
First you have to download Leptonica:
```bash
git clone git://github.com/danbloomberg/leptonica.git
```
A detailed link of how to install Leptonica is here:
[a link](http://www.leptonica.org/source/README.html)
