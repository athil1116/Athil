🎬 Movie Dataset Analysis using Pandas (Google Colab)
This project involves exploratory data analysis on a movie dataset using Python and Pandas in Google Colab. The dataset contains information about various films such as ID, title, release year, rating, and duration. The goal was to perform data cleaning, transformation, and various insightful queries.

📁 Dataset Structure
The dataset used contains the following columns:

Id — Unique identifier for each film

Movie — Name of the film

Year — Year the film was released

Rating — User rating of the film

Duration — Duration of the film (in minutes/seconds depending on dataset)

✅ Tasks Performed
Load and Inspect Dataset
Set the column names: Id, Movie, Year, Rating, Duration.

Shape of Dataset
Display the number of rows and columns.

Top 5 Films by Duration
Display the five films with the highest duration.

Remove Duplicates
Check and remove duplicates (if any), then reset the index accordingly.

Rename Column
Rename the column Movie to Film.

View Specific Range
Display all observations from index 100 to 200.

Longest Film
Display the name and year of the film with the maximum duration.

Yearly Film Count
Display the number of films released in each year.

Top Duration Film (1986–1996)
Find the film with the highest duration released between 1986 and 1996.

High Duration & Rating
Find films with duration > 7000 and rating > 3.5.

Lowest Rated Films
Display 5 films with the lowest rating, sorted in descending order.

Top Rated Film of 1996
Print the name of the highest-rated film released in 1996.

🛠️ Tools Used
Python 3

Pandas

Google Colab

📌 Notes
Make sure your dataset is clean and correctly formatted before running these operations.

The column names should exactly match the names used in the script.

🚀 How to Run
Upload the dataset to Google Colab.

Import the dataset using pd.read_csv().

Follow each step using the corresponding Pandas operations.
