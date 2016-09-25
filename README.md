# Toaster
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/mkiisoft/KeySaver) [![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=1.0&x2=0)](https://github.com/mkiisoft/Toaster/toaster.aar) [![Android](https://img.shields.io/badge/language-Android-blue.svg)](https://github.com/mkiisoft/Toaster)
=================
Toaster it's a super simple Toast but with a listener to know when the message on screen is gone.

# Install and Usage

## Android Studio:

- Put toaster.aar over "libs" folder.
- File > New > New Module > Import .JAR/.AAR Package
- Select toaster.aar from the "libs" folder and press Finish.

## How to use:

``` 
Toaster.getInstance().makeText(context, "your custom message", Toast.LENGTH_SHORT, new OnToasterFinish() {
                @Override
                public void finish() {
                    // Your code over here after the Toast
                }
            });
```
