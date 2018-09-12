
## Data Visualisation : Comparisons with Bar Charts 

Create bar graphs for given exercises. 

## Exercise 1

Make a vertical bar graph for the following set of data:

> ### Jim's Video Library contains 40 crime/mystery, 30 science fiction, 10 drama, 50 comedy, 25 action and 5 documentary movies.

* Use a different style for the bar graph
* Label the axes and Give a title
* Set the Genres at x-ticks


```python
# import the required libraries

# Set x, y and labels

# Create a new figure object

# Create an axes 

# Plot vertical bars of fixed width by passing x and y values to .bar() function 

# Give a title to the bar graph

# Output the final plot

```


```python

```


![png](index_files/index_2_0.png)


## Exercise 2

Let's extend above example for a lmuch larger movie collection. Number of movies and genre labels have been provided as python lists below. Draw vertical vs horizontal bar plots as subplots and comment of suitability of both with an increased number of genres. 

* Apply all formatting to both subplots as above. 


```python
labels = ['Adventure', 'Action', 'Drama', 'Comedy', 'Thriller/Suspense', 'Horror', 'Romantic Comedy', 'Musical',
         'Documentary', 'Black Comedy', 'Western', 'Concert/Performance', 'Multiple Genres', 'Reality']
quantity = [
    941,
    854,
    4595,
    2125,
    942,
    509,
    548,
    149,
    1952,
    161,
    64,
    61,
    35,
    5
]
```


```python
# Create x and y 

# Create a figure with two columns 

# Set titles for both axes

# Show the final plot
```


```python

```


![png](index_files/index_6_0.png)



```python
# We can see that horizontal bar graph is much easier to view, compare and interpret with labels clearly readable. 
# We can, however, apply rotation to labels of vertical bar graph to make it more readable 
```

##  Exercise 3

Following data presents a subset of happiness index for males and females for some of the major cities in world. Draw a grouped bar chart to show both gendres for all the cities. Label the plot, give it a title and briefly 
comment on the output.

    city=['Delhi','Beijing','Washington','Tokyo','Moscow']
    happiness_male=[60,40,70,65,85]
    happiness_female=[30,60,70,55,75]


```python
# Prepare the data

# Create labels for genders

# Set the label position from city list

# Plot the bars

# Label the ticks and axes

# Show the title and the legend
```


```python

```


![png](index_files/index_10_0.png)



```python
# Stuents may comment on the fact that delhi(India) has much less happy females than males. 
# Washington(USA) has equally happy males and females
# In Moscow(Russia) , females are much happier than males

# All to do  socio-economic factors in these countries
```

## Exercise 4

Create a stacked bar chart with following data. This represents number of hours spent on each day for studying number of data science skills for 4 days in a week.
    
    Saturday = [5, 3, 4, 7, 2]
    Monday = [3, 4, 4, 2, 5]
    Tuesday = [2, 5, 6, 2, 1]
    Thursday= [3, 0, 4, 4, 3]
    skills = visualisation, pandas, regression, decision trees, KNN clustering
    
The scatter plot should highlight each skill on the x-axis and how much time is being spent on it for the four days shown above.


```python
# Prepare the data 

# Set the index for number of classes

# Create a single figure and axes object

#Create the rectangles while using bottom argument 

# Set the labels and titles
```


```python

```


![png](index_files/index_14_0.png)

