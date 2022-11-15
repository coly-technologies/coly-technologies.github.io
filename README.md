## Repo to host web API of coly rest-api

This repo is used to host the api documentation of coly. 

Github pages works by publishing the contents of [username].github.io to https://[username].github.io/

By putting an index.html file in the root we can therefore host our own site. 

Clone this repo and follow the steps below.


### How to publish changes in our api-docs/github pages.

**Let's keep things simple by writing in the markdown file coly-api.md, exporting it as html from a markdown editor, then publishing.**

To do that, follow these **steps**:

1. Do your changes in the file `coly-api.md`. After you've decided you want to publish these changes continue with the next steps. 
2. Export the contents of `coly-api.md` to html using a markdown editor (preferably [Typora](https://typora.io/))*. Consider that different markdown editors might format documents differently. The nicest looking one I could find was typora, so let's start with using that one (unless you have a better idea). Ping Mats if you don't want to get it, and he'll export the html file for you.
3. Name the exported file `index.html` and put it in the root, replacing the old one. 
4. Commit changes, and push.
5. Updates are now done and available automatically, and available at https://coly-technologies.github.io/



---

**tl;dr** No need to read any further unless you're curious. 

---

#### Why go through the manual step of exporting .md to html?

There are plenty of ways around this manual step. Two examples I've considered is:

* Setting up a jekyll static site generator that converts the .md files for us. This is a recommended approach for github pages. See instructional video [Here](https://www.youtube.com/watch?v=VDOyjwWPKs4).
* Import the .md file straight into index.html using zero-md, as suggested in [this post](https://stackoverflow.com/questions/37770620/how-to-include-markdown-md-files-inside-html-files). 

However, for now that might be a bit overkill since we only have a single file to care about. It's also not always possible to the formatting to be as nice. For example code snippets with highlighting, and mermaid graphs might not be supported, zero-md for instance removes formatting completely.

Let's consider the above examples if we would ever need them in the future.
