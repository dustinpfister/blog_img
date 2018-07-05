## blog_img

This is a repo of images that I aim to use in my blog.

## gh-pages branch

This project makes use of the gh-pages branch so that the images can be accessed via https://[username].github.io/blog_img/posts/[post#]/[imagefilename]. So when editing this project make sure to merge any changes made in master to gh-pages, or vise versa.

To list branches, and find out what branch I am currently using.
```
$ git branch
```

To switch to gh-pages from master

```
$ git checkout gh-pages
```

To merge changes made in master to gh-pages, assuming that I am currently on gh-pages.

```
$git merge master
```