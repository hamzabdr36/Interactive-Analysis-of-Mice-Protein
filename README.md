<h1>Interactive Analysis of Mice Protein Expressions</h1>

<h2>Description</h2>
In this project, I conducted an in-depth exploratory data analysis and created an interactive visualization dashboard using Python, Dash framework, and various data analysis libraries. The dataset used for this project is the Mice Protein Expression Dataset, which contains expression levels of 77 proteins measured in the cerebral cortex of different classes of mice. The goal was to analyze the dataset and create an interactive dashboard that provides insights into the relationships between protein expressions, classes, and various dimensionality reduction techniques. I achieved it by cleaning and preprocessing the dataset, creating insightful visualizations, and developing an interactive dashboard using Python, Dash framework, and various data analysis libraries.
<br />


<h2>Project Features and Steps</h2>

<b>Data Cleaning and Preprocessing: </b> 

-Loaded the dataset using pandas.

-Handled missing values by filling them with mean values.

-Extracted subgroups "t-CS-s" and "c-CS-s" from the dataset.

<b>Parallel Coordinates Plot: </b>

-Utilized the Plotly library to create a parallel coordinates plot.

-Plotted the protein expressions (pPKCG N, pP70S6 N, pS6 N, pGSK3B N, ARC N) for the two classes with distinct colors.

-Annotated each axis with the corresponding protein name.

<b>Dimensionality Reduction Techniques: </b>

-Applied PCA, ISOMAP, and t-SNE as dimensionality reduction techniques to the dataset.

-Visualized the reduced data using scatter plots for each technique.

-Created an interactive interface using the Dash framework.

<b>Interactive Dashboard: </b>

-Built a Dash application with a user-friendly interface.

-Included a radio component for users to select between PCA, ISOMAP, and t-SNE.

![radio button](https://github.com/MadniAbdulWahab/InteractiveAnalysisofMiceProteinExpressions/assets/105889425/9015e081-f98c-4f12-9dfa-d1377295791f)


-Displayed a scatter plot based on the selected dimensionality reduction technique.

-Added dropdown menus to select the protein expressions for x and y axes.

![dropdown menu](https://github.com/MadniAbdulWahab/InteractiveAnalysisofMiceProteinExpressions/assets/105889425/78d4570d-3448-4001-87f4-8ed75e35f562)


<b>Dynamic Scatter Plots: </b>

-Implemented the ability to add multiple scatter plots.

-Included an "Add" button that replicates the scatter plot with the current axis settings.

![add button](https://github.com/MadniAbdulWahab/InteractiveAnalysisofMiceProteinExpressions/assets/105889425/2b02df7a-184e-4f35-86b4-a5e3a6c1aabf)


-Accommodated the addition of multiple scatter plots below the existing ones.


Here is how it looks like after adding three scatterplots with different proteins:

![mice protein project](https://github.com/MadniAbdulWahab/InteractiveAnalysisofMiceProteinExpressions/assets/105889425/105f8a52-3c9b-4dd3-9885-2260905ee8c5)

The three scatterplots in the second row od the image were added by the user through clicking on the add button. User can add many number of scatterplots according to his need.

<h2>Technologies and Libraries Used:</h2>

I used the following languages and libraries during the development of this project: 

- <b>Python: </b>  The primary programming language for data analysis and visualization.

- <b>Pandas: </b> Data manipulation and analysis library.

- <b>Plotly: </b>  Interactive visualization library.

- <b>Dash: </b> Web framework for building interactive web applications.

- <b>Scikit-learn: </b> Machine learning library for dimensionality reduction techniques.

<h2>Code Summary: </h2>

The provided code showcases the implementation of the above features. It initializes a Dash application, sets up the layout with interactive components, and defines callback functions to update the visualizations based on user inputs. The code also handles the addition of scatter plots and dynamic updates to the figure container.

Feel free to explore the dataset, analyze protein expressions, and interact with the dynamic visualizations to gain insights into the relationships between different classes and proteins in mice.

<b>Note:</b>

Please ensure that you have the necessary dependencies installed before running the application.

Thank you for visiting my project! If you have any inquiries or feedback, please don't hesitate to reach out.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
