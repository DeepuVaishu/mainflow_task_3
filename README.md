# YouTube Trending Data Analysis 📊

## 📑 Overview
This project performs an exploratory data analysis (EDA) on the **YouTube Trending Videos** dataset, focusing on understanding user engagement metrics and trends. Using Python libraries such as Pandas, Matplotlib, and Seaborn, the project visualizes various aspects of the data to uncover insights about popular content on YouTube.

## 📋 Table of Contents
- [Dataset Information](#dataset-information)
- [Key Analysis & Visualizations](#key-analysis--visualizations)
- [Usage](#usage)
- [Results & Insights](#results--insights)
- [Contributing](#contributing)
  
## 📂 Dataset Information
- **Source**: The dataset contains data on trending YouTube videos in India.
- **Features**:
  - `video_id`, `title`, `channel_title`, `category_id`
  - `views`, `likes`, `dislikes`, `comment_count`
  - `trending_date`, `publish_time`
- **Objective**: To explore engagement patterns and identify trends in popular YouTube content.

## 📊 Key Analysis & Visualizations
- **Bar Chart**: Top 10 YouTube channels by total views.
- **Line Chart**: Trends of likes, dislikes, and comments for the most viewed video.
- **Scatter Plot**: Relationship between views and likes.
- **Histograms**: Distribution of views, likes, and dislikes.
- **Box Plot**: Distribution analysis using quantiles for views, likes, and dislikes.

## 🚀 Usage
Run the Jupyter Notebook for detailed analysis:
```bash
jupyter notebook notebooks/task.ipynb
```

## 📝 Results & Insights
- **Top Channels**: Identified the most popular channels based on total views.
- **Engagement Trends**: Higher views generally correlate with increased likes and comments.
- **Category Insights**: Some video categories receive significantly higher average views than others.
- **Quantile Analysis**: Revealed the spread and outliers in metrics like views, likes, and dislikes.

## 🤝 Contributing
Feel free to contribute by submitting a pull request. For significant changes, please open an issue first to discuss what you would like to change.
