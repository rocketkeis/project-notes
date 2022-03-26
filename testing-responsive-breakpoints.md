---
title: Testing Responsive Breakpoints
last updated: Mar 26, 2022
---

# Testing Responsive Breakpoints

Googling "responsive breakpoints 2022", one of the results showed the common breakpoints:

* 320px — 480px: Mobile devices
* 481px — 768px: iPads, Tablets
* 769px — 1024px: Small screens, laptops
* 1025px — 1200px: Desktops, large screens

### Devices and their viewport sizes

| Breakpoint notes | Viewport size | Device |
|-|-|-|
|                | 320 x 480   | iPhone 4
| 01 Min mobile  | 320 X 568   | iPhone 5/SE
|                | 375 x 667   | iPhone 6/7/8
|                | 375 x 812   | iPhone X
| 02 Mobile      | 390 X 844   | iPhone 12 Pro
|                | 414 X 736   | iPhone 6/7/8 Plus
|                | 414 x 896   | iPhone XR
| 03 Max mobile  | 480 x 800   |
| 04 Min tablet  | 481 x 800   |
| 05 Max tablet  | 768 x 1024  | iPad Mini
|                | 820 x 1180  | iPad Air
|                | 1024 x 1366 | iPad Pro

Viewport sizes based from Chrome dev tools.


| Breakpoint notes | Resolution | Device |
|-|-|-|
| 06 Min laptop  | 769 x 600   |
|                | 800 x 600   | _Classic_
| 07 Max laptop  | 1024 x 768  |
| 08 Min desktop | 1025 x 768  |
| 09 Max desktop | 1200 x 800  |
|                | 1280 x 800  | 13- to 15-inch (16:10)
|                | 1366 x 768  | 13- to 15-inch (16:9)
|                | 1440 x 961  | My personal laptop*
| 10 Work laptop | 1536 x 864  | My work laptop*
|                | 1900 x 1080 | My monitor*

*Based on [whatismyscreenresolution.net](http://whatismyscreenresolution.net/)

### Tools

* Chrome dev tools - One of my work besties. Those with breakpoint notes in the tables above are added in the list of Emulated Devices so that I can easily access or switch between them.

* [Window Resizer Chrome extension](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en)

* [What is my screen resolution?](http://whatismyscreenresolution.net/)

* [mattkersley/Responsive-Design-Testing](https://github.com/mattkersley/Responsive-Design-Testing) - I forked it and have a revised version using the primary mobile and tablet sizes I need to view for my project.
