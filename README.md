# dokku-node

dokku-node is a plugin for [dokku][dokku] that injects node with the listed packages within your dokku environment.
This is mostly useful for instances where you have a say a python buildpack but you want to have less or coffeescript
available to compile files.

## Installation

```sh
git clone https://github.com/pnegahdar/dokku-node.git /var/lib/dokku/plugins/dokku-node
dokku plugins-install
```

All future deployments will use have node with the packages in the `pacakges` file installed by npm.

## License

The MIT License (MIT)

Copyright (c) 2013 Parham Negahdar

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
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[dokku]: https://github.com/progrium/dokku
