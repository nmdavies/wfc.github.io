# Website for the Within Families Consortium


## Local development

For local development

1. Clone the repository
2. Install Ruby and RubyGems
3. Install the required packages for the website by running `bundle install` inside the repository's root directory
4. Run `bundle exec jekyll serve --watch` to start the server
5. Open your browser and navigate to `http://localhost:4000/`

You can modify the markdown files and the new changes will be reflected in the browser in realtime.

## Deployment

The website's html files will be built automatically by running `bundle exec jekyll build`, and saved in the `docs/` folder. Once these changes are pushed to GitHub, the updated pages will be automatically deployed to the live website.


