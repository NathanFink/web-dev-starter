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

Color Concerns: changed from agreen background color to a white one for easier reading

Sematic HTML Concerns: Fixed the div class=nav to just nav and removed the depreciated fonts with a generic css rule with the same style and then added paragraph elements

Image Concerns: I've added an alt to each of the images for the screen users

Audio message concerns: providing a transcript for them within the webpage and a downloadable audio is added if audio isnt accessible

Froms Concerns: I've added the aria-label to the search input, for the comment inputs I've added the necessary labels and changed the css a little bit

Show/Hide comment concerns: I have changed it to a button instead of a div so that it can be tabbed to and then an enter press can open or close it

Table concerns: added a short summary and changed the scope of each row and column element to make things clear

## Running
Clone the github repository using

    git clone https://github.com/NathanFink/M4.2_Lab.git

Move into the directory

    cd NathanFink/M4.2_Lab

Open the project in Vscode

Install Live Preview on Vscode

Start the Live Preview from the Command Palette

If you wish to view this in your browser you can use the local url

    http://127.0.0.1:3000