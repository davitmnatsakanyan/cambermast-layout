# cambermast-layout
This is the CSS Grid layout for the Cambermast website, prior to adding to Jekyll.

https://billraymond.github.io/cambermast-layout/

## Developer setup
This will ultimately be a Jekyll site, but the following are only required for this repo:
1. Visual Studio Code.
2. Live Sass compiler extension.
3. Live Server extension.

After you repo the code, click the "watch sass" link at the bottom of VSCode.

Right-click the index.html file and choose "open with live server" to see the code running in a browser.

The entire site is static HTML/SCSS/CSS Grid/Flexgrid. No javascript.

## Layout
Look in the images/design folder for the current layout from the designer. There may be some changes.

## Layout
The scss folder uses the 7-1 method, but not all seven :-). See following folder structures currently in place.

/scss/layout
 - Here you will find all the files as the relate to each part of the css grid. As of this writing, only for the landing page.

/scss/abstracts
- Any functions, mixins, or variables.

/scss/base
- Typography and font styles.

/scss/main
- Any new style file gets imported here so it is the main style sheeet when the scss is compiled.

## Site layout
- Everything should use CSS grid.
- Right now, the site is mobile when <768 pixels (defult) and "full screen" when >= 768 pixels.

## TODO
Go to the index.html page and scroll to the bottom. Currently working on the "services_area".

Look further down index.html and you will see the commented areas still to be designed.

As of this writing, none of the other pages have been created. It is the structure that is really in place, not necessarily the site.

## Image sizes
Logo: 250x35
Banners: 1366px by 500px
Block images (services): 720px by 550px

