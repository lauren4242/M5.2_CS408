# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

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

TODO

The Forms:

The Show/Hide Comment Control:

The Table:

Other Considerations: