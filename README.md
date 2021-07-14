## airline_performance_dashboard

Practicing Plotly/Dash on airline data.

##### Python packages used : 
1. Pandas
2. Plotly ( express and graph_objects )
3. Dash ( dash_html_components, dash_core_components, callback function for interactive functionaluty)

##### Methods and technics, related to data analysis, used:
1. pandas : pd.read_csv(), df.groupby(), df.reset_index()
2. Dash : dash.Dash(),  app.layout() , @app.callback, app.run_server()
3. Plotly: px.bar(), px.line(), px.pie(), px.chloropleth(), px.treemap(),

#### Structure of analysis:
1. Load data from CSV
2. Create an app and its layout with dash_html_components
3. Create function for callback which built graphs with 2 different options ( 2 dropdown options) 
4. Create callback decorator funtion for interaction


![Picture](https://github.com/Folongton/airline_performance_dashboard/blob/master/dash%20pics%20for%20git/1.png)
