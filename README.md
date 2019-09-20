# hello: a minimalist template for personal websites on Github Pages

## Why **hello**?  
  
**hello** has a simple goal: to make GitHub Pages accessible to everyone.  
  

**hello** is a minimalist template that lets you design a beautiful website or portfolio on GitHub Pages - without installing a Ruby
development environment, learning to use Jekyll, **or even typing a single line of code**. It's ideal for GitHubbers
who want to start building their personal website on [GitHub Pages](https://pages.github.com/), but maybe aren't so familiar with web development.
  

The default layout of **hello** is a streamlined single page with three major customizable sections: a required "about" section, an optional portfolio, and an optional CTA. Using [Liquid](https://shopify.github.io/liquid/) variables declared by in the config and index files, **hello** offers an easy-to-use design where all customizations necessary for a basic personal website can be written in [Markdown](https://www.markdownguide.org/basic-syntax/). **hello** is adapted from [Twenty](https://html5up.net/twenty), a responsive, mobile-friendly theme by HTML5 Up.  


Demo **hello** [here](https://saragong.github.io/hello/).

## Getting started
To use **hello**, follow these steps:

1. Click the green "Use this template" button on the main page of the **hello** repository.

2. Follow the instructions to create a new repository from **hello**, setting the repository name as "*your-username*.github.io".

3. Under **Settings** for this new repo, navigate to the **GitHub Pages** section and ensure that GitHub Pages is enabled for the `master` branch.

4. On the command line, clone this new repository to your local directory.

```
$ git clone https://github.com/*your-username*/*your-username*.github.io.git
```

5. Navigate into the project folder, open the `_config.yml` and `index.md` files in your preferred text editor, and start customizing your website!

6. When you're ready to see your work, commit your changes to the remote repo.
```
$ git add .
$ git commit -m "first commit"
$ git push origin master
```

7. In just a few moments, Github will build your shiny new website at "https://*your-username*.github.io/".

## Usage

### The following variables are required:

`_config.yml`:
* `title`
* `author`
* `description`
* `baseurl`  

`index.md`:
* `banner_title`
* `banner_subtitle`
* `background_image`

### The following variables are optional:
`index.md`:
* `favicon`
* `facebook_username`
* `twitter_username`
* `github_username`
* `linkedin`
* `google_analytics` (your Google Analytics Tracking ID)

By declaring these variables, you can include a button that links to an external website or to media.
* `about_button` (the link)
* `about_button_label` (the label on the button)

By declaring these variables, you can include a portfolio showcasing your work and organize your portfolio's items into a custom layout, all without adding any CSS. In addition, you must 1) create an HTML file in the_includes folder for each project with the text you'd like to display, and 2) create a YAML file in the _data folder describing how each project should be shown and categorized. See `/includes/example.html` and `/_data/work.yml` for examples.
* `portfolio` (the heading for your portfolio and title of your YAML file)
* `portfolio_description` (a description to be displayed below the heading and above the content)

By declaring these variables, you can include a CTA section.
* `cta` (the heading for your CTA section)
* `cta_description` (a description to be displayed below the heading and above the content)
* `cta_button` (a link to an external website or to media)
* `cta_button_label` (the label on the button)

## Additional Information
Created by [Sara Gong](https://saragong.github.io/), University of Southern California.  

This work is licensed under the MIT License, which lets you use, modify, and publish adaptations of this template free of charge and without restriction, as long as you preserve all copyright notices and licenses.  

This original theme, of which this is an adaptation, is licensed by HTML5 Up under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/).  

The images from the demo website are from [Unsplash](https://unsplash.com/).

## Theme Information
Twenty by HTML5 UP  
html5up.net | @n33co  
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)