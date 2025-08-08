# Algorithm Optimization Project - Machine Learning

[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-algorithm-optimization-project-machine-learning/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-algorithm-optimization-project-machine-learning/actions/workflows/codespaces/create_codespaces_prebuilds)

A comprehensive programming optimization project focused on improving algorithm efficiency and code performance. This project demonstrates essential optimization techniques through practical exercises involving text processing and list operations.

![Project Preview](assets/preview.png)


## Project Overview

This project focuses on algorithm optimization through two main exercises that teach fundamental performance improvement techniques:

**Exercise 1: Text Processing Optimization**
- Convert text to lowercase
- Remove punctuation marks efficiently
- Count word frequencies
- Extract most common words

**Exercise 2: List Processing Optimization**
- Filter even numbers from lists
- Duplicate list elements
- Sum numerical values
- Prime number detection

The project provides hands-on experience with:
- Code refactoring and optimization
- Efficient data structure usage
- Python built-in function utilization
- Modular programming practices
- Performance analysis and improvement


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you loose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (dependencies are pre-installed)

3. **Start Working**
   - Open `notebooks/assignment.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook

### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.10

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/assignment.ipynb
   ```


## Project Structure

```
├── .devcontainer/        # Development container configuration
├── assets/               # Files and resources directory
│
├── notebooks/            # Jupyter notebook directory
│   ├── assignment.ipynb  # Assignment notebook with exercises
│   └── solution.ipynb    # Solution notebook with optimized code
│
├── .gitignore            # Files/directories not tracked by git
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```


## Learning Objectives

1. **Algorithm Analysis**: Identify performance bottlenecks in existing code
2. **Data Structure Optimization**: Use appropriate Python data structures for efficiency
3. **Built-in Functions**: Leverage Python's optimized built-in functions
4. **List Comprehensions**: Replace loops with more efficient comprehensions
5. **Modular Design**: Break code into focused, reusable functions
6. **Performance Comparison**: Understand the impact of different approaches

## Technologies Used

- **Python 3.11**: Core programming language
- **Collections**: Counter for efficient frequency counting
- **String**: Built-in string processing utilities
- **Math**: Mathematical operations and functions
- **Jupyter**: Interactive development environment


## Contributing

This is an educational project. Contributions for improving the optimization examples or adding new exercises are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request
