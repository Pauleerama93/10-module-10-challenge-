# SVG Logo Maker

## Description
SVG Logo Maker is a Node.js command-line application that allows users to generate simple logos by specifying text, text color, shape, and shape color. The generated logo is saved as an SVG file.

## User Story
AS a freelance web developer  
I WANT to generate a simple logo for my projects  
SO THAT I don't have to pay a graphic designer

## Acceptance Criteria
- **GIVEN** a command-line application that accepts user input
- **WHEN** I am prompted for text
  - **THEN** I can enter up to three characters
- **WHEN** I am prompted for the text color
  - **THEN** I can enter a color keyword (OR a hexadecimal number)
- **WHEN** I am prompted for a shape
  - **THEN** I am presented with a list of shapes to choose from: circle, triangle, and square
- **WHEN** I am prompted for the shape's color
  - **THEN** I can enter a color keyword (OR a hexadecimal number)
- **WHEN** I have entered input for all the prompts
  - **THEN** an SVG file is created named `logo.svg`
  - **AND** the output text "Generated logo.svg" is printed in the command line
- **WHEN** I open the `logo.svg` file in a browser
  - **THEN** I am shown a 300x200 pixel image that matches the criteria I entered

## Installation
1. Clone the repository:
    ```sh
    git clone <Your repo url>
    ```
2. Navigate to the project directory:
    ```sh
    cd  <Your repo url>
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage
1. Run the application:
    ```sh
    node index.js
    ```
2. Follow the prompts to generate your logo:
    - Enter up to three characters for the logo text.
    - Specify a color for the text (e.g., `red` or `#ff0000`).
    - Choose a shape from the list (circle, triangle, square).
    - Specify a color for the shape (e.g., `blue` or `#0000ff`).

3. After entering all prompts, the generated `logo.svg` file will be saved in the project directory, and you will see the message "Generated logo.svg" in the command line.

## Walkthrough Video
[Link to Walkthrough Video](https://drive.google.com/file/d/1DmRB8j-jsxygj3Z1AOaiC1ONume5bDz7/view)

## Credits

I would like to extend my deepest gratitude to my teachers, Drew and Kyle, for their invaluable guidance and support throughout the development of this module. Their expertise and encouragement were instrumental in helping me navigate the challenges and successfully complete this project.

A special thanks to Drew for his speed runs, which were exceptionally helpful in understanding the concepts and techniques required to optimize performance and efficiency.

Thank you both for your dedication to teaching and for inspiring me to achieve my best.


## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
