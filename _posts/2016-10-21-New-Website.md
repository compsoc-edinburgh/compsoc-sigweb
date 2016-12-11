---
    author: tbrb
---
Bought to you by SIG:Web, We've launched the new comp-soc.com!

It's all open source, and ultra-easy to get involved with. All you need is a text editor and a GitHub account! All the source for the new website is available in the [compsoc-edinburgh/website2016](https://github.com/compsoc-edinburgh/website-2016) repository.

You should first fork the repository so you can work on your copy locally, before submitting content to us.

If you want to write a post, all you need to do is to create a file in the `_posts` directory. The new post filename should follow the Jekyll post naming scheme which is detailled [here](https://jekyllrb.com/docs/posts/).

You can see the "code" that's gone into making this post right [here](https://github.com/compsoc-edinburgh/website2016/blob/master/_posts/2016-10-21-New-Website.md). As you can see, it's all [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), which is really easy to write.

If this is your first post, you should also create an author profile too! This is what puts your own information to the left of the post like you can see on this one. Author profiles live in `_data/authors.yml`.

Inside `_data/authors.yml` you'll see a bunch of entries like these:

```yaml
tbrb:
  name: "Harry Reeder"
  uri: "http://harryreeder.co.uk/"
  email: "harry@harryreeder.co.uk"
  bio: "I build stuff"
  avatar: "http://www.gravatar.com/avatar/882fea3f994a649328155e5ab2316b7f?s=200"
  twitter: "harry_reeder"
  github: "hreeder"
```

The initial `tbrb` at the beginning is what identifies you on the CompSoc website. You'll use it at the start of any posts you write. For instance, this post has the following lines at the top:

```
---
    author: tbrb
---
```

If you want to preview your post, we've included a handy little script which works at minimum on Linux, while the only requirement is to have Docker installed. First, change `_config.yml` and comment line 15, while uncommenting line 14. Afterwards, simply run `preview.sh` and Docker will build and serve the CompSoc website locally for you. Any changes you make to the files will be reflected when you refresh your web browser too.

Once you've written a post and published it on GitHub, you can submit it in a pull request to the website2016 repository linked above. This will be reviewed by the SIG:Web team and published before you know it!

I hope you enjoy this website, and I look forward to receiving contributions!