
---

# Netflix Power BI Project

## Project Overview

The **Netflix Power BI Project** is an interactive dashboard designed to analyze Netflix’s movie and TV show catalog. Using data from two primary tables (**Netflix** and **Category Mapping**), the project provides valuable insights into various factors like film categories, ratings, duration, directors, and more. This dashboard allows users to explore detailed information about specific films and visualize trends across Netflix’s content library.

### Data Overview

1. **Netflix Table**:
   - **show_id**: Unique identifier for each show.
   - **type**: Type of content (Movie or TV Show).
   - **film_name**: Name of the movie or TV show.
   - **director**: The director of the film or show.
   - **country**: The country of production.
   - **add_date**: Date the show was added to Netflix.
   - **release_date**: Release date of the film.
   - **rating**: Rating of the film (e.g., PG, R).
   - **duration**: Total duration of the movie or TV show in minutes.
   - **category**: The primary category or genre (e.g., Drama, Comedy).
   - **duration_in_min**: Duration of the show in minutes.
   - **first_category**: The first assigned category for the film.

2. **Category Mapping Table**:
   - **show_id**: Unique identifier for each show (maps to Netflix table).
   - **listin_id**: Identifier for the list/category the show belongs to.

---

## Dashboard Overview

The Power BI dashboard is divided into **two main pages**: **Overview** and **Account**. Below are the details for each page:

### Page 1: Overview

This page provides a general overview of Netflix's catalog and key trends. Key components include:

- **Slicer (Film Name)**: 
   - Located at the top-right corner. Users can select a film or TV show, and the dashboard will display detailed information about it:
     - **Duration in Minutes**
     - **Release Year**
     - **Type** (Movie or TV Show)
     - **Category**
     - **Director**
     - **Country**
     - **Date Added**
     - **Show ID**

- **Map Visualization (Country)**: 
   - A map that visualizes the countries where the films were produced. This allows users to see the global distribution of Netflix's content.

- **Bar Chart (Film Count by Rating and Type)**:
   - A bar chart displaying the count of films based on their **Rating** (e.g., PG, R) and **Type** (Movie/TV Show). This chart provides an overview of how films are categorized by type and rating.

---

### Page 2: Account

This page provides more detailed insights into the content trends on Netflix. Key components include:

- **Pie Chart (Percentage of Films by Type)**:
   - Shows the percentage distribution of films by type (Movie or TV Show). This allows users to quickly understand the balance between movie and TV show content on Netflix.

- **Column Chart (Top 5 Directors by Number of Films)**:
   - Displays the top 5 directors with the highest number of films or shows on Netflix. It helps identify the most prolific directors on the platform.

- **Max Duration in Minutes by Film Name**:
   - Highlights the films with the longest durations in minutes. This helps users discover long-form content available on Netflix.

- **Stacked Bar Chart (Ratings by Film Name)**:
   - Displays ratings for each film in a stacked bar chart format. This chart helps to visualize the rating distribution across different movies and TV shows.

- **Area Chart (Total Movie and TV Show Release Year)**:
   - An area chart showing the release years of movies and TV shows. This chart provides an overview of when content was added to Netflix and reveals trends in release years.

- **Cards (General Metrics)**:
   - Displays key statistics like:
     - Total number of films.
     - Number of films by category.
     - Number of films by type.
     - Average duration of films.
     - Average ratings.

- **Slicers (Filters for Category, Film, and Year)**:
   - These filters allow users to narrow down the data and focus on specific categories, films, or years of interest.

---

## How to Use This Dashboard

1. **Filter by Film Name**:  
   Use the **Film Name** slicer to select a specific film or TV show. Detailed information about the selected film (e.g., type, duration, release year) will be displayed.

2. **Explore Trends**:  
   Interact with various charts (bar, pie, area, etc.) to analyze global trends in Netflix's catalog, such as film distribution by rating, country, and type.

3. **Use Slicers**:  
   Filter the data by **Category**, **Film**, or **Year** to explore different segments of Netflix's content library.

4. **Hover and Click for Details**:  
   Hover over different elements in the charts for additional information, and click on items to drill down further into specific data points.

---

## Technologies Used

- **Power BI**: All visualizations and interactive components were created using Power BI.
- **DAX (Data Analysis Expressions)**: Custom calculations and metrics were generated using DAX.
- **Power Query**: Data transformation and cleaning were carried out using Power Query to ensure data quality.

---

## Data Sources

This project uses publicly available data about Netflix's films and TV shows, including information on film categories, ratings, directors, countries, and more. The **Category Mapping** table helps link films to their respective categories.

---

## License

This project is open-source. Feel free to explore, modify, and share the dashboard as needed. Please provide attribution if you use or modify any part of the project.

---

## Contact

For any questions, feedback, or further inquiries, feel free to contact me via GitHub or email.

---

Bu **README** sənədi, **Netflix Power BI** layihənizin əsas funksiyalarını və vizuallaşdırmalarını aydın şəkildə izah edir. Hər hansı bir əlavə dəyişiklik və ya əlavələr etmək istəyirsinizsə, mənə bildirə bilərsiniz!
