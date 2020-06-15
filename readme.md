Microsite CSS
=============

A simple example website showing how to use the JNCC Website CSS to make a microsite with the same look and feel.

Open it up as as file in your browser like `file:///home/pete/work/microsite-css/index.html`.

The `frontend-orignal` folder is taken directly, for reference, from the `frontend` folder in the JNCC Website source code, as created by the website contractor Carbon Six Digital, on 11 April 2019.

The `frontend` folder here contains just those files we determined were needed to make a microsite. You could copy additional files from the original source if necessary.

> A production build of a microsite could reference all the files in `frontend` in the parent JNCC website (like `../frontend` or whatever) to save the user needing to download these files, some of which are fairly large, more than once.

To make a new microsite, copy the `frontend` folder from here into your project and use `index.html` as a reference for building the markup.

Notes
-----

- The JNCC logo always takes you to the JNCC home page
- Search in the header forwards the query to a separate JNCC search site for consistency. Microsite search, if needed, can be done in some other way appropriate to the microsite.
- The first menu item is `< Main site`. Users do not all look at or understand URLs. The microsites just "look like a different menu" in the JNCC Website. The first menu item is the name of the microsite, and any subsequent menu items within the microsite can go to the right.
- The logo next to the Microsite name is the database icon by default but could be something else if you can find something better.
- If you don't want the massive 'hero image' on a page, you annoyingly need to add the class `no-page-hero` to the `top-bar nav` element, which is probably going to be in your master page template.
- The footer will need updating to match the current live JNCC Website content.
