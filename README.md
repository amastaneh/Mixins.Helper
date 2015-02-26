# Mixins.Helper

Mixins.Helper is a basic and useful collection of **Less Mixins Functions** that are used to redeuce the work needed to apply styling to elements and cross-browser CSS compatibility. Mixins.Helper comes with a visual studio and microsoft friendly NuGet package.

## <a name="get-started"></a> Get Started (with Visual Studio)
####Step 1
Add [Mixins.Helper NuGet](https://www.nuget.org/packages/Mixins.Helper/) to your project

    PM> Install-Package Mixins.Helper

####Step 2
Import Mixins.Helper with this line in top of your less

    @import "mixins.helper.less";
    
####Step 3
After press `.` you can find out your Mixins from Visual Studio intelliSense box.

## <a name="documentation"></a> Documentation
Smaple of Mixins Helepr

01. **[.left](#)**
02. **[.right](#)**
03. **[.center](#)**
04. **[.fullscreen](#)**
05. **[.hide()](#)**
06. **[.edge-less](#)**
07. **[.no-select](#)**
08. **[.border-radius(@radius: 0)](#)**
09. **[.border-radiuses (@topright: 0, @bottomright: 0, @bottomleft: 0, @topleft: 0)](#)**
10. **[.text-overflow(@type: ellipsis)](#)**
11. **[.truncate](#)**
12. **[.text-shadow (@shadow: 0 1px 3px rgba(0, 0, 0, 0.25))](#)**
13. **[.box-shadow(@shadow: 0 1px 3px rgba(0,0,0,.25))](#)**
14. **[.drop-shadow (@x: 0, @y: 1px, @blur: 2px, @spread: 0, @alpha: 0.25)](#)**
15. **[.inner-shadow (@x: 0, @y: 1px, @blur: 2px, @spread: 0, @alpha: 0.25)](#)**
16. **[.box-sizing (@type: border-box)](#)**
17. **[.opacity (@opacity: 0.5)](#)**
18. **[.gradient (@startColor: #eee, @endColor: white)](#)**
19. **[.horizontal-gradient (@startColor: #eee, @endColor: white)](#)**
20. **[.animation (@name, @duration: 300ms, @delay: 0, @ease: ease)](#)**
21. **[.transition (@prop: all, @time: 1s, @ease: linear)](#)**
22. **[.rotate (@deg)](#)**
23. **[.scale (@factor)](#)**
24. **[.skew (@deg1, @deg2)](#)**
25. **[.translate (@x, @y: 0)](#)**
26. **[.translate3d (@x, @y: 0, @z: 0)](#)**
27. **[.perspective (@value: 1000)](#)**
28. **[.transform-origin (@x: center, @y: center)](#)**

## <a name="license"></a> License
This project is dedicated to public and is free for all uses, commercial or otherwise.
