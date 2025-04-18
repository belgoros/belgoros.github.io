# NerdAbility - A CV Generator

A Jekyll based CV page generator.

## Making your own CV

To make your own GitHub hosted CV:

1. Fork this repo into your github account
2. Click the "Settings" button in your new forked repository (in the menu on the right), and change the repository's name to `{{yourusername}}.github.io`, replacing your username with your GitHub user name.
3. Update `/_config.yml` with the details of your CV - the comments will explain what is required.
4. Push to your github remote resitory.
5. Visit `http://{{yourusername}}.github.io` to check it out.
6. Share your new CV/Profile with the world!

## Running

If you want to test it locally:

- install **Ruby** & **Jekyll**
- clone the repository locally
- run `bundle` to install dependencies
- `jekyll serve`
- navigate to `localhost:4000`

## Deploying

If you want to host the page on your own web hosting, you will need to run it locally and jekyll will build the site files to the `/_site` directory which you can then push to your hosting provider - See https://jekyllrb.com/ for more details.
