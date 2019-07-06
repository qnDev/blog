---
layout: post
title: "Markdown syntax"
comments: true
---

# HEADERS
```
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag
```
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag

# LISTS
## Unordered
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b

## Ordered
```
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b
```
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

# IMAGES
```
![Screenshot home page](/images/screenshot-homepage.png)
Format: ![Alt Text](url)
```

![Screenshot home page](https://raw.githubusercontent.com/qndev/jekyll-theme/master/images/screenshot-homepage.png)

# EMPHASIS
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

# LINKS
```
http://github.com - automatic!
[GitHub](http://github.com)
```
http://github.com - automatic!
[GitHub](http://github.com)

# Blockquotes
```
As Grace Hopper said:

> I’ve always been more interested
> in the future than in the past.
```
As Grace Hopper said:

> I’ve always been more interested
> in the future than in the past.

# Syntax highlighting
```javascript
function test() {
console.log("look ma’, no spaces");
}
```

# Task Lists
```
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
```
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)

# EMOJI
```
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
```
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
