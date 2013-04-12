Eclipse Dark CSS
================

This project contains some CSS files that you can use to customize your Eclipse IDE in dark colors.

* black.css: Black background
* dark_gray.css: Dark gray (#333) backgound

![Screenshot](https://github.com/albertoruibal/eclipse_dark_css/raw/master/screenshot.png)

This is not a perfect solution, as the scrollbars and other IDE elements aren't themed, but I use it to work everyday in a less eye-stressing environment.

Steps to customize eclipse
* Install "E4 CSS Editor (Incubation)" from the Eclipse Platform Incubator (Update site: http://download.eclipse.org/e4/updates/0.12)
* Go to Preferences->General->Appearance and now you can paste the contents of the CSS file (black.css or dark_gray.css) in the new CSS text box (I modified the "Default Theme")
* Install "Eclipse Color Theme" (Update site: http://eclipse-color-theme.github.com/update) 
* Go to Preferences->General->Appearance->Color Theme and choose a black theme (I use the "RecognEyes" theme)

Finally (and this needs a lot of time), you need to change manually some colors (backgrounds to #333 if dark gray or #000 if black and foregrounds to light colors)
* Preferences->General->Appearance->Colors and Fonts (You can filter using the "background" keyword)
* Preferences->General->Editors->Text Editors
* Preferences->Run/Debug->Console

CSS SPY
=======

From the Eclipse incubation site you can also install the "E4 CSS Spy (Incubation)", once installed, if you press SHIFT+ALT+F4 the CSS Spy window will be opened.

With this CSS Spy Tool you can browse through the styles of the SWT interface and try to change the CSS.

References
==========

This CSSs were initially from the "Eclipse Darker Theme" https://github.com/jinmingjian/eclipse.themes.darker and I made some modifications.

Problems
========

The E4 CSS Editor saves the CSS files in the $HOME/.e4css directory.

At some point my E$ CSS Editor stopped saving the CSS changes, and I had to delete the $HOME/.e4css directory, then it started working again.