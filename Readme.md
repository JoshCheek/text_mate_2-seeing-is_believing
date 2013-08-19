Seeing Is Believing
===================

Integration of `seeing_is_believing` and TextMate2 as a Bundle.

Prerequisites
-------------

You need to have your `$TM_RUBY` env var set to point at the Ruby you're using.
If you're using **rvm**, [here](http://rvm.io/integration/textmate) are instructions for how to set up TextMate to work with it
(I recommend the wrapper approach). If you're using **rbenv**, [here](http://uberfork.com/post/12280974742/integrate-rbenv-with-textmate)
are instructions for how to set up TextMate to work with it.

You need to have [seeing_is_believing](http://rubygems.org/gems/seeing_is_believing) installed
for the ruby you're using (and if you're using gemsets, make sure you installed it to the gemset your `$TM_RUBY` is using).

    gem install seeing_is_believing

Installation
------------

This uses git to get the code, but really any way you get the code into this dir is fine,
you could download and unzip it, for example.

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/Avian/Bundles/
    git clone git://github.com:JoshCheek/text_mate_2-seeing-is_believing.git Seeing\ Is\ Believing.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

Use
===

There are three commands you can use

* Command + Option + N - Annotate Marked Lines
* Command + Option + B - Annotate all lines
* Command + Option + V - Remove annotations

There are also some snippets you can use to play around with SiB in a more interesting environment.

* `s_arb` tab        - In memory ActiveRecord environment
* `s_nokogiri` tab   - Experiment with Nokogiri
* `s_sinatra` tab    - Experiment with Sinatra
* `s_reflection` tab - Common examples of reflection

Thanks
======

To Infiniknight on [irc](irc://irc.freenode.net/textmate) for customizing the menu layout and giving me feedback on the integration.

License
=======

           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                       Version 2, December 2004

    Copyright (C) 2012 Josh Cheek <josh.cheek@gmail.com>

    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

     0. You just DO WHAT THE FUCK YOU WANT TO.


