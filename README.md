# jekyll-site
static microblog generated with the help of jekyll, hosted by GitHub

This is my scratch pad for learning about simple web development tidbits.

Built with the Hagura Jekyll theme. 'n' folders maintained with an individual listing and base url each. 
On the indexing page there is a custom theme used for each with the base url changed so that they return to the site root.
Otherwise posts will return to the folder base url. 

index.html in the root is hard coded and added to the website side manually. 
about.html isa hard linked, supplied to all other pages and is added to the website side manually.
index.html in each of the folders can be generated with the rest of the posts each time.

to generate portions of the website you will need to run jekyll build in each of the 'n' folders.
the destination paths and other config are in individual _config.yml
post themes (including the custom one for a folder index.html) will need to be copied and names refilled for each folder added if this grows
