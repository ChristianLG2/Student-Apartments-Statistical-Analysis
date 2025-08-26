# R Statistical Analysis of Student Apartments in Rexburg, Idaho

Video Link: https://youtu.be/cWNsnR5KE6E 

### Overview

This project provides a detailed statistical analysis and visualization of apartment rental data for students in Rexburg, Idaho. The data includes various characteristics of 122 apartments, with the objective to explore rent prices, deposits, apartment capacities, and other amenities that might influence students' housing choices.

The analysis was conducted in R using an R Markdown file, and the results were visualized using several R packages to provide a comprehensive view of the available apartment options.

### Project Structure

R Data Analysis.Rmd: The main file containing the code for data wrangling, statistical analysis, and visualization.

Rent.csv: The dataset containing information on 122 apartments, including attributes such as:
Apartment Name
Gender Accommodation (Male/Female/Co-ed)
Address and Contact Details
Rent Price, Deposit, and Utility Deposit
Number of Rooms and Floor Plans
Proximity to Campus (Distance and Walking Time)
Availability of Parking and Other Amenities
Data Wrangling and Preparation
The dataset was first cleaned and prepared using the tidyverse library. A new column, TotalPrice, was created to capture the sum of rent, deposit, and utility deposit for each apartment, giving a clearer view of the total cost associated with each listing.

### Key Statistical Insights

Pricing Range:

Rent prices range from $850 to $1,585, with a median price of $1,120.
Private room rents range from $850 to $1,669.
Deposits are relatively low, with a maximum of $200, making housing more accessible for students.
Utility deposits are often $0, indicating minimal upfront utility costs.
Apartment Characteristics:

The apartments vary widely in terms of layout, with between 1 and 36 different floor plans per apartment.
The dataset also includes descriptive information about each apartment, such as names, addresses, and whether parking is available.

### Visualizations

The analysis leverages ggplot2 for visualizing key insights from the dataset, including price distributions, apartment capacity comparisons, and proximity to campus.

### Geographic Analysis

Using the leaflet library, a geographic visualization of the apartments was created, providing a map-based view of how the apartment locations are distributed in relation to the campus. This helps students make informed decisions based on both cost and convenience.

### Results

The HTML output generated from this analysis includes:

Summary statistics and key insights about apartment prices, deposits, and amenities.
Visualizations of the distribution of rent prices.
A geographic map showing the apartment locations and their distance from campus.
Recommendations based on the data to help students choose the best housing option according to their budget and preferences.