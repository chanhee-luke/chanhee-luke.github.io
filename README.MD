
## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

### Run server

``` bash
$ npm install
$ hexo g
$ hexo s
```

### Deploy to remote sites

``` bash
$ hexo clean && hexo d -g
```

Remember to switch to gh-pages and commit favicons.

### Change these:

```
themes/cactus/layout/archive.ejs
themes/cactus/layout/index.ejs
source/_data
```

#### When upload files
rm -rf .deploy_git/