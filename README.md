<div align="center">

# Kadnavbar

Responsive navbar with zero bootstrap/jQuery dependencies and css cross-bow nav button animation.

[![Made in Nigeria](https://img.shields.io/badge/made%20in-nigeria-008751.svg?style=flat-square)](https://github.com/acekyd/made-in-nigeria)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-red.svg?style=flat-square)](http://makeapullrequest.com)

![code snapshot](images/kadnavbar-basic-snapshot.png)

</div>


## Features

* No jQuery or external js libraries
* Completely independent 
* Doesn't break main stylesheet
* Super responsive
* All animations are css animations
* Can accomodate various range of nav brand size
* Semantic html markup
* Extra support for [font-awesome](https://fontawesome.com/) icons

## Demo

Demo preview is available on the [github page demo of the repo](https://kadetxx.github.io/kadnavbar/) (detailed documentation coming soon on this page as well). For a quick start, see usage guide below.

## Quick Usage Guide

You can either download asset folder and link up in your html code or link to files directly from github servers.

### Using github servers

1. Copy and paste the css link below into your index.html file in the header. This link should come before your main style link in your header in order to allow navbar edits in your main css file. 

```html
<link rel="stylesheet" href="https://github.com/kadetXx/kadnavbar/blob/master/kadnavbar/css/styles.css">
```
2. Copy and paste this js script link in your index.html file just before the closing body tag.

```html
<script src="https://github.com/kadetXx/kadnavbar/blob/master/kadnavbar/js/script.js"></script>
```
3. Copy the default html structure for the header navbar and paste inside your index.html file just after the opening body tag.

```html
<header class="kad-header">

    <div class="kad-mobile-container">

      <div class="kad-header-logo">
        <a class="kad-link" href="#" title="kadnavbar">Kadnavbar</a>
      </div>

      <div class="kad-menu-button">
        <div class="kad-menu-bar kad-menu-bar-one"></div>
        <div class="kad-menu-bar kad-menu-bar-two"></div>
        <div class="kad-menu-bar kad-menu-bar-three"></div>
      </div>

    </div>

    <nav class="kad-nav">
      <ul class="kad-nav-list">
        <li class="kad-nav-list-item"><a class="kad-link kad-list-link" href="#">Home</a></li>
        <li class="kad-nav-list-item"><a class="kad-link kad-list-link" href="#">About</a></li>
        <li class="kad-nav-list-item"><a class="kad-link kad-list-link" href="#">Contact</a></li>
        <li class="kad-nav-list-item"><a class="kad-link kad-list-link" href="#">Support</a></li>
      </ul>

    </nav>

  </header>

```
4. Save changes.

### Downloading Source files

1. Download kadnavbar zip file here.
2. Unzip file into your root project folder.
3. Copy and paste the css stylesheet link below into your index.html file in the header.

```html
<link rel="stylesheet" href="kadnavbar/css/styles.css">
```
4.  Copy and paste this js script link in your index.html file just before the closing body tag.

```html
<script src="kadnavbar/js/script.js"></script>
```
5. Copy the default html structure as specified in the github server method above.
6. Save changes.

## Icons and buttons

Kadnavbar also supports extra buttons or icons at the right side of the header (desktop view). To use this feature, simply copy the code below and paste it inside the header template provided above just before the closing `nav` tag. Replace the `i` links with icon links of your choice.

```html
<div class="kad-nav-extras">
        <button class="kad-nav-button">Download</button>
        <div class="kad-nav-icons">
          <a href="#"><i class="fab fa-github"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-codepen"></i></a>
          <a href="#"><i class="fas fa-hashtag"></i></a>
          <a href="#"><i class="fas fa-envelope"></i></i></a>
        </div>
</div>
```
Don't forget to include the icon library stylesheet link in your html `head`. By default, kad nav bar is set to use font awesome icons (I recommend this) so you can just copy the icon library stylesheet link below and paste it inside your html `head` tag.

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css">
```
## Transparent/Light Version

The default Kadnavbar has a dark background color which can abe switched by changing the background-color property of the `.kad-header` class. I decided to add a feature for a transparent navbar for much lighter background colors. You can make the navbar transparent by adding the `kad-header-transparent` class to the `header` tag as shown below.

```html
<header class="kad-header kad-header-transparent">
```

## Licensing 

This project is an opensource project under the MIT license and can be used for personal or commercial use, can be distributed and also modified. [View full license here](https://github.com/kadetXx/kadnavbar/blob/master/license.md).

## Contributing

This project is open to collaborators and contributors from all over the world. Kindly report an issue or fork repo, edit and create a pull request.

## Author

Collins Enebeli

> Originally inspired by a failed attempt to use bootstrap's navbar without importing the full bootstrap's styling to the whole webpage.
