# Reflections

This site was generated using [Hugo](https://gohugo.io) for a Harvard Final Reflection

## Running the Server

Run `hugo server -w -v` in order to locally run the website. If you don't have it downloaded, I would recommend following [this guide](https://gohugo.io/getting-started/quick-start/) for the first 2 or so steps

## Contributers and How we Split the Work

### [Andrea](https://github.com/andreafoo11)

- Provided all of the information, images, and styling in addition to finding the proper Hugo theme
- Setup the Github Action portal
- Co-implemented changes to the template
- Changed the `config.toml` file to match what was necessary in the code

### [Alex](https://github.com/alexz12948)

- Co-implemented changes to the template
- Changed the `config.toml` file to match what was necessary in the code
- Wrote the Github Pages Action to allow for a CD pipeline for the repository

## Resources Used

- For the theme, we used the [mediumish](https://themes.gohugo.io/themes/mediumish-gohugo-theme/) theme
- For GH action documentation, we used [this](https://docs.github.com/en/actions/quickstart) to remind ourselves how it works
- Used [this guide](https://gohugo.io/hosting-and-deployment/hosting-on-github/) to get deployment to work
- For GH actions around the deployment suggestion from the guide, we needed to look at [this](https://github.com/peaceiris/actions-gh-pages#%EF%B8%8F-first-deployment-with-github_token) to understand how a Github token worked