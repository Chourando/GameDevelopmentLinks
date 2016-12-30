# Game-Development Links
This is a collection of useful game-development links including, but not restricted to, development with MonoGame.

During the process of developing our game I came across a large variety of websites that I found very useful.  
This page is a collection of all of them baring a short description. I will check in every month or so and update this list accordingly.  
Let me mention that I didn't record those links in any particular order and that the sites, I link to in this section, may contain much more than the description of the link suggests. Chances are that I didn't even look through each and every page of every single site before finding it helpful and bookmarking it. These are just the pages I found searching for solutions for the problems in the various fields of interest you inevitably stumble over when starting to write a game.  

I tried to sort every link-table it in a way that should benefit your learning curve (most complex subjects last).  

**If you want to contribute just fork this repo, make changes and then a pull request.**  

***Contributions are welcome!***  

**Don't forget to star this repo.**  

# Table of Contents
> * [Theory](#theory)
* [Link Lists](#link-lists)
* [Tutorial Sites](#tutorial-sites)
    * [Lookup Tables](#lookup-tables)
    * [Mathematics And Stuff](#mathematics-and-stuff)
    * [Programming Guides](#programming-guides)
      * [General](#general)
      * [AI](#ai)
      * [XNA](#xna)
      * [Graphics And Effects](#graphics-and-effects)
      * [Spatial Partitioning](#spatial-partitioning)
      * [HLSL Shaders](#hlsl-shaders)
      * [Audio](#audio)
* [Practice](#practice)
    * [Components](#components)
    * [Libraries](#libraries)
      * [Game Engines](#game-engines)
      * [Networking](#networking)
      * [Connectors](#connectors)
    * [Tools](#tools)
    * [Artistic Material](#artistic-material)
      * [Graphics](#graphics)
      * [Fonts](#fonts)
      * [Sounds](#sounds)

# Theory

## Link Lists
Here are other link-lists to browse.  

* [**Awesome-MonoGame**](https://github.com/aloisdeniel/awesome-monogame) - This one contains a large list of MonoGame related projects on GitHub. Thx to the awesome Alois Deniel.
* [**The Big List Of Indie Game Marketing**](http://www.pixelprospector.com/the-big-list-of-indie-game-marketing/) - On this page you will find a collection of handpicked articles about indie game marketing.

## Tutorial Sites
No specific order.  

* [**Shawn Hargreave's Blog**](http://blogs.msdn.com/b/shawnhar/) - This is a must-read for every XNA developer. The blog of the Master himself.
* [**XNAdevelopment**](http://www.xnadevelopment.com/tutorials.shtml) - Great beginners tutorials around XNA game development.
* [**Catalin Zima's Blog**](http://www.catalinzima.com) - You should all know this one (and you will, I promise). Good examples. I would say that most of the content in here is for the advanced beginner.
* [**Riemer's XNA Tutorials**](http://www.riemers.net/) - Flood of useful tutorials. I found it a bit untidy in a way.
* [**digitalerr0r**](http://digitalerr0r.wordpress.com/tutorials/) - HLSL tutorials for every level of expertise. Nice guy but sort of retired, sadly.
* [**Kyle Schouviller's Blog**](http://www.kyleschouviller.com/) - Good tutorials. Focus on content and tooling.
* [**RB Whitaker's Wiki**](http://rbwhitaker.wikidot.com/xna-tutorials) - Extremely versatile. Covers almost every aspect of XNA game development. Many thanks.
* [**Threading in C#**](http://www.albahari.com/threading/) - A must-read for every programmer.
* [**XNA Game Tutorials**](http://xnatd.blogspot.co.at/) - Some XNA game tutorials (2D collision, etc…)

## Lookup Tables
This section contains tables that I found useful during game-development.  

* [**Color Charts**](http://www.kyleschouviller.com/xna/xna-color-charts/) - You want to set a color, but you can't see it?  This site has proven most useful for me. There is not a single day that I don't visit it. It contains all the named colors you may use directly in XNA (or windows respectively), sorted the way you want.  He has some more stuff going on at his blog, but frankly I didn't have the time to look into it.  

## Mathematics And Stuff
This section contains articles about mathematical problems. You can't do without.  

* [**Trajectory Calculations**](http://stackoverflow.com/questions/966935/trajectory-math-c-sharp) - Want your bullet to fly the right way?  These links show you how to do the necessary math for a 3D trajectory.
* [**Solving Ballistic Trajectories**](https://blog.forrestthewoods.com/solving-ballistic-trajectories-b0165523348c#.pz7p5pej7) - Nice article that contains all the math and explains it very well. Features a GitHub repo containing all the code.
* [**Ballistic Trajectory**](http://www.gamedev.net/topic/333044-does-anybody-have-a-simple-ballistic-trajectory-algorithm-i-can-use/)
* [**Curve-Path**](http://stackoverflow.com/questions/3273396/animate-sprite-along-a-curve-path-in-xna)
* [**Calculate a bounce-angle**](http://stackoverflow.com/questions/573084/how-to-calculate-bounce-angle) - Want your ball to bounce off the wall?  This StackOverflow topic shows you how to do the necessary math.  
* [**Collision Detection Overview in XNA**](http://msdn.microsoft.com/en-us/library/bb313876%28v=xnagamestudio.20%29.aspx) - You want the monster to die, when you hit it?  This is a good and very general overview. It describes the procedure using XNA-datastructures (which isn't always the best choice), but I think that this is a "must read".  
* [**Line Intersection**](http://community.topcoder.com/tc?module=Static&d1=tutorials&d2=geometry2) - You have intersecting lines but you don't know the intersection point?  Helpful formulas when wanting to know the intersection-point of lines in general.  
* [**Intersection Tests**](http://www.gamasutra.com/view/feature/3383/simple_intersection_tests_for_games.php?page=1) - You want to know the point where the bullet hit the plane?  This is THE site containing an abundance of intersection tests for various geometric primitives. Must read. Thank you very much Miguel Gomez.  
* [**Wiki-page for SAT**](https://en.wikipedia.org/wiki/Hyperplane_separation_theorem) - Good explanation with some helpful diagrams.
* [**Separating Axis Theorem (SAT)**](http://www.metanetsoftware.com/technique/tutorialA.html) - You want to know, if the ray hit the polygon?  By the way: AABB means Axis-Aligned-Bounding-Box.  This is a very interesting and helpful technique (and straight forward).
* [**And another tutorial on the SAT**](http://www.metanetsoftware.com/technique/tutorialA.html) - Great diagrams. Nice read.
* [**SAT - Explained**](http://www.dyn4j.org/2010/01/sat/) - And another one. You should be able to tell that this one is important from the number of articles here. This one has nice diagrams and a really good explanation.
* [**Generating Fantasy Maps**](http://mewo2.com/notes/terrain/) - A site explaining the process of procedurally generating 2D maps with rivers, towns, etc.
* [**Island Generator**](http://exupero.org/hazard/post/islands/) - A nice tutorial on how to procedurally generate islands.

## Programming Guides
This section contains tips about how to structure your programs or how to achieve certain tasks necessary for game-deployment.

### General
* [**Shadow-Copying of applications**](http://www.codeproject.com/Articles/29961/Shadow-Copying-of-Applications) - You want your installer to delete itself in windows?  You might come to a point where you'll end up writing your setup or updating your application, where you want to unload a program, that is currently running. In general that's not easily possible, but this project might help. We circumvented the issue by using a WIX setup (you are able to run programs before and afterwards that are not present on the disk, but in the GAC, which is very nice; We deleted the install-directory that way by running a C# deletion-program leaving no trace of the game whatsoever).
* [**Repositioning the cursor**](http://www.pinvoke.net/default.aspx/user32.setcursorpos) - You want to reposition or clamp the windows cursor to or within a window?  On a multi-monitor setup you should prevent the mouse cursor from leaving the monitor your customer is playing on. Here you'll find the proper interop-calls (I'm sure you know this site).
* [**Saving the state of your game**](http://stackoverflow.com/questions/3723287/what-is-a-good-example-of-saving-game-data-in-xna-4-0) - You want to create a save-game?  This is a very quick and elegant method to accomplish this by using XML.  
* [**Get special folders**](http://dn.embarcadero.com/article/32384) - You want to save your save-game in %appdata%?  This page shows you how to get the paths of these special directories regardless of the version of windows your customer is running. Necessary to avoid "no write permission" errors on saving any game-data.  
* [**Multi CPU usage**](http://www.codeproject.com/Articles/7933/Smart-Thread-Pool#Feature5) - You want to use all of the CPU cores on your customer's machine?  You may want to use .NET's new parallels framework or, if you are stuck with an older .NET framework, write one of your own.
* [**'Non-Blocking' synchronization**](http://www.albahari.com/threading/part4.aspx) - You want your code synchronized without blocking waits?  This is the premier-league of multi-threaded-programming. It's very difficult and subtle. Fasten your seatbelts, you're in for some ride.
* [**Decompress DXT textures**](http://www.gamedev.net/topic/467156-dxt-decompress-in-c/) - You want to manually decompress DXT Format Files? There are not many reasons for you to want to do this, but nevertheless. Here it is.  
* [**The Guide To Implementing 2D Platformers**](http://higherorderfun.com/blog/2012/05/20/the-guide-to-implementing-2d-platformers/) - Avery comprehensive guide covering almost all aspects of such an endeavor.
* [**Super Nerd Boy**](http://meyermike.com/wp/?p=160) - Mike's Blog about the experience of making a 2D platformer hero jump the right way.

### AI
* [**Pathfinding.js**](http://qiao.github.io/PathFinding.js/visual/) - A very nice graphical animated presentation of the most common pathfinding algorithms. Very nice way to visualize the differences.
* [**Introduction to A-Star**](http://www.redblobgames.com/pathfinding/a-star/introduction.html) - One of the nicest explainations I've ever read. Interactive too.
* [**A Star Example**](http://blog.two-cats.com/2014/06/a-star-example/) - A good in-depth introduction and the article points to a few production-ready implementations as well.
* [**XNA Game Studio - Pathfinding**](http://xbox.create.msdn.com/en-US/education/catalog/sample/pathfinding) - The good old article about an A-Star implementation from MS.
* [**Path-Finding**](http://www.codeproject.com/Articles/5758/Path-finding-in-C) - You want your hero to find the right way?  This is a good implementation of the A-Star Algorithm. You have to modify it of course, because the garbage collector would kill you in no time, but it's a good starting point.
* [**A-Star algorithm implementation in C#**](http://www.codeproject.com/Articles/15307/A-algorithm-implementation-in-C) - A CodeProject article explaining much about the A-Star algorithm and has a production-ready implementation to download.
* [**Shortest Path**](https://harablog.wordpress.com/2011/09/07/jump-point-search/) - A nice explanation of the Jump-Point-Search algorithm along with illustrations.
* [**EpPathFinding**](http://www.codeproject.com/Articles/632424/EpPathFinding-cs-A-Fast-Path-Finding-Algorithm-Jum) - A nice C# library that comes with a demo, is production ready and implements the Jump-Point-Search algorithm.
* [**SharpNav**](https://github.com/Robmaister/SharpNav) - A complete and portable pathfinding library in C#. MIT license.

### XNA
* [**XNA 3.11 to XNA 4.0 Conversion Cheat Sheet**](http://nelxon.com/resources/xna-3-1-to-xna-4-0-cheatsheet.php) - You want to change XNA 3.1 code to 4.0?  This is a great help when searching for a way to get things done the right way. Many examples.  
* [**Getting a list of supported display modes**](http://blog.gallusgames.com/xna/getting-a-list-of-supported-display-modes-in-xna) - You want to know the resolutions your client's machine supports?  This one is very simple. You just ask XNA and you'll get what you want.  
* [**2D camera with zoom and rotation**](http://www.david-amador.com/2009/10/xna-camera-2d-with-zoom-and-rotation/) - You want to write a platformer?  This is a tutorial on how to implement a proper camera for a 2D game.  
* [**Premultiplied Alpha in XNA**](https://blogs.msdn.microsoft.com/shawnhar/2010/04/08/premultiplied-alpha-in-xna-game-studio-4-0/) - The master Shawn Hargreaves himself explains the reason for the premultiplied alpha values in XNA.  
* [**Premultiplied Alpha**](https://blogs.msdn.microsoft.com/shawnhar/2009/11/06/premultiplied-alpha/) - Another short, but in depht explanation of premultiplied alpha in XNA (and therefore in MonoGame) by Shawn Hargreaves.

### Graphics And Effects
* [**Using shaders**](http://www.xnamag.de/article.php?aid=34) - You want to use shaders and don't know what that is?  Then this site is a good place to start.  
* [**Worl- View- and Projection Transformation Matrices**](http://www.codinglabs.net/article_world_view_projection_matrix.aspx) - A really nice article along with images covering the basics of transformation matrices and how they are commonly used in 3D graphics programming.
* [**3D model drawing guide**](http://www.3dgameprogramming.net/2007/06/04/getting-started-with-xna-drawing-a-3d-model/) - You want to draw a 3D model in XNA?  This guide shows, step by step, how to draw a mesh in XNA. Nicely done, thank you very much.  
* [**2D circles and lines**](http://xboxforums.create.msdn.com/forums/p/7414/200025.aspx) - Want to draw 2D using XNA?Well. Then you're in for a treat!  It's impossible to do that without completely destroying the performance of your game. But since you're inevitably sitting on a high-performance-graphics-workhorse already, you may draw 3D as well. These links show you how.
* [**2D circles and lines**](http://www.bit-101.com/blog/?p=2832)
* [**Premultiplied alpha and alpha-blending**](http://blogs.msdn.com/b/shawnhar/archive/2009/11/06/premultiplied-alpha.aspx) - You want to understand the intricacies of this subject?  Well. Here is the Master of XNA for you. May I present: Shawn Hargreaves...  
* [**Post processing effects**](http://www.float4x4.net/index.php/2011/02/xna-after-effects-part-1/) - You want a bloom-filter?  This tutorial explains the usage and limitations of such an effect.  
* [**Dynamic 2D shadows**](http://www.catalinzima.com/samples/12-months-12-samples-2008/dynamic-2d-shadows/) - You want a flashlight in your 2D game?  This is one of the most popular tutorial-sites out there. I cannot thank Catalin enough for his efforts making this site.  
* [**Depth-Sorting sprites**](https://blogs.msdn.microsoft.com/shawnhar/2009/02/18/depth-sorting-alpha-blended-objects/) - Shawn Hargreaves himself on how to order your sprites before drawing.
* [**The half-pixel offset**](http://drilian.com/2008/11/25/understanding-half-pixel-and-half-texel-offsets/) - In XNA or MonoGame driven games you will see a Vector(.5f, .5f) added on a projection matrix sometimes. Here is why.
* [**And another one on the half-pixel**](https://msdn.microsoft.com/en-us/library/windows/desktop/bb219690(v=vs.85).aspx) - This is Microsofts explanation for it.
* [**Premultiply Alpha for textures loaded via FromStream**](http://scott-franks.com/xna-gpu-premultiply-alpha/) - This is a snippet of code that leverages the GPU to quickly premultiply alpha for textures that are loaded using Texture2D.FromStream which bypasses the preprocessing provided by the content projects.
* [**How to Generate Shockingly Good 2D Lightning Effects**](https://gamedevelopment.tutsplus.com/tutorials/how-to-generate-shockingly-good-2d-lightning-effects--gamedev-2681) - Lightning has plenty of uses in games, from background ambience during a storm to the devastating lightning attacks of a sorcerer. In this tutorial, the author explains how to programmatically generate awesome 2D lightning effects: bolts, branches, and even text.
* [**Drawing Antialiased Lines With OpenGL**](https://www.mapbox.com/blog/drawing-antialiased-lines/) - Nice article describing a method to generate smooth lines using primitives.

### Networking
* [**What Every Programmer Needs To Know About Game Networking**](http://gafferongames.com/networking-for-game-programmers/what-every-programmer-needs-to-know-about-game-networking/) - Very nice and short article describing the basics of game networking.
* [**Making Fast-Paced Multiplayer Networked Games is Hard**](http://www.gamasutra.com/blogs/MarkMennell/20140929/226628/Making_FastPaced_Multiplayer_Networked_Games_is_Hard.php) - Fast-paced multiplayer networked games over the Internet are difficult to develop to a standard where the experience is still fun. This post is from a developer talking about the caveats of network programming. Very interesting read. Covers all the basics / intermediate stuff.

### Spatial Partitioning
* [**Spatial Partitioning**](https://en.wikipedia.org/wiki/Space_partitioning) - Spatial Partitioning - an overview.
* [**CollisionGrid**](https://github.com/UnterrainerInformatik/collisiongrid/blob/master/README.md) - This is the way to go for evenly distributed objects in a small 2D space.
* [**Quadtree**](https://en.wikipedia.org/wiki/Quadtree) - This is the way to go for unevenly distributed objects in a 2D space.
* [**Octree**](https://en.wikipedia.org/wiki/Octree) - This is the way to go for unevenly distributed objects in a 3D space.

### HLSL Shaders
* [**Graphics Pipeline Diagram**](http://www.riemers.net/eng/Tutorials/XNA/Csharp/Series3/HLSL_introduction.php) - You are stuck programming your shader and don't know what happens and when?  This is a very popular site about XNA game development in general. This particular page contains a very useful diagram of the graphics rendering pipeline, that may lighten things up a bit during dark, non-comprehending times (you will have that, I promise).  
* [**HLSL language reference**](http://msdn.microsoft.com/en-us/library/windows/desktop/ff471376(v=vs.85).aspx) - Want to know how HLSL works?  This is Microsoft's HLSL reference. Nothing more, nothing less.  
* [**Wiggle Effect**](http://digitalerr0r.wordpress.com/2009/04/22/xna-shader-programming-tutorial-9-post-process-wiggle/) - Want your background to wiggle?  Then this tutorial is for you. Presented to you by digitalerr0r, a great site for HLSL tutorials.  
* [**Bloom Post Process Filter**](http://digitalerr0r.wordpress.com/2009/10/04/xna-shader-programming-tutorial-24-bloom/) - Want your game to shine?  This tutorial explains the use of post process filters and the bloom filter. Many pictures. Expertly commented. Recommended.  
* [**GPU Driven Terrain Mapping**](http://allenwp.com/blog/2010/05/06/simple-fast-gpu-driven-multi-textured-terrain/) - You want to render your terrain given a low-res terrain-map-texture?  This example uses a low-res terrain-map-texture (where the information which tile to draw is encoded in the colors) to render a terrain. Advanced and only usable under certain circumstances, but worth the time.
* [**Deferred Engine Playground**](https://github.com/UncleThomy/DeferredEngine) - Deferred rendering engine written to make developing and understanding custom shaders easier.
* [**ShaderFrog**](http://shaderfrog.com/) - A online web-based shader editor providing WYSIWYG. Nice project.
* [**WPF Shader Effects Library**](http://wpffx.codeplex.com/) - This one contains many cool effect files easy to adopt for your game. It's under the Ms-PL license which should be ok as long as you don't publish the source-code. There is a [video](https://channel9.msdn.com/shows/Continuum/WPFFXDemo/) demonstrating the effects along with a narration.

### Audio
* [**XACT audio tutorials**](http://rbwhitaker.wikidot.com/audio-tutorials) - You want to make noise, but you don't know how?  This is a very elaborate collection of very useful tutorials starting from "Audio in XNA" and ending with "3D Audio Effects". Very straight forward and many screenshots.  
* [**Attenuation / Doppler pitch shifting in XACT**](http://msdn.microsoft.com/en-us/library/dd231913.aspx) - You want your close sprites to be louder than the ones far away?  Very elaborate Microsoft tutorial on creating attenuation and doppler-pitch-shifting using XACT. Nice, step by step and many screenshots.  

### Procedural Generation
* [**Procedural Dungeon Generation**](http://www.varav.in/posts/2016/05/25/dungeon.html) - An interactive article about automatic dungeon generation. Good stuff.
* [**Algorithms for making more interesting mazes**](http://www.gamasutra.com/blogs/HermanTulleken/20161005/282629/Algorithms_for_making_more_interesting_mazes.php) - An article that explains various ways to generate interesting mazes. Nice pictures, nice explanations, no code.

# Practice

## Components
This stuff here is either directly ripped from our game or from other libraries. For you to take and use as you like.  

* [**Object Pool**](https://gist.github.com/guFalcon/39a24c1c0bba644a2ba3e03f53601632) - This is a lock-free object pool. One of the integral parts of a game-engines.
* [**Collision Grid**](https://github.com/UnterrainerInformatik/collisiongrid) - Used in the broad-phase of collision detection. Faster than a Quad-Tree. Description is inside.
* [**SplitStopWatch**](https://github.com/UnterrainerInformatik/splitstopwatch) - Want to debug timings and you like a pretty console-output using split-times, etc? Take this.
* [**ThreadPool**](https://github.com/UnterrainerInformatik/threadpool) - Want to do async work but the methods you like to call all have different signatures? This is a very fast implementation of a fill-and-start thread pool.
* [**Per Pixel Collision**](https://github.com/UnterrainerInformatik/perPixelCollision) - Want to know how to do matrix-transformations? Want to know if two textures collide with pixel-precision? Take this, but read the readme.md first. It explains why using this technique in a production environment is a bad idea.
* [**XNA Examples - MonoGame Port**](https://github.com/DDReaper/XNAGameStudio) - An almost complete MonoGame port of the good old XNA examples from MS.

## Libraries
Here you find game-engines, extensions, etc.

### Game Engines
* [**MonoGame**](http://www.monogame.net/) - XNA continued!  By leveraging C# and other .NET languages on Microsoft and Mono platforms you can write modern, fast, and reliable game code.
* [**MonoGame.Extended**](https://github.com/craftworkgames/MonoGame.Extended) - An awesome extension library for MonoGame dealing with additional stuff that was out-of-scope for MonoGame.
* [**Nez**](https://github.com/prime31/Nez) - Another great extension library. Very comprehensive.

### UI
* [**EmptyKeys**](http://emptykeys.com/) - A very cool multi-platform UI library based on XAML.
* [**Nuclex**](https://nuclexframework.codeplex.com/) - An older framework written for XNA.
* [**Nez**](https://github.com/prime31/Nez) - This extension library also contains a port of LibGDX Scene 2D UI.
* [**Squid**](https://github.com/Roderik11/Squid) - SQUID is an SDK to create user interfaces for games and other 2D/3D realtime applications, using a Retained Mode system. SQUID does not depend on a certain rendering engine, you can use it with any engine you like, on any platform that supports the .NET 2.0 framework. Squid is free and maintained by [IONSTAR Studios](http://www.ionstar.org/?page_id=4).
* [**MonoGame Gui4U**](https://gui4u.codeplex.com/) - Simple. A port from XNA Simple GUI
* [**Neoforce-Mono**](https://github.com/NeoforceControls/Neoforce-Mono) - A MonoGame port of the NeoForce controls. Pretty comprehensive.

### Shadows
* [**Penumbra**](https://github.com/discosultan/penumbra) - 2D lighting with soft shadows for MonoGame.

### Map Editors
* [**Tiled**](http://www.mapeditor.org/) - An awesome editor for all kinds of maps. Freeware and if you search for a MonoGame loader for the maps generated by this beauty, then look for MonoGame.Extended.

### Networking
* [**Lidgren**](https://github.com/lidgren/lidgren-network-gen3) - One of the major players when it comes to connecting your game-clients. Definitely worth a look.
* [**RakNet**](https://github.com/OculusVR/RakNet) - One of the major players as well.

### Connectors
* [**Steamworks.NET**](https://github.com/rlabrecque/Steamworks.NET) - A .NET wrapper for the SteamWorks API.

## Tools
Build tools, deployment tools, etc.

* [**ProtoBuild**](https://protobuild.org/) - If you wanna do cross-platform development this tool will help you to keep your project-files in order.
* [**wyBuild**](http://wyday.com/wybuild/features.php) - You want to have an updating game (maybe self-updating)?  A tool to create and deliver AND install updates manually or automatically in any given .NET language. This one saved and saves our butts during the alpha-testing stage.  
* [**Convert to Icon**](http://converticon.com/) - You want your own mouse-cursor?  When programming a game in XNA you come to a point when you want your own mouse-cursor. This program helps you to convert your image-files to an icon-file. And it's completely online.  
* [**DXT Compression**](http://code.google.com/p/libsquish/) - You want to compress the textures of your game on your own?  Normally you'd use the content-loader-pipeline of XNA (don't fear; the content-loader-pipeline does almost everything automatically), but if you can't use it, then you'll be stuck with this when you're trying to get compressed textures to your graphics-card.  
* [**Using Platform Specific Libraries from a Platform Agnostic Project**](http://code-jedi.com/blog/post/Using-Platform-Specific-Libraries-from-a-Platform-Agnostic-Project) - We've all had this problem. You want to use a library, but that comes in x86 or x64 flavor and your game should use the 'AnyCPU' target. This article describes how you can switch between the libraries on demand after editing the project file directly. Works like a charm, although it just determines the currently used context and replaces the files accordingly. So you cannot really build an 'AnyCPU' project using this method because the build-result will be fixed to the context used on your computer at compile-time.

## Legal Stuff, Licenses
One important thing: When searching for legal advice concerning licenses you'll be pretty much out of luck. Most of the time people tell you that they won't give 'legal advice' since the legal ramifications resulting from such an advice are just too awful.
So I won't do that either. You'll have to read for yourself and don't just take my word for it.
So, for what it's worth, here are some useful links and the comments are just my humble opinion.

* [**Comparison of free and open-source software licenses**](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses) - A very nice wiki-article with a nice table. For a quick lookup.
* [**Top 10 Copyright Myths**](http://www.copyrightservice.co.uk/copyright/copyright_myths) - A text from the UK Copyright Service. Thx to MrValentine from the MonoGame boards for finding it.

### Copyright
If you'd like to make money with your game, these licenses here are your friends. They allow you to use the code / asset / whatever, retain the original license, maybe do some sort of attribution of the original author, but don't prohibit you selling your work for money.

* [**Copyright**](https://en.wikipedia.org/wiki/Copyright) - Explanation of copyright and waht it's used for.
* [**Unlicense**](http://unlicense.org/) - Free for everything, including commercial use.
* [**MIT License**](https://en.wikipedia.org/wiki/MIT_License) - Also completely free. But don't remove the license.
* [**GNU LGPL**](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License) - A little less permissive as the MIT license, but is not copyleft as its big brother the GPL.
* [**Apache License**](https://en.wikipedia.org/wiki/Apache_License) - Free for commercial use as far as I know.
* [**BSD Licenses**](https://en.wikipedia.org/wiki/BSD_licenses) - Free for commercial use as well.
* [*CC-BY*](https://en.wikipedia.org/wiki/CC-BY) - Free. But don't forget to attribute properly.
* [**Do What The Fuck You Want To Public License (WTFPL)**](https://en.wikipedia.org/wiki/WTFPL) - I had to put it in here because of... well... you know... it's obvious, isn't it?

### Copyleft
Essentially and if there is no change in the text of the license in the work you're trying to use, the following licenses are viral.
If you use code under such a license, you'll have to adapt your license to theirs.
Not great if you'd like to make some money with your game later on.

* [**Copyleft**](https://en.wikipedia.org/wiki/Copyleft) - Explanation of copyleft and what it's used for.
* [**GNU GPL**](https://en.wikipedia.org/wiki/GNU_General_Public_License) - Beware: Copyleft.
* [**CC-BY-SA**](https://en.wikipedia.org/wiki/CC-BY-SA) - Like CC-BY, but copyleft.

## Artistic Material
All the sites I link to in this paragraph contain "free for commercial use" material, although they may contain non-free material as well. It's your responsibility to check before you use it.  
You won't be able to dodge the fight with the even or odd license-text when dealing with creative content, so you might as well get over it and try to get a grasp on things.  
### Mixed
* [**Open Game Art**](http://opengameart.org/) - A site containing a rather limited collection of open art, but still, worth a look.
* [**Gamedeveloper Studio**](http://www.gamedeveloperstudio.com/) - Looking for game assets?  Are you looking for professional quality assets for your games? Would you like to cut your development time in half? This site contains some royalty free content.

Would you prefer not to invest hundreds or thousands of dollars into your title?

### Graphics
You want a sky-, grass- or other texture? These sites contain, besides other stuff, free-for-commercial-use textures.  

* [http://www.noctua-graphics.de/deutsch/fraset_d.htm](http://www.noctua-graphics.de/deutsch/fraset_d.htm)  
* [http://telias.free.fr/](http://telias.free.fr/)  
* [http://www.cgtextures.com/](http://www.cgtextures.com/)  
* [https://remos.itch.io/isometric-tree-sprites](https://remos.itch.io/isometric-tree-sprites)

### Fonts
You want to write something on the screen without getting sued?  These sites contain, besides other stuff, many free-for-commercial-use fonts (you'll have to read the licenses though).  

* [http://www.fontsquirrel.com](http://www.fontsquirrel.com)
* [http://www.1001fonts.com](http://www.1001fonts.com)

### Sounds
You've got no sound yet?These sites contain, besides other stuff, free-for-commercial-use samples.  

* [http://www.mediacollege.com/downloads/sound-effects/](http://www.mediacollege.com/downloads/sound-effects/)
* [http://www.partnersinrhyme.com/pirsounds/WEB_DESIGN_SOUNDS_WAV/BUTTONS.shtml](http://www.partnersinrhyme.com/pirsounds/WEB_DESIGN_SOUNDS_WAV/BUTTONS.shtml)
* [**SoundImage**](http://soundimage.org/) - Very large and cool library of original music-pieces and sounds all licensed under a public license that only reqires proper attribution as stated on the About-page 'Section 3 – License Conditions.'. It is neatly explained again on the home-page of this site. Thanks Eric Matyas. Great work. Please consider donating a small amount of money for all the hard work.
