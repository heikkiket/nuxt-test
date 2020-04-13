# MANUAL

Clone the repository and test demo site for example with

    cd nuxt-test/dist
    python -m SimpleHTTPServer

(Then navigate to http://localhost:8000)


## Editing the site

If you don't have node and npm installed, try this:
 ( sudo apt install nodejs npm )

    npm install
    
    npm run dev
    
    
(dev site runs in localhost:3000)

Now you can alter the code to your liking.

Pages contains all pages. Assets has static files like images and css.
Layouts contains the default layout and other optional layouts.

All pages are Vue components. Their HTML must be inside template-element. In template element, only single root element is allowed. Wrap everything inside div for starters.

* See more: https://nuxtjs.org/guide
* More about single page Vue components: https://vuejs.org/v2/guide/single-file-components.html

## Compiling the site:

    npm run generate

Now the compiled site is inside /dist.
