# Bivariate plotting with pandas
## Visually capture the patterns and correlations in any dataset.

### Scatter Plot	
`df.plot.scatter()`	
Good for interval and some nominal categorical data.	

### Hex Plot	
`df.plot.hexbin()`		
Good for interval and some nominal categorical data.	

### Stacked Bar Chart	
`df.plot.bar(stacked=True)`
Good for nominal and ordinal categorical data.	

### Bivariate Line Chart
`df.plot.line()`
Good for ordinal categorical and interval data.

# Faceting with seaborn

## Facet Grid	
`sns.FacetGrid()`	
Good for data with at least two categorical variables.		

## Pair Plot	
`sns.pairplot()`
Good for exploring most kinds of data.	

# Multivariate plotting

### Multivariate Scatter Plot    
`df.plot.scatter()`   
    
### Grouped Box Plot    
`df.plot.box()`    

### Heatmap    
`sns.heatmap`    
    
### Parallel Coordinates    
`pd.plotting.parallel_coordinates` 

# Plotly
### Scatter Plot
`go.Scatter()`

### Choropleth
`go.Choropleth()`

### Heatmap
`go.Heatmap()`

### Surface Plot
`go.Surface()`

