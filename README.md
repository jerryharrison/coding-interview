# JS assessment Interview Questions

This repo includes a set of tests that can be used to assess the skills of
a candidate for a JavaScript position, or to evaluate and improve one's own
skills.

## I want to work on the tests; what do I do?
To use the tests, you will need to install [Node](https://nodejs.org/). Note
that on Windows, there are some reports that you will need to restart
after installing Node - see #12.

You can clone or download this repo. Once you have done so, from the root
directory of the repo, run:

    npm install
    npm start

You can then view the tests in your browser at
[http://localhost:4444](http://localhost:4444).

When you visit that page, all of the tests should be failing; your job is to
get the tests to pass. To do this, you'll need to refer to the tests in the
files in the `tests/app` directory, and edit the files in the `app/` directory.
Once you update a test, you can reload the test page in the browser to see
whether it worked.

You can also run (most of) the tests on the command line:

    npm test

The command line runner is a work in progress; contributions welcome :)

### Available dependencies

The repo includes jQuery, Backbone, and Underscore. You can use these
libraries when writing your solutions!

## I want to see the answers!

First, bear in mind that looking up the answers is going to teach you a whole
lot less than you'll learn by working on the tests, even if you occasionally get
stuck.

## I hate \<some technology you've chosen\>

Feel free to `npm install` or `yarn install` other packages and use them as you 
see fit. This lets me know your ability to extend and use a variety of packages 
not just the ones handed to you.

# License

Copyright &copy; 2017 Jerry Harrison

With love to (Copyright &copy; 2012-2016) Rebecca Murphey with many thanks to several

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
