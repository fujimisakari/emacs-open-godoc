# open-godoc.el


## Introduction

open-godoc is to open godoc.org site from emacs.


## Screenshot

![open-godoc](image/open-godoc.gif)


## Installation

You can install `open-godoc.el` from el-get.

Add following to your el-get-sources setting and execute `M-x el-get-install open-godoc`

```lisp
(setq el-get-sources
      '(
        (:name open-godoc
               :type github
               :description "open godoc"
               :url "https://github.com/fujimisakari/open-godoc")
        ))
```

You also install by not using el-get.  git clone this repository to your emacs lisp directory.

```
$ git clone git://github.com/fujimisakari/open-godoc.git path/to/dir
```

## Usage

#### `open-godoc`

Search from godoc.org site with search query
