# What is this?

A documentation experiment. After many discussions on which
documentation tool to use (yuidoc, jsdoc, jsduck, docco, etc..)
I felt like it was time to experiment myself.

### Great so what will this do...?

Documentation generation typically means generating a static website
that is served somewhere. I think its a flawed assumption that we should
generate some static copy to describe our code that is _not_ actually
the code. Our code should live as a documented guide on _how_ to use the
code. Can we simply enhance how we view the code to create amazing
documentation? [see docco's take on this]

The documentation viewer itself will be implemented using web standards
and the [esprima](http://esprima.org/doc/) JavaScript parser. We will
read files from disk and display formatted version of your code.
By using Markdown and code highlighting we can present a formatted
version of the code [similar to docco] with enhanced markdown document
blocks. Additionally we can leverage the JS parser information to
present enhanced view of all function arguments and object properties.

### Awesome where is the code!

Nothing yet- just ideas and a goal of having really nice documentation
that is really trivial to deploy/develop.

### Won't this (if there was code) be really f'n slow?

Maybe at first. I think with sane e-tag handling (http cache) and
caching the parsed results we will end up with something very fast.

## License

The MIT License (MIT)

Copyright (c) 2013 Sahaja James Lal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
