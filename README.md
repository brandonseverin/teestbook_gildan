# Introduction

This is a test gitbook. After an afternoon of trying to install node.js successfully on a mac I followed [this tutorial](https://galdin.dev/blog/publishing-gitbook-to-github-pages/) to produce a gitbook via github pages. Now I am testing how it works.

So it appears to work in the following manner:

You make edits/add a markdown page.

Then you add that markdown page to the SUMMARY.md file including the path to the folder whcih the page is in (acts as a section) plus the path to the page. If one doesn't do this, then the page will not appear in the side bar. 

The run the following commands make sure that you are in the main/master branch.

```bash

git add .

git commit -m "updated docs"

git push

gitbook build

gulp publish

```

make sure that you are in the main/master branch
