# Easy Setup (Hugo + Netlify + Forestry)
Build your website with kross hugo theme by following this easy steps (No Coding Required)

<a href="http://bit.ly/meghna-hugo-installation" target="_blank" title="meghna hugo installation" rel="nofollow"><img width="100%" src="https://user-images.githubusercontent.com/37659754/70844354-4028be00-1e6a-11ea-8d84-02e9a25e7db8.png"></a>

In this tutorial we will show you to make your website live without buying any hosting and touching a single line of code. We made this tutorial based on [meghna hugo](https://github.com/themefisher/meghna-hugo) but you can setup everything like this.

### What you need !!

1. Git account (Ex: Github, Gitlab etc ) . In our case we use github.
2. [Netlify](https://bit.ly/netlify-account) account to host files and add custom domain .
3. [Forestry](https://bit.ly/forestry-account) account to maintain whole project without code.


### Step 1 : Fork or Clone repository

First we will fork this [vex hugo](https://github.com/themefisher/vex-hugo) template.

### Step 2 : Add your repository in Forestry

Go to your [forestry](https://bit.ly/forestry-account)  account and click on `import your site now`. declare your config.toml file [`exampleSite`] and fill up basic settings .

**Or just click this button for one click installation** [![import to forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=themefisher/vex-hugo&engine=hugo&version=0.73.0&config=exampleSite)

Now mark everything as done, then go to configuration to change the base url . You can put any url but this have to similar as netlify . So for now put a name which you are going to put in netlify as netlify subdomain.

### Step 3 : Setup and host website with Netlify

Here comes the last step . Go to your [netlify](https://bit.ly/netlify-account) account and click add new site . Choose your git repository to import your website in netlify .  And now you can see the forked `vex hugo` theme. select it and follow the steps. Then go to `site settings` for change the site name and put your subdomain name here what you put on forestry as base url. save it and go to `deploy` from top menu, Wait a while and click on `site preview` or just simply go to the subdomain you put as base url. **BOOM! Your site is live.** Now you can go to forestry and add, remove or customize every setting and content.

> If you face any issue regarding the installation feel free to [open a new issue](https://github.com/themefisher/vex-hugo/issues)

## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Main Features](#main-features)
- [What's New](#what's-new)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions-(paid))
- [Licensing](#licensing)
- [More Hugo Themes](https://themefisher.com/hugo-themes/)

## Demo

| Homepage  | Blog  | Product  | Contact  |
|---|---|---|---|
| ![Homepage](https://user-images.githubusercontent.com/58769763/87217772-ba70e080-c36e-11ea-8b7d-a0cf98191e84.png) | ![Blog](https://user-images.githubusercontent.com/58769763/87217775-be046780-c36e-11ea-8e10-acb45e54beaa.png) | ![product](https://user-images.githubusercontent.com/58769763/87217776-bfce2b00-c36e-11ea-891a-6f3157c35311.png) | ![contact](https://user-images.githubusercontent.com/58769763/87217777-c197ee80-c36e-11ea-8bd4-8b513cdebe78.png) |

[Live Demo](http://demo.themefisher.com/vex-hugo/).

**The images are only for demonstration purpose, Please don't use those images.**

## Installation
At the top we have shown an easy hugo installation. but still if you think you want to go with the traditional way then use the following commands:

**Note : You must use `hugo-extended` version to compile SCSS**

```
$ git clone git@github.com:themefisher/vex-hugo.git
$ cd vex-hugo/exampleSite/
$ hugo server --themesDir ../..
```


## Main features

* Fully Responsive Ready.
* Multilingual Support.
* Powered by bootstrap 4 framework.
* Product Showcase.
* Product Details Page.
* Snipcart Included.
* Blog Post.
* Contact Form.
* Email Subscription Section.
* Documented codes.

## What's New

* Multilingual Support.
* Product Details Page.
* Snipcart Included.
* Blog Post.
* Contact Form.

## Icons

To view the catalog of available themefisher-font icons, visit https://themefisher.github.io/themefisher-font/

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Vex Template. Please Search [existing issues](https://github.com/themefisher/vex-hugo/issues). It’s possible someone has already reported the same problem.
If your problem or idea is not addressed yet, [open a new issue](https://github.com/themefisher/vex-hugo/issues)

## Technical Support or Questions (Paid)

If you have questions or need help integrating the product please [contact us](mailto:mehedi@themefisher.com) instead of opening an issue.

## Licensing
Copyright &copy; 2020 Designed by [Themefisher](https://themefisher.com) & Developed by [Gethugothemes](https://gethugothemes.com)

**Code License:** Released under the [MIT](https://github.com/themefisher/vex-hugo/blob/master/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their own licence, we don't have permission to share those image.

## Hire Us
We are available for Hiring of your next HUGO project. Drop Us a mail [mehedi@themefisher.com](mailto:mehedi@themefisher.com)

## Premium Themes

| [![Mega-Bundle-HUGO](https://gethugothemes.com/wp-content/uploads/edd/2019/09/Mega-Bundle-HUGO.png)](https://themefisher.com/products/hugo-mega-bundle/) | [![Adrian](https://gethugothemes.com/wp-content/uploads/edd/2019/12/adrian-ecommerce-template.jpg)](https://gethugothemes.com/products/adrian/) | [![influencer](https://gethugothemes.com/wp-content/uploads/2019/11/Influencer.png)](https://gethugothemes.com/products/influencer-hugo/) |
|:---:|:---:|:---:|
| **Hugo Mega Bundle**  | **Adrian**  | **Influencer**  |
