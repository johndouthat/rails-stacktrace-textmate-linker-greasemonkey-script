A greasemonkey script / Chrome extension that will make your stack trace lines open in TextMate
-----------------------------------------------------------------------------------------------

I wrote this because I wanted a quicker way of getting from a rails error page in development to the line of code where it broke in TextMate

It works in both Firefox and Chrome, but if you want it to work in firefox you need to have [greasemonkey](http://addons.mozilla.org/en-US/firefox/addon/748) installed first.

To install it, just [click here](http://github.com/johndouthat/rails-stacktrace-textmate-linker-greasemonkey-script/raw/master/rails-stacktrace-linker.user.js)

Note
----

When I was scratching my itch I found [Rails Footnotes](http://github.com/josevalim/rails-footnotes) which does the same thing but as a rails plugin but 
I did not like that route because I didn't want to add any more dependencies or bloat to my already big rails app, and I figure it would be just a burden
to all my coworkers that don't use textmate. Rails Footnotes does some other cool stuff but I actually didn't want that either, I use Rack::Bug for that.
I guess another side effect is that it will work for any rails app I am working on, not just the ones I have installed the plugin in.


If you want to get it work on things other than textmate
--------------------------------------------------------

take a look at some of these:

http://www.gauda.de/ruby-on-rails/use-rails-footnotes-to-open-files-in-netbeans-from-firefox/

http://josevalim.blogspot.com/2008/06/textmate-protocol-behavior-on-any.html

http://ruy.ca/2007/04/01/handling-txmt-urls-in-windows

http://www.jetbrains.net/devnet/message/5239980