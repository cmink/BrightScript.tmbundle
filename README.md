BrightScript Language Definition Bundle
=======================================

Get BrightScript syntax highlighting in [TextMate](http://macromates.com/) or [Sublime Text](http://www.sublimetext.com/) with this Language Definition bundle.

Installation for TextMate
-------------------------

Clone this bundle into your TextMate/Bundles directory:

    [ ! -f ~/Library/Application\ Support/TextMate/Bundles ] && mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/cmink/BrightScript.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

Installation for Sublime Text 2
-------------------------------

Sublime Text users can do similarly by cloning the repository into the Packages directory:

    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    git clone git://github.com/cmink/BrightScript.tmbundle.git

Then start Sublime Text.

Installation for Atom
---------------------------

Atom users can convert the bundle using the following syntax:

    apm init --package ~/.atom/packages/language-brightscript --convert https://github.com/cmink/BrightScript.tmbundle

BrightScript Friendly Customized Mustang Theme
----------------------------------------------

I've moved the theme out of this repository and into a separate repository where it belongs. It is the TextMate adapted Mustang theme with some custom colors for the BrightScript language. Get it here [Mustang.tmbundle](http://github.com/cmink/Mustang.tmbundle).

This bundle was orginally adapted from ASP.tmbundle [https://github.com/textmate/asp.tmbundle.git](https://github.com/textmate/asp.tmbundle.git).
