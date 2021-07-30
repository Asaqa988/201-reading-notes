# Video and Audio APIs
HTML5 comes with elements for embedding rich media in documents —  (video and audio) — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.
### Prerequisites:	JavaScript basics (see first steps, building blocks, JavaScript objects), the basics of Client-side APIs
### Objective:	To learn how to use browser APIs to control video and audio playback.

## The HTMLMediaElement API

Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both (audio and video) elements, as the features you'll want to implement are nearly identical. Let's go through an example, adding features as we go.

## Implementing the JavaScript
We've got a fairly complete HTML and CSS interface already; now we just need to wire up all the buttons to get the controls working.

1- Create a new JavaScript file in the same directory level as your index.html file. Call it custom-player.js.

2- At the top of this file, insert the following code:

const media = document.querySelector('video');
const controls = document.querySelector('.controls');

const play = document.querySelector('.play');
const stop = document.querySelector('.stop');
const rwd = document.querySelector('.rwd');
const fwd = document.querySelector('.fwd');

const timerWrapper = document.querySelector('.timer');
const timer = document.querySelector('.timer span');
const timerBar = document.querySelector('.timer div');

3- Next, insert the following at the bottom of your code:

# Images

Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.
#### You can also achieve several interesting effects using
#### background images. In this chapter you will learn how to:

- Specify the size and alignment of an image using
- Add background images to boxes
- Create image rollovers in CSS
![](https://th.bing.com/th/id/R.282e775ecefe5676af10df1532850512?rik=2k18udza72%2frQg&pid=ImgRaw)

## Centering images in CSS 

By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block.

- Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:
1: On the containing element, you can use the text-align property with a value of center.
2: On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

You can specify class names that allow any element to be centered, in the same way that you can for the dimensions or alignment of images.
![](https://th.bing.com/th/id/R.dc847b264230669a311f5b4aa3e61b94?rik=GNQJDxR%2f9aFlNg&pid=ImgRaw) 


# Flash, Video& Audio

Flash is a very popular technology used to add animations, video, and audio to websites. This chapter begins by looking at how to use it in your web pages.

## How Flash Works

Since the late 1990s, Flash has been a very popular tool for creating animations, and later for playing audio and video in websites. 
Whether you are creating an animation or a media player in Flash, the files you put on your website are referred to as Flash
movies.

If you want to create your own Flash movie, you need to purchase the Flash authoring environment from Adobe.

There are, however, several companies that offer Flash animations and slideshows,
as well as video and audio players that you can use without purchasing this tool.

When you create a Flash file in the Flash authoring environment, it is saved with the .fla file extension. In order to use this file on a web page it has to be saved in a different format known as SWF. (It has the .swf file extension.)

When you export the movie into SWF format, Flash creates code that you can use to embed the Flash movie in your page.

- Traditionally, this code used the HTML <object> and <embed> tags. However, now it is more common to use JavaScript.
To view Flash, browsers need to use a plugin (an extra piece of software that runs in the browser) called the Flash Player.
Statistics commonly indicate that 98% of browsers on desktop computers have the Flash plugin installed. (The percentage of mobiles and tablets with it is much less.) There is not space in this book to teach you how to create Flash movies (there are many books devoted to that one topic), but this chapter will show you how to add Flash movies to your site.
  ![](https://masterherald.com/wp-content/uploads/2014/10/Adobe-Flash-Player.jpg)
