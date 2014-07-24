# Curated list of Espresso Sugars to improve your workflow
[Espresso](http://macrabbit.com/espresso/ "Espresso, the web code editor") is a very good code editor out of the box, but there's a lot more it can do once you **install the proper Sugars**.

For those of you who don't know it, Sugars are plugins or addons, for adding extra functionality to Espresso.

I promise after checking out some of these you will **write better code** a lot faster. And I mean a woeful lot faster.

## The must-haves
- ShellActions: **IMPORTANT: you need this to run other plugins in this list, please install it** This provides internal capabilities to other sugars to run shell scripts. Unless you are a Sugar developer you don't need to worry about this, but you **need it** to run other Sugars in this list.
- [Autopair](https://github.com/onecrayon/Autopair-sugar "Autopair Sugar for Espresso"): This will change your coding life. It will automatically close braces and quotes for you and you will be able to exit the braces/quotes with a simple tab. So, every time you type `{`, Espresso will automatically add the closing `}` for you and you will be able to exit the `{}` by simply hitting the tab key. Moreover, if you try to delete the opening brace or quote, it will automatically delete the closing one, too. And guess what's more? If you select some text and type one of the triggers (braces or quotes) it wraps everything up! It doesn't get any sweeter than that.
- [Handy](https://github.com/onecrayon/Handy.sugar "Handy: a collection of text actions for Espresso, che code editor"): Handy is a collection of text actions to simplify your editing workflow. It includes: select all copies of text/word, edit multiple selections at once, auto-indent closing braces, increment/decrement numbers, and a lot more.
- [HTMLBundle](https://github.com/onecrayon/HTMLBundle.sugar "A huge time-saver for html editing for Espresso the web editor"): This is another huge time-saver. The HTMLBundle sugar will add a woeful lot of html snippets with tab navigation through default attributes. You will have a form up and running in no time. (Please, do follow the link given on GitHub for [more info](http://onecrayon.com/products/htmlbundle/ "More info on the HTMLBundle Sugar for Espresso"), don't know why Ian, the developer, hasn't put everything on GitHub like he usually does.)

## Languages
- [jQuery Sugar](https://github.com/derekr/jquery.sugar "jQuery autocompletion for Espresso"): Adds autocompletion for jQuery.
- [WordPress Sugar](https://github.com/funkylarma/WordPress.sugar "WordPress functions autocompletion for Espresso"): Adds autocompletion for many WordPress-specific functions. Incredibly useful if you will ever work with WordPress. **Alternative repo:** I have just found [this other one](https://github.com/olach/WordPress.sugar "WordPress sugar for Espresso"), but I haven't tested it out. It looks like it pulls data from wpseek.com so I guess it should be always up-to-date with everything new in WordPress. It seems like it also provides parameter hinting. I will definitely try this in my next project.
- [Kit Sugar](https://github.com/GioSensation/kit.sugar "Syntax highlighting for CodeKit's .kit files in Espresso"): Adds basic support (highlighting and html support) for [CodeKit](http://incident57.com/codekit/index.html "CodeKit: the webdev holy grail uncovered")'s .kit files in Espresso. **Disclaimer**: I am the developer behind this sugar. It is still pretty basic, but it works. Feel free to contribute.
- [Sass Sugar](https://github.com/sfcgeorge/Sass.sugar "Sass sugar for Espresso"): Adds basic support for the scss preprocessor syntax. This is very limited and not maintained. If you know of anything better, please do let me know. **Alternative repo:** I just found this other [sugar for Sass (scss)](https://github.com/d3head/SCSS.sugar "Sass scss syntax for Espresso"). I haven't tested it, but it is a lot more recent than the other one and this makes me hopeful.
- [Sql](https://github.com/fileability/sql.sugar "Sql syntax highlighting for Espresso"): Syntax highlighting for .sql files. (Check out the haiku in the repo's readme!)
- [Slim](https://github.com/slim-template/Slim-Sugar "Syntax highlighting for Slim files in Espresso"): Syntax highlighting for Slim files.
- [Haml](https://github.com/lianghai/Haml.sugar "Syntax highlighting for Haml files in Espresso."): Syntax highlighting for Haml files.

## The useful utils
- [GetInfo](https://github.com/onecrayon/Get-Info.sugar "GetInfo Sugar for Espresso"): Nice little add-on that lets you inspect the Info panel of the Finder right from Espresso, so that you can have more information on the file itself such as file size, creation date, etc.
- [Dash](https://github.com/Kapeli/Dash-Espresso-Plugin#readme "Espresso Sugar for Dash.app"): If you use [Dash.app](http://kapeli.com/dash "Dash.app – Offline code docs at your fingertips") for checking code documentation (and you should, really), you will find this pretty useful to inspect syntax from right within Espresso with a simple shortcut.
- [Validatorian](https://github.com/onecrayon/Validatorian.sugar "Adds css validation capabilities to Espresso"): This adds local css validation by W3C to Espresso. I admit I have it installed, but I have never used it.
- [Barista Beautifier](https://github.com/jancbeck/Barista-Beautifier.sugar "HTML, js and css beautifier for Espresso"): This sugar beautifies previously minified html, css or javascript. Very handy.
- [Kaleidoscope diff](https://github.com/onecrayon/Kaleidoscope.sugar "Adds a quick way to diff files in Espresso"): This provides a quick and easy way to diff files in [Kaleidoscope](http://www.kaleidoscopeapp.com "Kalidoscope, powerful file diffing for the Mac") right from within Espresso. You can diff two files or diff a file with the clipboard. Super handy when comparing local files with remote versions.
- [LineDance](https://github.com/onecrayon/LineDance.sugar "Handy line management shortcuts for Espresso"): Offers quick commands to manipulate lines: delete lines, duplicate lines and duplicate upward.
- [ConvertLineBreaks](https://github.com/onecrayon/ConvertLinebreaks.sugar "Convert Line Break styles in Espresso"): Converts all line breaks in the file to either Unix, Windows or Mac-Classic style.

If you need balancer delimiter highlight, you might want to try [Seesaw](https://github.com/onecrayon/Seesaw.sugar "Balancer delimiter highlighting for Espresso"), but unfortunately I find it almost of no use since it needs to be triggered by the user and this is quite annoying. I know this is a limitation forced by the way Sugars actually works, but still its use is quite limited this way.

## Why aren't these functionalities included by default?
And this brings me to my final point. Many of the Sugars listed above – notably the most useful ones – are developed by the great [Ian Beck](https://github.com/onecrayon "Ian Beck, Espresso sugar developer") (@onecrayon here on GitHub), who is part of the MacRabbit team. I wonder why in the world they don't integrate those right inside Espresso.

I am sure that most developers are turned off by the lack of functionality such as multiple selection editing, autopairing, powerful html snippets and more. Especially given that this page is the most up-to-date gallery of Espresso Sugars and many don't even know that Espresso can perform such things. I am sure MacRabbit would conquer back a lot of popularity (and market share) if they integrated these into Espresso right of the box.

They will surely have their reasons for this and I hope it's not that they are holding back for a version 3.0 release, or it better come quite soon.

## Contribute to the list!
This is by no means a comprehensive list of all available sugars. A quick search here on GitHub will find you many more. This is just the ones that I use most often and that I think greatly improve my experience with Espresso.

If you feel like I am missing something, issue a pull request or simply reach out to me on [Gravida's website](http://gravida.pro/emanuele-feliziani-web-developer "Emanuele Feliziani, Web Developer at Gravida.pro in Macerata").

I am sure with these sugars installed you will find Espresso an even better tool for your trade. These bring Espresso right there with the top players in the market.

Enjoy!

PS I will soon be publishing an article about why I still prefer Espresso over other text editors and what are its most impressive features. I will update this page once it's out. If you are interested, stay tuned by select "Watching" from the drop-down menu above. Cheers!
