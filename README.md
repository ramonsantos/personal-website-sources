# Personal Website Sources

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Setup

### Install Hexo
``` bash
sudo npm install hexo-cli -g
```

### Clone the repository
``` bash
git clone git@github.com:ramonsantos/personal-website-sources.git ramonsantos.github.io && cd ramonsantos.github.io
```

### Install dependencies
``` bash
npm install
```

``` bash
npm dedupe
```

### Install Theme

#### Clone the repository
``` bash
git clone git@github.com:ramonsantos/shine-on-you-crazy-diamond-theme.git themes/shine-on-you-crazy-diamond-theme && cd themes/shine-on-you-crazy-diamond-theme
```

#### Install dependencies
``` bash
npm install
```

#### Build
``` bash
gulp
```

## Generate Website
``` bash
hexo generate
```

## Run locally
``` bash
hexo server
```

## Deploy
``` bash
hexo deploy
```
