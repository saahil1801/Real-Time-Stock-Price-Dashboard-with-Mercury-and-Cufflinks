# Real-Time-Stock-Price-Dashboard-with-Mercury-and-Cufflinks


![image](https://github.com/saahil1801/Real-Time-Stock-Price-Dashboard-with-Mercury-and-Cufflinks/assets/84408557/0200803d-8515-4aa6-a911-8fcddbd28092)


![image](https://github.com/saahil1801/Real-Time-Stock-Price-Dashboard-with-Mercury-and-Cufflinks/assets/84408557/1207d638-3b87-45a0-aae8-30a9e8bfe8d0)


![image](https://github.com/saahil1801/Real-Time-Stock-Price-Dashboard-with-Mercury-and-Cufflinks/assets/84408557/8f84dd23-4f5d-4b87-983d-d3a6abfa960f)




This repository contains a Jupyter Notebook that guides you through the process of creating an interactive stock price dashboard using Python. The dashboard allows users to select a stock ticker symbol, customize the time period for data analysis, and visualize stock performance. The dashboard is built using various libraries and tools, and it can be deployed as a web application using the Mercury framework.

## Step 1: Setup
Before you begin, make sure to install the required libraries. You can do this by running the following command:

### !pip install yfinance ipyvuetify cufflinks mercury

## Step 2: Configure the Mercury App
In this step, we set up the Mercury app, which will serve as the platform for our stock price dashboard. The app is configured with a title and description, and input widgets are created to allow users to interact with the app.

You can select your preferred stock symbol and customize the time period for data analysis. The default selection showcases semiconductor stocks, but you can easily replace them with your preferred stock symbols.

## Step 3: Visualize Stock Performance
This step focuses on downloading and visualizing stock data for the selected stock. The data is downloaded using the yfinance library, and interactive plots are created with cufflinks. Here's what you can do in this step:

Download and visualize stock data for a selected stock (e.g., NVIDIA Corporation).
Create interactive line plots, filled area plots, and plots with best-fit lines.
Perform quantitative analysis using the QuantFig class from cufflinks and add technical indicators and volume data to gain deeper insights.
Comparing Semiconductor Companies
Next, you can download and compare historical stock data for multiple semiconductor companies, such as NVIDIA, Intel, AMD, TSMC, and Micron. You'll create interactive line plots to compare their adjusted close prices.

Calculating Cumulative Returns
In the final step, you'll calculate and visualize cumulative returns for a weighted portfolio of semiconductor stocks. You can define your own portfolio weights based on your investment strategy. Daily returns are calculated, and cumulative returns are displayed with an interactive plot.

## Step 4: Deploy the Notebook as a Web App Using Mercury
The last phase involves deploying your stock price dashboard as an interactive web application using the Mercury framework. Follow these steps to prepare your notebook for deployment:

Download the notebook.
Remove code or Markdown cells that you don't want to display on the web.
Download the requirements.txt file to specify dependencies.

After setting up your Mercury account, create your first site, upload your notebook and requirements.txt, and open the app to explore and interact with your dashboard.

Feel free to replace the stock symbols and customize the dashboard to align with your specific area of interest and analysis goals. Enjoy exploring and visualizing stock data with this interactive dashboard!
