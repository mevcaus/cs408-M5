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

# Color:
1. The current colors did not contrast well enough. I updated the main background color to Turqouise and the text to black.

# Semantic HTMl:
1. Currently when tabbing the website it makes large jumps and the comments aren't stopped at.
2. I removed all the <br> and replaced them with <p> tags. I also changed the div with class nav to an actual <nav>. The table headers were also just <td> instead of <th>.
3.the <div> should be replaced with <nav> which I did.

# Images
1. alt attribute was added to make the images screen readable

# Audio Player
1. For hearing impaired people there is a link to download the transcript of the audio
2. For browsers that don't support audio I included a download link for the audio

# Forms
1. The aria-label atrribute makes the label only readable for screen readers.
2. The for attribute specifies which input the label is for

# Show-Hide Comment Control
1. By changing it to a button it can now be tabbed to and enter toggles the show/hide.

# Table
1. The headers were changed to TH. And a caption was added to summarize the information

# Other Considerations
1. you could add special css rules for when focusing on a clickable object to help visually impaired users
2. Adding a lang attribute to the html to help screen readers recognize the words are all in english.