<p align="center"><img width="50%" height="50%" src="docs/images/image-logo-graphic.png"></p>
<h1 align="center">Learnosity APIs CSS</h1>
<p align="center">All of the Learnosity CSS files in one place.</p>

---

## Table of Contents

* [Overview: what does it do?](#overview-what-does-it-do)
* [How can I use it?](#how-can-i-use-it)
* [Learnosity products](#learnosity-products)

## Overview: what does it do?
This repo is intended for developers who are looking for more information about the changes made to our CSS style between LTS releases.

This will help make migrations and upgrades to the newest LTS version easier and will help to reduce the amount of time needed to visually confirm the latest changes.

## How do I use it?
This repo contains one branch per active LTS release and a `developer` branch for the development only version. The branch naming structure will be similar to `lts/v2022.3.LTS`.

Within each branch contains an individual file per Learnosity API product. Only products which have UI elements will have a CSS files and these can be found in the `/css/` directory.

With individual LTS branches, it is possible to see the code diff between any two LTS versions here on GitHub. For example, if you are currently using `v2021.3.LTS` and are upgrading to `v2022.2.LTS` you will be able to use the following link to check for all styling differences:

[https://github.com/Learnosity/learnosity-apis-css/compare/lts/v2022.1.LTS..lts/v2022.2.LTS?w=1](https://github.com/Learnosity/learnosity-apis-css/compare/lts/v2022.1.LTS..lts/v2022.2.LTS?w=1)
* The base URL tells GitHub to compare branches - https://github.com/Learnosity/learnosity-apis-css/compare/
* The two versions listed tell GitHub to compare from v2022.1.LTS to v2022.2.LTS - `lts/v2022.1.LTS..lts/v2022.2.LTS`
* The `w=1` parameter will ignore whitespaces

The resulting page will list all CSS differences between the two specified LTS versions. From here, you will be able to see changes where we may have added styles for new features or modified older styles to improve the product accessibility. For a general summary of LTS to LTS styling changes, [check our migration guides on the Learnosity Help site](https://help.learnosity.com/hc/en-us/sections/360000194338-Long-Term-Support-Announcements).

## Learnosity products

The CSS files for each of the products below are compiled from the files that are served in the production environment.

### Learnosity Assessments
* Annotations API `/css/annotations.css`
* Assess API `/css/assess.css`
* Questions API `/css/questions.css`
* Items API - this product does not contain any CSS, see the above files instead.

### Learnosity Author
* Author API `/css/authorapi.css`
* Question Editor API `/css/questioneditor.css`

### Learnosity Analytics
* Reports API `/css/reports.css`
* Events API - this product does not contain any CSS, see Reports API and the Learnosity Assessments products.

## Further reading
Thanks for reading to the end! Find more information about developing an app with Learnosity on our documentation sites:

* [help.learnosity.com](http://help.learnosity.com/hc/en-us) -- general help portal and tutorials,
* [reference.learnosity.com](http://reference.learnosity.com) -- developer reference site, and
* [authorguide.learnosity.com](http://authorguide.learnosity.com) -- authoring documentation for content creators.

[(Back to top)](#table-of-contents)

