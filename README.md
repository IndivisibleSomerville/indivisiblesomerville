# Indivisible Somerville

Welcome to the Indivisible Somerville Github! 

Indivisible Somerville's website is build with the open-source blogging engine Ghost. We chose this because we wanted a way for members without a technical background to easily add content, while also giving our tech team the freedom and extensibility that comes with an open source platform designed with developers in mind. We feel that Ghost is much better suited to handle both of these use cases than something like Wordpress, Squarespace, or a static website.

We host our production and staging site on Digital Ocean in Droplets. This is relatively cheap - certainly cheaper than paying for a Wordpress theme and hosting - and makes it easy to manage sites, make backups, and spin up new Droplets if something fails.

Since we are not making changes to the Ghost engine (yet), this repo contains just the theme. On our staging droplet (http://104.131.108.130), we've set up a git repo at /var/www/ghost/content/themes. You can plug in the contents of this repo into a local or staging Ghost instance and it should update the appearance appropriately. (Note: we will have commits to master automatically go to the server and trigger a Ghost restart - this isn't done yet). 

## Contributing

To commit to the repo, please fork it and work on a feature branch. We will set up a guide on how to test Ghost locally to help you test changes. When you're ready, submit a pull request. 

To get started hacking on Ghost themes, check out the themes intro: http://www.freshtechtips.com/2014/04/create-custom-ghost-theme.html

## Wishlist

The issues tab contains a wish list of small features we'd like to have. Some are changes to the code in this repo, some are standalone projects. Feel free to start working on those at any time.
