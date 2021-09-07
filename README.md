# Files to Build John Christian Gaby's Personal Website

This repository contains the files needed to build [John Christian Gaby's personal website](https://chrisgaby.github.io/).

## Content

The website is built with [Hugo](https://gohugo.io/), a static website builder, using a template for the `Academic` theme, which has since undergone multiple updates and has been rebranded [Wowchemy](https://wowchemy.com/).

The website content is created using Markdown, RMarkdown, and Jupyter Notebook.

The website is formatted as a Curriculum Vitae to provide up-to-date information on John Christian Gaby's career accomplishments and professional skills. It is also a site where he publishes blogposts on bioinformatics and data analysis. In addition, in the blogposts section he has also published galleries of some examples of his botanical photography.

## Use These Commands to Rebuild and Push to Github

In the root repository folder for the website, use the following BASH commands to push changes to the GitHub repository the contains the files needed to build the website:

1. `git add .`
2. `git commit -m "Repo update blogpost 2"`
3. `git push -u origin master # use '--force' if necessary`

Next, build the website with Hugo, which creates and organizes all the files needed for the website in the `pubic` folder off of the root repository folder, and then push the `public` folder to GitHub:

1. `hugo`
2. `cd public`
3. `git add .`
4. `git commit -m "Web update blogpost 2"`
5. `git push origin master`

To check the appearance of the website before pushing, one can run the BASH command 'hugo server' then open http://localhost:1313/ in a web browser.

## License

The original Academic theme for Hugo is copyright of [George Cushen](https://georgecushen.com), 2017-present, and is released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.
