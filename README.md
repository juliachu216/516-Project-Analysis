## What is Chronic Wasting Disease?

Chronic Wasting Disease (CWD) is a contagious neurological disease affecting deer, elk and moose. It causes a characteristic spongy degeneration of the brains of infected animals resulting in emaciation, abnormal behavior, loss of bodily functions and death.

CWD belongs to a group of diseases known as transmissible spongiform encephalopathies (TSEs). Within this family of diseases, there are several other variants that affect domestic animals: scrapie, which has been identified in domestic sheep and goats for more than 200 years, bovine spongiform encephalopathy (BSE) in cattle (also known as “mad cow disease”), and transmissible mink encephalopathy in farmed mink.

Several rare human diseases are also TSEs. Creutzfeldt-Jakob disease (CJD) occurs naturally in about one out of every one million people worldwide. Variant Creutzfeldt-Jakob disease (v-CJD) has been associated with the large-scale outbreak of BSE in cattle herds in Great Britain.

## Why are we concerned about Chronic Wasting Disease?

CWD poses serious problems for wildlife managers, and the implications for free-ranging deer and elk are significant:

* Ongoing surveillance programs are expensive and draw resources from other wildlife management needs.
* Impacts of CWD on population dynamics of deer and elk are presently unknown. Computer modeling suggests that CWD could substantially reduce infected cervid populations by lowering adult survival rates and destabilizing long-term population dynamics.
* Where it occurs, CWD may alter the management of wild deer and elk populations, and it has already begun to do so.
* Ultimately, public and agency concerns and perceptions about human health risks associated with all TSE’s may erode hunters confidence and their willingness to hunt in areas where CWD occurs.

## How do we study Chronic Wasting Disease in this project?

We propose to evaluate the effectiveness of Raman spectroscopy on skin biopsies from white-tailed deer infected with CWD.  Raman spectroscopy is a rapid, repeatable and widely used non-destructive analysis technology that has been widely used in many applications including diagnostic medicine. Application of Raman spectroscopy to an easily obtainable skin biopsy could transform our ability to identify CWD infected animals and control the spread of the disease.

### Samples preparation



### Raman Spectrum collection 



### Raman Spectrum Data Analyze






### Explore the data

Demonstrate what you would do to describe the data and if it has any patterns or anomolies.  Make some plots.

### Model the data

Build a model, fit the model, validate the model.

### Communciate and visualize the results

What did you learn and do the results make sense?  Revisit your initial question and answer it.  H

### Class Exercise

In each project, I'd like to see a homework assignment that the class can do/evaluate to learn more about your data.  This should be a reproducible notebook that allows them to learn one or more aspects of your data workflow.  It is also an opportunity to share your research with your colleagues.

Here is an example of a fantastic project website:

https://stephenslab.github.io/ipynb-website/

## Advanced Features

### Stylesheet (Advanced)

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts (Advanced)

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/slate/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Overriding GitHub-generated URLs (Advanced)

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/slate/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).


### Contributing (Advanced)

Interested in contributing to Slate? We'd love your help. Slate is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/slate`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
