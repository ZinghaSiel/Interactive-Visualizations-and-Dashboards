# Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria_by_filterforgedotcom.jpg)

This exercise involves building an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/) using Plotly.js to build interactive charts for the dashboard.

The following steps were completed in order to obtain our dashboard;
    ![Dashboard Page](Images/dashboard_part1.png)
    ![Dashboard Page](Images/dashboard_part2.png)

    * Creating a PIE chart that uses data from samples route (`/samples/<sample>`) to display the top 10 samples.
    ![PIE Chart](Images/pie_chart.png)
    
    * Creating a Bubble Chart that uses data from samples route (`/samples/<sample>`) to display each sample.
    ![Bubble Chart](Images/bubble_chart.png)
    
    * Displaying the sample metadata from the route `/metadata/<sample>`
    
    * Updating all of the plots any time that a new sample is selected.

    * The next step will be to deploy our app to Heroku using the squlite file for the database and adapting the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the Weekly Washing Frequency obtained from the route `/wfreq/<sample>`
    ![Weekly Washing Frequency Gauge](Images/gauge.png)
    
    *The final step with be to use Flask API starter code to serve the data needed for our plots and testing our routes by visiting each one in the browser.
