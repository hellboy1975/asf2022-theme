---
title: Home
body_classes: 'title-center title-h1h2'
banner:
    headline: 'Secrets of the Nullarbor'
    follower: 'Presented by the ASF and the SA Speleo Council'
    blurb: 'A 5-day caving conference held in Ceduna, and with field trips to the Nullarbor'
hook:
    teaser: 'Pellentesque viverra vulputate enim. Aliquam volutpat. Pellentesque tristique Risus'
    byline: 'In posuere eleifend odio. Quisque semper augue mattis wisi. Maecenas ligula. Pellentesque viverra vulputate enim. Donec pulvinar ullamcorper metus.'
    button:
        text: 'This is a test'
        target: '#'
cta:
    headline: 'Cras vitae metus aliNuam'
    copy: 'Pellentesque pede. Donec pulvinar ullamcorper metus. In eu odio at lectus pulvinar mollis. Vestibulum sem magna, elementum vestibulum arcu.'
    button:
        text: 'Nulla aluctus eleifend'
        target: '#'
notices:
    heading: 'Cras vitae metus aliNuam'
    byline: 'pulvinar mollis. Vestibulum sem magna, elementum vestibulum arcu.'
    items:
        -
            icon: cogs
            heading: 'Nulla luctus eleifend'
            point: 'In posuere eleifend odio. Quisque semper augue mattis wisi. Maecenas ligula pellentesque.'
        -
            icon: wrench
            heading: 'Etiam posuere augue'
            point: 'Maecenas ligula. Pellentesque viverra vulputate enim. Aliquam erat volutpat liguala.'
        -
            icon: leaf
            heading: 'Fusce ultrices fringilla'
            point: 'Maecenas pede nisl, elementum eu, ornare ac, malesuada at, erat. Proin gravida orci porttitor.'
        -
            icon: cogs
            heading: 'Nulla luctus eleifend'
            point: 'In posuere eleifend odio. Quisque semper augue mattis wisi. Maecenas ligula pellentesque.'
        -
            icon: wrench
            heading: 'Etiam posuere augue'
            point: 'Maecenas ligula. Pellentesque viverra vulputate enim. Aliquam erat volutpat liguala.'
        -
            icon: leaf
            heading: 'Fusce ultrices fringilla'
            point: 'Maecenas pede nisl, elementum eu, ornare ac, malesuada at, erat. Proin gravida orci porttitor.'
        -
            icon: cogs
            heading: 'Nulla luctus eleifend'
            point: 'In posuere eleifend odio. Quisque semper augue mattis wisi. Maecenas ligula pellentesque.'
        -
            icon: wrench
            heading: 'Etiam posuere augue'
            point: 'Maecenas ligula. Pellentesque viverra vulputate enim. Aliquam erat volutpat liguala.'
        -
            icon: leaf
            heading: 'Fusce ultrices fringilla'
            point: 'Maecenas pede nisl, elementum eu, ornare ac, malesuada at, erat. Proin gravida orci porttitor.'
portals:
    heading: 'Cras vitae metus aliNuam'
    byline: 'pulvinar mollis. Vestibulum sem magna, elementum vestibulum arcu.'
    items:
        -
            thumbnail: person.png
            alt: 'Molly Millions'
            target: '#'
            heading: 'Molly Millions'
            teaser: 'In posuere eleifend odio quisque semper augue wisi ligula.'
        -
            thumbnail: person.png
            alt: 'Henry Dorsett Case'
            target: '#'
            heading: 'Henry Dorsett Case'
            teaser: 'In posuere eleifend odio quisque semper augue wisi ligula.'
        -
            thumbnail: person.png
            alt: 'Willis Corto'
            target: '#'
            heading: 'Willis Corto'
            teaser: 'In posuere eleifend odio quisque semper augue wisi ligula.'
        -
            thumbnail: person.png
            alt: 'Linda Lee'
            target: '#'
            heading: 'Linda Lee'
            teaser: 'In posuere eleifend odio quisque semper augue wisi ligula.'
---

### Suspendisse dictum porta

Donec leo. Vivamus fermentum nibh in augue. Praesent a lacus at urna congue rutrum. Nulla enim eros, porttitor eu, tempus id, varius non, nibh. Vestibulum imperdiet, magna nec eleifend semper augue mattis wisi maecenas ligula nunc lectus vestibulum euismod lacinia quam nisl.    
---
# Say Hello to Grav!
## installation successful...

Congratulations! You have installed the **Base Grav Package** that provides a **simple page** and the default **Quark** theme to get you started.

!! If you see a **404 Error** when you click `Typography` in the menu, please refer to the [troubleshooting guide](http://learn.getgrav.org/troubleshooting/page-not-found).

### Find out all about Grav

* Learn about **Grav** by checking out our dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, **themes**, as well as other Grav **skeleton** packages from the [Grav Downloads](http://getgrav.org/downloads) page.
* Check out our [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.

!!! If you want a more **full-featured** base install, you should check out [**Skeleton** packages available in the downloads](http://getgrav.org/downloads).

### Edit this Page

To edit this page, simply navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in your [editor of choice](http://learn.getgrav.org/basics/requirements).  You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

### Create a New Page

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `03.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/03.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: The page will automatically show up in the Menu after the "Typography" menu item. If you wish to change the name that shows up in the Menu, simple add: `menu: My Page` between the dashes in the page content. This is called the YAML front matter, and it is where you configure page-specific options.
