# Scriptular

A regular expression editor for javascript.

## Backstory

Before the summer of 2011 I never took the time to dig into regular expressions and actually learn how they work. Then [Hubot](http://hubot.github.com) came along and suddenly regular expressions were cool.

Immediately I began writing hubot scripts and started using [Rubular](http://rubular.com) to test my regular expressions. Unforunately there are some differences between Ruby's regular expressions and the myriad of implementations in javascript (and specifically the V8 implementation that hubot uses), so I needed a new Rubular, one for javascripts.

So I created [Scriptular](http://scriptular.com) and started regular expressing myself ;) This is a beta, probably has a ton of bugs, but you have to start somewhere. Also, since it uses your browsers javascript interpreter there will be differences between your results here and other browsers and even V8, so this is not necessarily the perfect editor for regular expressions in hubot.

Having said that, I hope someday to have a V8 option to run against so you can write perfect regular expressions for hubot everytime.

## Compiling Coffeescript in Development

* clone the repo
* npm install -g coffee-script
* cake build

## CONTRIBUTE

If you'd like to hack on Scriptular, start by forking the repo on GitHub:

https://github.com/jonmagic/scriptular

The best way to get your changes merged back into core is as follows:

1. Clone down your fork
1. Create a thoughtfully named topic branch to contain your change
1. Hack away
1. If you are adding new functionality, document it in the README
1. If necessary, rebase your commits into logical chunks, without errors
1. Push the branch up to GitHub
1. Send a pull request for your branch

## License

Copyright (c) 2011 Jonathan Hoyt

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.