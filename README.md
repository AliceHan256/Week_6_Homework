# How to run and use this dashboard

1. Open your computer's terminal for Mac or git bash for Windows system.
2. In your terminal, open your jupyter notebook by typing "jupyter lab".
3. Navigate to the folder which contains the file called "Week_6_Homework".
4. Open the filed called "dashboard.ipynb".
5. From the tabs shown on the top of the Jupyter Notebook, select "Run" then "Ren All Cells". This will run all the cells to generate all tables and visualizations.
6. To generate visualizations on your local serval, firstly you need to create a file called "run.sh", then add the following code in it: panel serve dashboard.ipynb --log-level debug --show
7. After that, open a terminal from the launcher in your Jupyter Notebook. Navigate to the current file, Week_6_Homework. Copy the code contained in the folder "run.sh" and run it. This will make the desired visualizations on your local server. It will contain five tabs: Welcome, yearly Market Analysis, Neighborhood Analysis, Parallel Plots Analysis and Sunburst Plot Analysis. 
8. You can explore in details on each page by clicking the tabs shown on the top of the screen.
