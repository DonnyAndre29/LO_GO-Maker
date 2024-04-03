# SVG Logo Maker

## Task

Your task is to build a Node.js command-line application that takes in user input to generate a logo and save it as an [SVG file](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). The application prompts the user to select a color and shape, provide text for the logo, and save the generated SVG to a `.svg` file.



### User Story

```md
AS a freelance web developer
I WANT to generate a simple logo for my projects
SO THAT I don't have to pay a graphic designer
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for text
THEN I can enter up to three characters
WHEN I am prompted for the text color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I am prompted for a shape
THEN I am presented with a list of shapes to choose from: circle, triangle, and square
WHEN I am prompted for the shape's color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I have entered input for all the prompts
THEN an SVG file is created named `logo.svg`
AND the output text "Generated logo.svg" is printed in the command line
WHEN I open the `logo.svg` file in a browser
THEN I am shown a 300x200 pixel image that matches the criteria I entered
```

## Mock-Up

![Square](/Examples/logo.svg)


## Usage

Use the command line to navigate to the directory of the application.

Install all dependencies (npm i), then type the command node index.js. 

You will then be taken through a series of questions. 

Once all questions have been answered properly, a message will display to the command line telling you your logo has been generated.

Find your new logo in the newly generated SVG file.

## Visuals

![Walkthrough Video](/Images/Untitled_%20Apr%202,%202024%2011_11%20PM.gif)


## Test

Open the terminal, and use the command npm test.

![Test](/Images/Untitled_%20Apr%202,%202024%2011_47%20PM.gif)

## Installation

Inquirer v.8.2.4

Jest


## License

MIT

