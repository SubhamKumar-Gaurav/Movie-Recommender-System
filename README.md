# Movie Recommender System

Welcome to the Movie Recommender System! This project uses machine learning and natural language processing techniques to recommend movies based on user preferences. Explore, analyze, and find your next favorite movie easily with this system.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Libraries Required](#libraries-required)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## Introduction
This project aims to provide users with personalized movie recommendations. It leverages content-based filtering using movie metadata such as genres, cast, crew, and descriptions. The application is built using Python and Streamlit for an interactive user interface.

---

## Features
- Search for movies by title.
- Get similar movie recommendations based on:
  - Genre
  - Cast
  - Crew
  - Description
- Simple and intuitive user interface.

---

## Technologies Used
- **Python**: The core programming language.
- **Streamlit**: For building the web interface.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For implementing the recommendation algorithm.
- **NLTK**: For text preprocessing.

---

## Libraries Required
The following libraries are required to run this project:
- streamlit
- pandas
- numpy
- scikit-learn
- nltk
- ast
- json
- requests
- re

Install these libraries using the `requirements.txt` file or manually with pip.

---

## Installation

### Prerequisites
- Python 3.7 or higher installed.
- Libraries listed in `requirements.txt`.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/SubhamKumar-Gaurav/Movie-Recommender-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Movie-Recommender-System
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## Usage
1. Launch the application using the above command.
2. Enter a movie title in the search bar.
3. View recommended movies based on your selection.

---

## Dataset
The dataset used in this project contains metadata about movies such as title, genres, cast, crew, and descriptions. The dataset is sourced from [Kaggle TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and preprocessed for effective recommendations.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Inspired by various movie recommendation systems.
- Thanks to open-source libraries and datasets for making this project possible.

---

## Contact
For any questions or feedback, please reach out to:

Subham Kumar Gaurav: subhamgaurav2001@gmail.com  
GitHub: [SubhamKumar-Gaurav](https://github.com/SubhamKumar-Gaurav)

---
