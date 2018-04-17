# mrover.org
Jekyll Powered site for the University of Michigan Mars Rover Team

### Building the site
To build the site, simply run

    jekyll build

inside of the `mrover` directory, and move the `_site` folder to `/docs`:

    mv _site ../docs
    
The site in the /docs folder is the site that Github Pages will deploy.
Make sure that you add a file called CNAME that contains the text `mrover.org` to the docs folder.

### Note
Do not edit the `/docs` folder directly. This is automatically generated.
