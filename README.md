
# Android Easing Functions [![Build Status](https://travis-ci.org/daimajia/AnimationEasingFunctions.svg?branch=master)](https://travis-ci.org/daimajia/AnimationEasingFunctions)

This project is originally from my another project, [AndroidViewAnimation](https://github.com/daimajia/AndroidViewAnimations), which is an animation collection, to help you make animation easier.

While, I was still unsatisfied with the animation effect.

So, I started to explore how to make it more and more real.

I found the [Easing Functions](http://easings.net/) made by [Robert Penne](http://robertpenner.com/), then, I implemented Easing Functions and make a lovely demo.

## Demo

![](http://ww4.sinaimg.cn/mw690/610dc034jw1ehuzoul4h8g20b00gmh9s.gif)

## Usage

> `NineOldAndroids` has been removed since version 2.0. Thanks Jake Wharton.

**minSdkVersion: 11**

### Step 1

Gradle

```groovy
implementation 'com.daimajia.easing:library:2.4@aar'
```
or maven

```xml
<dependency>
    <groupId>com.daimajia.easing</groupId>
    <artifactId>library</artifactId>
    <version>2.4</version>
    <type>apklib</type>