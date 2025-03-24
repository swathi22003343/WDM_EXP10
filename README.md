### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from other programs or used as an API. Individual functions can be called from the command line. RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![Screenshot (664)](https://github.com/user-attachments/assets/21df9c51-da55-418e-931f-65979324d28b)

![Screenshot (663)](https://github.com/user-attachments/assets/6790ee54-5a16-4a40-86d8-ac6db6fb5217)


### Result:
Thus, sentimental analysis for the given data using Rapidminer is done successfully.
