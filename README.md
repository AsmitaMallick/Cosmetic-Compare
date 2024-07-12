# Cosmetics Recommendation System

This project is a content-based recommendation system for cosmetics, using their chemical components to suggest similar products. The data is processed and visualized using a Jupyter notebook.

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [File Structure](#file-structure)
5. [Contributing](#contributing)

## Features
- Preprocesses cosmetic ingredient data.
- Tokenizes ingredients and creates a document-term matrix.
- Reduces dimensions using t-SNE.
- Visualizes the similarity of cosmetic products with Bokeh.
- Interactive plot with hover tooltips showing product details.

## Installation
### Prerequisites
- Python 3.x
- Jupyter
- Bokeh
- scikit-learn
- Pandas
- NumPy

### Clone the Repository
```bash
git clone https://github.com/yourusername/cosmetics-recommendation-system.git
cd cosmetics-recommendation-system
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook cosmetics-comparison.ipynb
```

2. Run the cells in the notebook to preprocess the data, train the model, and visualize the results.

## File Structure
```
cosmetics-recommendation-system/
│
├── cosmetics-comparison.ipynb  # Jupyter notebook for data analysis and visualization
├── cosmetics.csv               # Cosmetic ingredient data
└── requirements.txt            # Project dependencies
```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.
