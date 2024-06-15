# Data Analysis on Mobile Applications Dataset

## Project Overview

This project aims to perform a comprehensive data analysis on a dataset of mobile applications. The primary objective is to uncover insights and trends related to app categories, user ratings, app sizes, pricing, and more. The analysis will help in understanding the mobile app market, user preferences, and factors that contribute to app success.

## Dataset Description

The dataset used in this project contains information about various mobile applications. It includes details such as:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

### Source

The dataset can be downloaded from the below link.

Dataset: https://drive.google.com/file/d/1lGIrooUAGjgNSSfD2C9VrS4Oy3paLTdO/view?usp=sharing

## Analysis Performed

The following analyses were performed on the dataset:

1. **Category Distribution**: Analysis of the distribution of apps across different categories.
2. **Rating Analysis**: Examination of user ratings and their distribution.
3. **Review Analysis**: Analysis of the number of reviews and their relationship with app ratings.
4. **Size and Installs**: Insights into the size of apps and their number of installs.
5. **Price Analysis**: Comparison of free vs. paid apps and their pricing strategies.
6. **Content Rating**: Analysis of content ratings and their distribution across different app categories.
7. **Genres**: Examination of app genres and their popularity.
8. **Updates and Versions**: Analysis of app updates and the versions of Android they support.

## Tools and Libraries

The project utilizes the following tools and libraries:

- **Python**: Programming language used for data analysis.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical computations.
- **Matplotlib**: Plotting library for data visualization.
- **Seaborn**: Statistical data visualization library based on Matplotlib.
- **Jupyter Notebook**: Interactive environment for running Python code and visualizing results.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/Data-Analysis-on-Mobile-Applications-Dataset.git
    cd Data-Analysis-on-Mobile-Applications-Dataset
    ```

2. **Install Dependencies**:
    Ensure you have Python installed. Then install the required libraries using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3. **Download the Dataset**:
    Download the dataset from [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps) and place it in the `data` directory of the project.

4. **Run the Jupyter Notebook**:
    Start the Jupyter Notebook server and open the analysis notebook:
    ```sh
    jupyter notebook
    ```
    Open `mobile_applications_data_analysis.ipynb` to explore the analysis.

## Results

The results of the analysis are presented in the Jupyter Notebook and include various visualizations and insights derived from the data. Here are some highlights:

- **Category Distribution**: The dataset contains a large number of apps in the 'Family' and 'Game' categories.
- **Rating Analysis**: Most apps have ratings between 4.0 and 4.5, indicating generally positive user feedback.
- **Review Analysis**: Apps with more reviews tend to have higher ratings, suggesting that popular apps are well-received.
- **Size and Installs**: Larger apps are generally installed more frequently, possibly due to higher functionality or features.
- **Price Analysis**: The majority of apps are free, with paid apps having varied pricing strategies.
- **Content Rating**: 'Everyone' is the most common content rating, indicating that many apps are suitable for all age groups.
- **Genres**: Action, Education, and Puzzle are among the popular genres.
- **Updates and Versions**: Frequent updates are common among successful apps, ensuring compatibility with the latest Android versions.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
