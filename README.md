### Wardrobe

A collection of Jekyll themes made by [Mu-An](http://muan.co).<br />
This is work in progress, come back later. Star the repo or follow me on [Twitter](https://twitter.com/muanchiou) to get updates.

---

#### To-dos

1. <del>Pagination</del>
2. Syntax highlighting code for each theme
3. <del>Style titles</del>
4. Pretty date
5. <del>Instruction</del>
6. <del>RSS feed</del>
7. Category links
8. Signoff
9. <del>Move things out of includes</del>
10. <del>Style blockquotes</del>
11. Check image and iframe presentations in posts
12. Confirm installation commands
13. Move theme layouts to _include
14. Update to Jekyll 1.1.0

---

#### Instruction for new Jekyll sites

1. [Fork this repository](https://github.com/muan/jekyll-wardrobe/fork)
2. Clone your forked repository to your computer
3. Go to your directory and edit `_config.yml` to your preference
4. `gem install jekyll`
5. And you're all set, run `jekyll build` and then `jekyll serve -w`. Your site should be up at `http://localhost:4000`

* Add **baseurl** in your config file if your blog is not sitting on root.

---

#### Instruction for existing Jekyll sites

1\. Clone both **_layouts** and **themes** folders and also `index.html`, `about.html` and `categories.html`; make sure you're using the cloned layouts for pages <br />
2\. 
Set the following variables in `_config.yml`  

    theme:            # scribble/a/b
    signoff:          # your name
    facebook_appid:   # facebook appid for like button
    google_analytics: # google analytics id
    disqus_shortname: # disqus account name
    
    owner:            
      name:           # your name
      avatar:         # your avatar url
      bio:            # biography
    
    links: 
      - name:         Home
        url:          /
      - name:         Categories
        url:          /categories
      - name:         About
        url:          /about
        
---

#### Contact

[Twitter](https://twitter.com/muanchiou), [Blog](http://muan.co), [Email](mailto:hello@muan.co)
