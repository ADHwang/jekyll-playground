# jekyll-playground
Jekyll playground

## Installation

安装 Jekyll 需要以下软件：

- Ruby (check `ruby -v`)
- RubyGems (check `gem -v`)
- GCC and Make (check `gcc -v`, `g++ -v` and `make -v`)

### Installing Ruby

#### Windows

Using [RubyInstaller](https://rubyinstaller.org/).

RubyGems 会随同 Ruby 一起被安装。

### Installing Make

#### Windows

Downloading [Make for Windows](http://gnuwin32.sourceforge.net/packages/make.htm). 有两种下载方式：1. 下载 Setup program of the package；2. 下载 zip 包，包括 Binaries 和 Dependencies 两个包。我选择第 2 种方式。下载完成后，直接解压，把两个包放到自己喜欢的目录下；比如我就把它们放到了 `D:\GnuWin\` 下面。

### Installing Jekyll

#### Windows

命令 `gem install jekyll bundler`。

## Quick Start

```
# Create a new Jekyll site at ./myblog
jekyll new myblog

# Change into your new directory
cd myblog

# Build the site on the preview server
bundle exec jekyll serve

# Now browse to http://localhost:4000
```
