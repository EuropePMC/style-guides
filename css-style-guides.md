# CSS Style Guides

Here are CSS style guides used by EuropePMC (http://europepmc.org). It is mainly from these two projects with modifications:

 - [Google CSS style guide](https://google.github.io/styleguide/htmlcssguide.xml)
 - [BEM](http://getbem.com/)

## ID and Class Name Delimiters

Separate words in ID and class names by a hyphen.

Do not concatenate words and abbreviations in selectors by any characters (including none at all) other than hyphens, in order to improve understanding and scannability.

    /* Not recommended: does not separate the words “demo” and “image” */
    .demoimage {}

    /* Not recommended: uses underscore instead of hyphen */
    .error_status {}

    /* Recommended */
    #video-id {}
    .ads-sample {}


## ID and Class Naming Convension

ID and class names are delimited by hyphens. We use a double hyphen `--` to separate a category name and a more specific DOM identifier.

    /* Recommended: a search input box on Home page */
    #home--search-input {}

    /* Recommended: a shared button */
    .button--with-left-icon {}
    .button--large-primary {}


