# Freezepop

This tiny tool will automagically:

1. Freeze Flask repositories using [Frozen-Flask](http://packages.python.org/Frozen-Flask/)
2. Minify HTML / JS / CSS using [htmlcompressor](https://code.google.com/p/htmlcompressor/)
3. Sync the frozen Flask site to AWS S3.

## Overview

0. Copy (symlink + gitignore?) `freezepop.py` and `.bin/` to your repository.
1. Add your site config to site-config
2. Add .awskey to .gitignore
3. Create an .awskey file containing your private aws key (make sure it is not committed!)

## Directories

## Authors
**Nick Semenkovich**

+ https://github.com/semenko/
+ http://web.mit.edu/semenko/

## License
Copyright 2013, Nick Semenkovich <semenko@alum.mit.edu>

Released under the MIT License. See LICENSE for details.


(External dependencies available under their respective licenses.)