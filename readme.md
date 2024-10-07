# JigsawPuzzleSolver

Welcome to **JigsawPuzzleSolver**, an intelligent jigsaw puzzle solver that utilizes advanced image processing techniques to analyze and solve puzzles efficiently. This project aims to take a set of puzzle pieces, identify their shapes, and reassemble them into the original image.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Limitations](#limitations)
- [Contributing](#contributing)
- [Credits](#credits)

## Features

- Image processing to detect edges and corners of puzzle pieces.
- Algorithmic matching to find correct placements for pieces.
- Visualization of the puzzle-solving process.
- Ability to handle various puzzle sizes and shapes.

## Installation

To get started with **JigsawPuzzleSolver**, you'll need to clone this repository and install the required dependencies. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/RaviPatel021/JigsawPuzzleSolver.git

2. Navigate to the project directory:
    ```bash
    cd JigsawPuzzleSolver

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt


## Usage

1. Open the Jupyter Notebook (`jigsaw_solver.ipynb`).

2. Change the photo path in the notebook to point to your scrambled jigsaw image. Look for the following line in the notebook:
   ```python
   image_path = "path/to/your/scrambled/image.jpg"  # Change this to your image path
   ```

3. Modify the debug flag in the notebook to check for errors:
   ```python
   DEBUG_MODE = True  # Set to True to enable debug mode for error checking
   ```

4. Run the entire notebook by selecting **Cell > Run All** from the Jupyter Notebook menu.

## Limitations

- **Image Source**: The solver only works with images from [Jigsaw Explorer](https://www.jigsawexplorer.com/). This limitation arises because the project focuses on analytical methods and machine learning models tailored for specific puzzle images.
  
- **Analytical Methods**: The analytical techniques employed, such as background removal and corner detection, are not flawless and may lead to inaccuracies during the solving process.
  
- **Machine Learning Models**: The machine learning components are not sufficiently trained to handle all scenarios, which restricts the solver's effectiveness. 

Due to these factors, the puzzle-solving capability is limited to images from the specified website, and even then, it may not work reliably in every case.

## Contributing

We welcome contributions to enhance the functionality and performance of this jigsaw puzzle solver. Here’s how you can contribute:

1. **Fork the Repository**: Click on the “Fork” button at the top right of the repository page to create your own copy of the repository.

2. **Clone Your Fork**: Use the following command to clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/jigsaw-puzzle-solver.git
   ```

3. **Create a New Branch**: Before making any changes, create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```

4. **Make Your Changes**: Implement your improvements or fixes in your new branch.

5. **Commit Your Changes**: After you’ve made your changes, commit them with a descriptive message:
   ```bash
   git commit -m "Add new feature or fix bug"
   ```

6. **Push to Your Fork**: Push your changes back to your fork on GitHub:
   ```bash
   git push origin feature-name
   ```

7. **Create a Pull Request**: Go to the original repository where you want to contribute, and you’ll see an option to create a pull request. Provide a clear description of your changes.

8. **Discussion and Review**: Your pull request will be reviewed by the contributors, and you may be asked to make additional changes before it can be merged.

Thank you for considering contributing to this project!


## Credits

This project is a collaborative effort, and we'd like to acknowledge the contributions of the following individuals:

- **Ravi Patel** - Project lead and primary contributor
- **Jason Dang** - Primary contributor
- **Julia Braun** - Primary contributor