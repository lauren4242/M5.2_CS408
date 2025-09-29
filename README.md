# web-dev-starter

This is a website showcasing accessibility in full-stack development.
It contains keyboard accessible elements, screen reader accessibility,
and colors with contrast for those with poor eyesight.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers
Color: The test result is that the background and foreground colors do not have
a sufficient contrast ratio, and points out that a low-contrast text is difficult
or maybe even impossible to read. (Rating: 75) After changes, the rating increased
to 82.

Semantic HTML:
When I try to navigate with a keyboard, the website takes me to the tabs, links, 
the search query, etc., but it doesn't navigate to "main content". Therefore, 
there is definitely room for improvement here, with <p> elements. The navigation 
menu should be placed in a header semantic element to make it more accessible

The Images:
I made the images more accessible by adding alt attributes to each of them.

The Audio Player:
For the audio, I added a button that displays the transcript of the audio when
pressed. it is italicized and quoted to separate the text from the rest of the
article.

The Forms:
For both the search and comments, I added labels to each <input>, and then changed
the visibility using a CSS section named .sr-only.

The Show/Hide Comment Control:
In truth, I wasn't able to figure out how to get this portion to function, although
it is keyboard accessible now.

The Table:
For the visuals of this table, I added a thicker line between the header and data,
bolded the text, and made the background a different color that is also visible to 
colorblind people (no matter their kind of color blindness).

Other Considerations:
I think that there could be better color combinations for those with poor eyesight
or colorblindness, that may help to visually separate sections of the page. As well
as that, for deaf users, there would need to be a lot more sounds describing the page,
reading the article, explaining where they are navigating on the page, etc.

## Sources

Github Copilot: "The forms" Accessibility CSS
Audio: https://www.shecodes.io/athena/3469-how-to-display-text-when-a-button-is-clicked-with-javascript
Color blindness colors: https://davidmathlogic.com/colorblind/#%23D81B60-%231E88E5-%23FFC107-%23004D40