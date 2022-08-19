<p align="center"><img width="50%" height="50%" src="docs/images/image-logo-graphic.png"></p>
<h1 align="center">Learnosity APIs CSS</h1>
<p align="center">All of our production CSS files in one place.</p>

---

## Table of Contents

* [Overview: what does it do?](#overview-what-does-it-do)
* [How can I use it?](#how-can-i-use-it)

## Overview: what does it do?
This repo is intended for developers who are looking for more information about the changes made to our CSS style between LTS releases.

This will help make migrations and upgrades to the newest LTS version easier and will help to reduce the amount of time needed to visually confirm the latest changes.

## How do I use it?
This repo contains one branch per active LTS release and a `developer` branch for the development only version. The branch naming structure will look like `lts/v2022.3.LTS`.

Within each branch is an individual file per Learnosity API product. Only products which have UI elements will have a CSS files. These can be found under the CSS folder.

Learnosity Assessments
* `css/annotations.css`
* `css/assess.css`

Learnosity Questions
* `css/questions.css`

Learnosity Author
* `css/authorapi.css`
* `css/questioneditor.css`

Learnosity Analytics
* `css/reports.css`

Note: these CSS files are the generated output of what you can see in production.

With multiple branches, you are able to see the code diff between any two LTS versions here on GitHub. For example, if you are currently using `v2021.3.LTS` and are upgrading to `v2022.2.LTS` you will be able to go to:
[https://github.com/Learnosity/tools-apis-css-publisher/compare/lts/v2022.1.LTS..lts/v2022.2.LTS?w=1](https://github.com/Learnosity/tools-apis-css-publisher/compare/lts/v2022.1.LTS..lts/v2022.2.LTS?w=1)
This page will list all of the CSS differences between the two specified LTS versions. From here, you will be able to see changes where we may have added styles for new features or modified older styles to improve the product accessibility. For a general summary of LTS to LTS styling changes, [check our migration guides on the Learnosity Help site](https://help.learnosity.com/hc/en-us/sections/360000194338-Long-Term-Support-Announcements).

## Further reading
Thanks for reading to the end! Find more information about developing an app with Learnosity on our documentation sites:

* [help.learnosity.com](http://help.learnosity.com/hc/en-us) -- general help portal and tutorials,
* [reference.learnosity.com](http://reference.learnosity.com) -- developer reference site, and
* [authorguide.learnosity.com](http://authorguide.learnosity.com) -- authoring documentation for content creators.

[(Back to top)](#table-of-contents)

