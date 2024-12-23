
# Music Recommendation System

## Project Overview
This project focuses on building a content-based music recommendation system using data from the 2000s to 2010s. By analyzing track audio features and metadata, the system predicts user preferences and recommends songs. The dataset is sourced from Spotify's Web API and includes hit tracks.

## Dataset
The dataset used for this project is [The Spotify Hit Predictor Dataset](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset). It contains a rich collection of songs with detailed audio features such as tempo, danceability, energy, and more.

## Features
- **Content-Based Recommendation**: Uses audio features and metadata to recommend similar tracks.
- **Dimensionality Reduction**: Employs Principal Component Analysis (PCA) to simplify and visualize data.
- **Similarity Metrics**: Utilizes cosine similarity to find and recommend tracks.
- **Era-Specific Focus**: Concentrates on songs from the 2000s to 2010s for targeted recommendations.

## Tools and Libraries
The following tools and libraries are used in this project:
- **Python Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `sklearn` for preprocessing and modeling (e.g., PCA, cosine similarity).
  - `matplotlib` for data visualization.
  

## How It Works
1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Scale features using MinMaxScaler or StandardScaler.
   - Encode categorical variables.

2. **Feature Analysis**:
   - Apply PCA for dimensionality reduction.
   - Analyze the distribution and correlation of features like tempo, energy, and danceability.

3. **Recommendation System**:
   - Calculate cosine similarity between songs.
   - Recommend tracks based on user-selected criteria or seed tracks.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AimanMadan/CS471_RecommendationSystems.git
   cd CS471_RecommendationSystems
   ```
2. Install dependencies:

## Usage
1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook RecommendationSystem.ipynb
   ```
2. Explore the dataset and visualize features.
3. Input your favorite tracks to get personalized recommendations.

## Results
The system successfully provides relevant song recommendations by analyzing user-selected tracks and identifying similar songs based on audio features.

## Future Improvements
- Integrate a user interface for easier interaction.
- Include additional data from newer time periods for expanded recommendations.
- Explore hybrid recommendation approaches combining content-based and collaborative filtering.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to [Kaggle](https://www.kaggle.com/) and the creator of [The Spotify Hit Predictor Dataset](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset) for providing the dataset.


