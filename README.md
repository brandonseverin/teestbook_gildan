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

Make sure that you are in the main/master branch.

Nota Bene: There is a time delay which can be quite a while > 5 minutes, sometimes 24 hours if there are a lot of changes for the site to update once you have run `gulp publish`.


What I really want to do create a bash script that automates the indexing of the pages to the summary file.   

Here is another great tutorial: https://medium.com/@richdayandnight/simple-tutorial-on-hosting-your-gitbook-documentation-on-github-pages-bonus-with-gitbook-editor-f27f60d5d408

