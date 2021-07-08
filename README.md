# My Jekyll Portfolio Website

Welcome to the repository for my latest portfolio website! 

## Contents

- [Setup](#setup)
- [Context](#Context)
- [The Theme](#Theme)

## Context

This website was built using Jekyll (a static site generator). Before this project, I took on the initial challenge of trying to construct my website with vanilla HTML, CSS and Javascript. It was only until I moved on from the landing that I began to realise that I would need to copy-and-paste a lot of similar code across pages (such as headers and footers). The major issue I found with this is that if I ever want to change a web component such as the header or footer, I would need to make changes to every webpage that used that web component.

Here is a link to the [repository](https://github.com/adriantan09/website) of the discontinued [website](https://adriantan09.github.io/website/)

It was at this point that I went back to the drawing board to see what other people on the internet had done. After researching, I found that static site generators would help to solve the issue I was experiencing. The setup and structure of these projects is also straightforward and simple, especially if you use a theme.

## Theme

For those curious, the [Jekyll](https://jekyllrb.com) theme I am using is called Pineapple.

See [Pineapple](https://github.com/arnolds/pineapple) in action on the [demo site](https://arnolds.io/pineapple/).

## Setup

Install dependencies:

```
$ gem install jekyll bundler
```

Pulldown the project:

```
$ git clone https://github.com/adriantan09/jekyll-website.git
$ cd jekyll-website
```

Start Jekyll:

```
$ jekyll serve
```

Browse to http://127.0.0.1:4000/jekyll-website/ for some goodness.
