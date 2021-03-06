Flickr-feed-viewer
=================

A simple responsive Flickr feed viewer using angular.js

The app is currently served from [here](http://mrudelle.github.io/Flickr-feed-viewer/app)

# Install

Put the content of `/app` at the root of your static webserver folder.

This project uses [SCSS](http://sass-lang.com/guide) to creat style sheets. The `.scss` files have to be compiled to have an effect on the webapge. For instance [Koala](http://koala-app.com/) is a good background real-time compiler (set the output directory to `app/css`).

**CSS files must not be modified manually** as they will be overwritten on scss compilation.

# Features

* View the **public Flickr feed** corresponding to a particular tag
* **Live tag search**: Just change the tag in the title and watch the feed refreshing itself
* **Mobile design, responsive design**: Layout adapted for small screen to allow a full user experience on any range of device
* View more information about a particular post
* **Link to Flickr** website for further details
* **Tag redirection**: click on a tag in the post view to see the public Flickr feed associated to this tag
* **Bad link handling**: tries to redirect you to the correct post on flickr when a specific post can not be found

# Future development

To see the future development projects see [the enhancement issues](https://github.com/mrudelle/Flickr-feed-viewer/issues?labels=enhancement&page=1&state=open).

# Browser Support

* Chrome (latest)
* Firefox (27+)
* Internet Explorer (9 and 10) see #10 why version 11 is not supported. (to be fixed in the future)
* safari (6 and 7)
