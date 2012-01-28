<pre style="font-size: 10px;">
ESP (EcmaScript Pages) edit mode for Sublime Text 2 (and probably TextMate)

v1.2, (c) 2012-01-24, __tb
Development platform: Sublime Text 2 Beta, Build: 2165

Provides advaced background highlighting for server-side and client-side scripts.
Kuler was used to extend the Monokai color set (http://kuler.adobe.com/#create/fromacolor)
This edit mode is based on the built-in ST2 HTML package.
    
Installation:
    Either:
    (0. if you do not have Package Control installed follow these instructions:
        http://wbond.net/sublime_packages/package_control/installation)
    1. ⌘⇧P (or ^⇧P) to open Command Palette
    2. select Package Control: Install Package
    3. select ESP
    
    Or:
    1. cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
       # or corresponding folder on your operating system
    2. git clone https://github.com/balazstth/subl-esp.git "ESP"
    3. Sublime Text 2 -> Preferences -> Color Scheme -> ESP -> Monokai ESP
    4. if not set automatically: after opening an ESP file
       View -> Syntax -> Open all with current extension as... -> ESP

TODO:
    Toggle Comment for EcmaScript still uses #
    Highlighting for embedded server-side script in client-side JavaScript strings.

Known issues:
    Might interfere with built-in HTML embedded language support, not drastically though.

Contact information: balazstth at github and gmail

</pre>
![Screenshot](https://github.com/balazstth/subl-esp/raw/master/subl-shot.png "Screenshot")
