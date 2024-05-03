# Nutrition Label Web Page

This is a simple HTML document that displays a nutrition label. The label includes information about serving size, calories, and various nutrients.

## Structure

The HTML document is structured as follows:

- The `head` section includes meta information, the page title, and links to external CSS stylesheets.
- The `body` contains a `div` with the class `label`, which represents the nutrition label.
- Inside the `label` div, there are several sections divided by `div` elements with the class `divider`.
- The `header` section includes the title of the label and serving size information.
- The `calories-info` section displays the amount of calories per serving.
- The `daily-value` section lists various nutrients and their daily value percentages.
- A `note` at the end explains what the daily value percentages mean.

## Styling

The page uses two external stylesheets:

1. Google Fonts stylesheet for the 'Open Sans' font.
2. A local stylesheet located at `./resources/styles.css`.

Various CSS classes are used to style the elements, such as `bold`, `right`, `sm-text`, `indent`, `dbl-indent`, `no-divider`, and size variations of `divider`.

## Usage

To view the page, simply open the HTML file in a web browser. The nutrition information is hardcoded into the HTML, so any changes to the information would require modifying the HTML source code.