# Docusaurus Tutorial :

- https://docusaurus.io/docs/en/tutorial-setup

```bash
# Install Docusaurus Project Dependencies:
-------------------------------------------------
$ npx docusaurus-init
npx: installed 24 in 12.731s
Website folder created!
::::::::::::::::::::::::::::::::::
Docusaurus installed in website folder!

-------------------------------------------------
# Create Docusaurus Example Project:
-------------------------------------------------
$ docusaurus-examples
Wrote docusaurus scripts to package.json file.

docusaurus-tutorial
├── Dockerfile
├── docker-compose.yml
├── docs
│   ├── doc1.md
│   ├── doc2.md
│   ├── doc3.md
│   ├── exampledoc4.md
│   └── exampledoc5.md
└── website
    ├── README.md
    ├── blog
    │   ├── 2016-03-11-blog-post.md
    │   ├── 2017-04-10-blog-post-two.md
    │   ├── 2017-09-25-testing-rss.md
    │   ├── 2017-09-26-adding-rss.md
    │   └── 2017-10-24-new-version-1.0.0.md
    ├── core
    │   └── Footer.js
    ├── package.json
    ├── pages
    │   └── en
    │       ├── help.js
    │       ├── index.js
    │       └── users.js
    ├── sidebars.json
    ├── siteConfig.js
    ├── static
    │   ├── css
    │   │   └── custom.css
    │   └── img
    │       ├── favicon.ico
    │       ├── oss_logo.png
    │       ├── undraw_code_review.svg
    │       ├── undraw_monitor.svg
    │       ├── undraw_note_list.svg
    │       ├── undraw_online.svg
    │       ├── undraw_open_source.svg
    │       ├── undraw_operating_system.svg
    │       ├── undraw_react.svg
    │       ├── undraw_tweetstorm.svg
    │       └── undraw_youtube_tutorial.svg
    └── yarn.lock
Done in 0.95s.

-------------------------------------------------
# Start Project in Dev Mode:
-------------------------------------------------
$ yarn start    # or, $ npm start

$ docusaurus-start
LiveReload server started on port 35729
Docusaurus server started on port 3000

-------------------------------------------------
# Production Build:
-------------------------------------------------
$ yarn build    # or, $ npm run build

$ docusaurus-build
generate.js triggered...
feed.js triggered...
feed.js triggered...
sitemap.js triggered...
Site built successfully. Generated files in 'build' folder.
Done in 30.12s.

-------------------------------------------------
# Publish the site into Github:
-------------------------------------------------
$ GIT_USER=rama5789 CURRENT_BRANCH=master npm run publish-gh-pages

> @ publish-gh-pages /home/rama/Downloads/github/docusaurus-tutorial/website
> docusaurus-publish

master
https://github.com/rama5789/docusaurus-tutorial.git
generate.js triggered...
feed.js triggered...
feed.js triggered...
sitemap.js triggered...
Site built successfully. Generated files in 'build' folder.
b86b99dd990f272515110f425d4cb3be9d4e8ec1
Cloning into 'docusaurus-tutorial-gh-pages'...
master
error: pathspec 'origin/gh-pages' did not match any file(s) known to git.
Switched to a new branch 'gh-pages'
::::::::::::::::::::::::::::::
Password for 'https://rama5789@github.com':
remote:
remote: Create a pull request for 'gh-pages' on GitHub by visiting:
remote:      https://github.com/rama5789/docusaurus-tutorial/pull/new/gh-pages
remote:
To https://github.com/rama5789/docusaurus-tutorial.git
 * [new branch]      gh-pages -> gh-pages
Website is live at: https://rama5789.github.io/docusaurus-tutorial
```
