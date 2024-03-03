# Python-Population-Project
This Python code provides a user-friendly tool to explore US population data stored in the `USPopulation1.txt` file. It offers various functionalities through a menu interface.



### Functionality:
To be used as an interactive tool for analyzing US population data from 1960 to 2022. It reads the data from a text file (`USPopulation1.txt`) and presents a menu-driven interface for users to explore the information in various ways:

Option 1: Display Population for Year: Users can enter a specific year between 1960 and 2022 to retrieve the corresponding population value.
Option 2: Display Population Change Between Years: This option allows users to input two years within the range and calculates the absolute difference in population between them.
Option 3: Display Average Population for Range: Users can specify a year range to calculate the average population for those years.
Option 4: Line Graph of Population: This functionality generates a line graph illustrating the population trend over a user-defined year range (1960-2022). It requires the matplotlib library to be installed.
Option 5: Scatter Plot of Population: Similar to the line graph, users can select a year range to visualize the population distribution between those years using a scatter plot (also using matplotlib).
Option 6: Exit: Users can terminate the program at any point.



### Error Handling:
The code incorporates error handling to validate user input for years. If a user enters a value outside the 1960-2022 range, an error message is displayed.

