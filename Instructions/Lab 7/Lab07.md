# Lab 07- Create a Notebook using Github Copilot chat and provide answers based on Test data

**INTRODUCTION**

This dataset tested_worldwide.csv is origin from Kaggle. This dataset,
which has the number of tests conducted over time, is important to help
make sense of daily reported cases and understand how COVID-19 is truly
spreading in each country.

**INSTRUCTIONS**

1.  Open Visual Studio Code from the Windows Start menu and open the
    folder navigating to C:\Labfiles\CopilotHackathon

> <img src="./media/image1.png" style="width:6.49167in;height:3.325in"
> alt="A screenshot of a computer Description automatically generated" />

2.  Click on **Yes,I Trust the Author** button.

<img src="./media/image2.png" style="width:6.49167in;height:3.7in" />

3.  Click on **Copilot** icon on right side down corner and select
    **Github Copilot Chat.**

<img src="./media/image3.png" style="width:6.49167in;height:3.775in" />

4.  Type your prompt create a new notebook in a project. Use command
    /newnotebook and name it as "COVID19 Worldwide Testing Data"

> <img src="./media/image4.png"
> style="width:6.49167in;height:6.03333in" />

5.  You can see the Copilot instructions helping you with instructions.
    Follow the steps and create the notebook.

- Open the command palette by pressing **Ctrl+Shift+P.**

- Type Jupyter: Create New Blank Notebook and press Enter.

> <img src="./media/image5.png"
> style="width:6.49167in;height:5.30833in" />

- A new notebook will be created. Save it with the name
  COVID19WorldwideTesting Data.ipynb.You can also ask Copilot how to
  save a new notebook.

> <img src="./media/image6.png" style="width:6.49167in;height:4.125in" />

- Go to the destination folder – **excercisefiles-? dataengineer** enter
  the COVID19WorldwideTesting Data.ipynb and save the file.

> <img src="./media/image7.png" style="width:6.49167in;height:3.95in" />

6.  You should see the file was created under **dataengineer** folder.

<img src="./media/image8.png" style="width:6.5in;height:2.64306in"
alt="A screenshot of a computer Description automatically generated" />

2\. Use Copilot and Copilot Chat to develop the exercise and support
your learning.

**EXERCISE**

Our analysis tries to provide an answer to this question: **Which
countries have reported the highest number of positive cases in relation
to the number of tests conducted?**

**Task 1: Import Required Libraries**

1.  Click on Notebook kernel and type \#*Import Required
    Libraries.Including Pandas and* press Enter

<img src="./media/image9.png" style="width:6.5in;height:2.74167in"
alt="A screenshot of a computer Description automatically generated" />

2.  Press tab. It will take you to the end of the line. Press Enter and
    again press Tab to add all libraries.

<img src="./media/image10.png" style="width:6.5in;height:3.58194in"
alt="A screenshot of a computer Description automatically generated" />

\# Import the necessary libraries, including pandas.

*\# Import Required Libraries*

*\# Here we are importing the necessary libraries for our task*

**import** pandas **as** pd *\# pandas is a software library written for
the Python programming language for data manipulation and analysis.*

<img src="./media/image11.png" style="width:6.5in;height:2.37847in"
alt="A screenshot of a computer Description automatically generated" />

# **Task 2 : Load the Dataset**

1.  Use pandas to load the 'tested_worldwide.csv' file from the root
    level.

2.  Ask Github Copilot to help you on how to load data. Enter Use pandas
    to load the 'tested_worldwide.csv' file from the root level

<img src="./media/image12.png"
style="width:5.91667in;height:8.40833in" />

3.  Enter the below code in a Notebook and run it.It will ask you to
    select **Python Environment**. Select it.

<img src="./media/image13.png" style="width:6.49167in;height:4.625in" />

7.  Select the recommended environment. script runs and provides the
    results.

<img src="./media/image14.png" style="width:6.49167in;height:3.725in" />

<img src="./media/image15.png" style="width:6.5in;height:5.28472in"
alt="A screenshot of a computer Description automatically generated" />

### Task 3 : Understanding the Data

1.  Use the head() function to display the first 5 rows of the dataset

2.  Ask your Github Copilot to help you with the code to display first 5
    rows of the dataset. display first 5 rows of the dataset

> <img src="./media/image16.png"
> style="width:6.49167in;height:7.01667in" />

3.  Click on **+ code** to open new kerner. Just enter \# display first
    5 rows of dataset. It will automatically predict your question. Just
    press tag and then press Enter.

> <img src="./media/image17.png" style="width:6.5in;height:4.69653in"
> alt="Screens screenshot of a computer screen Description automatically generated" />

8.  **Coiplot** predicts the command you are looking for, so press the
    tab to accept the code. You always have the option to edit/write
    your own code.

<img src="./media/image18.png" style="width:6.5in;height:4.7in" />

9.  Press the tab and accept the code. Run the kernel.

<img src="./media/image19.png"
style="width:6.49167in;height:4.41667in" />

10. You should see the results.

<img src="./media/image20.png" style="width:6.5in;height:4.22361in"
alt="A screenshot of a computer screen Description automatically generated" />

11. 

<img src="./media/image21.png" style="width:6.5in;height:4.52847in"
alt="A screenshot of a computer Description automatically generated" />

9\. Ask your copilot to help with Display the number of rows and columns
in the dataframe. Click on +code .enter the code and then run the
kernel. You can also use below code

num_rows, num_cols **=** data**.**shape

print("Number of rows:", num_rows)

print("Number of columns:", num_cols)

<img src="./media/image22.png"
style="width:6.49167in;height:4.33333in" />

10\. Ask your Copilot to help you with this**Display the data types of
each column** .You can also user data.dttypes

<img src="./media/image23.png" style="width:6.5in;height:5.08958in"
alt="A screenshot of a computer Description automatically generated" />

12. Ask your GitHub Copilot provide code for Display the number of
    missing values in each column.

<img src="./media/image24.png" style="width:5.24212in;height:7.98403in"
alt="A screenshot of a computer Description automatically generated" />

13\. Add a new kernel and add the below code and run it. You can also
use the code suggested by Copilot and check

missing_values **=** df**.**isnull()**.**sum()

print(missing_values)

<img src="./media/image25.png" style="width:6.5in;height:4.91181in"
alt="A screenshot of a computer program Description automatically generated" />

13. Run the below code in the new kernel to Display the number of unique
    values in each column. Check with your copilot about code and
    results.

unique_values **=** df**.**nunique()

print(unique_values)

<img src="./media/image26.png" style="width:6.5in;height:4.99028in"
alt="A screenshot of a computer Description automatically generated" />

**Task 4 : Data Cleaning**

1.  Run the below code to Drop the columns that are not needed for the
    analysis. Ask you copilot for the code and check the results.

> data **=** df\[\['Country_Region', 'positive', 'total_tested'\]\]

<img src="./media/image27.png" style="width:6.5in;height:4.54861in"
alt="A screenshot of a computer Description automatically generated" />

2.  Type \#Rename the columns to make them more readable In a new kernel
    and accept the code.

> <img src="./media/image28.png" style="width:6.5in;height:3.29306in"
> alt="A screenshot of a computer Description automatically generated" />

3.  You can use the below code and run it.

df**.**rename(columns**=**{'Country_Region': 'Country', 'positive':
'Positive Cases', 'total_tested': 'Total Tested'}, inplace**=True**)

<img src="./media/image29.png" style="width:6.5in;height:3.03333in"
alt="A screenshot of a computer Description automatically generated" />

4.  Ask your copilot to Drop the rows that have missing values And run
    the code in a new kernel or Type \#Drop the rows that have missing
    values In new kernel press enter. Press the tab and accept the code

<img src="./media/image30.png" style="width:6.5in;height:4.44792in"
alt="A screenshot of a computer Description automatically generated" />

5.  Add a new +Code kernel and type \#Convert the data types of the
    columns to the appropriate types , press **tag** to accept the code,
    again enter and press tab. Generate code for Positive cases, Total
    Tested and country, and then run it.

<img src="./media/image31.png" style="width:6.5in;height:4.12639in"
alt="A screenshot of a computer Description automatically generated" />

6.  Add a new +Code kernel and type \#Display the number of missing
    values in each column And press Enter. Press tab and accept the
    code. You can also ask in GitHub Copilot chat

> <img src="./media/image32.png" style="width:6.5in;height:4.59167in"
> alt="A screenshot of a computer program Description automatically generated" />
>
> <img src="./media/image33.png" style="width:6.5in;height:4.81944in"
> alt="A screenshot of a computer screen Description automatically generated" />

**Task 5 : Extracting the Top Ten Countries with Most Covid-19 Cases.**

1.  Ask your Copilot chat to help you with code Create a new dataframe
    that contains the total number of positive cases for each country Or
    open new code and type \#Create a new dataframe that contains the
    total number of positive cases for each country and press Etner.
    Press tab to accep the code.

<img src="./media/image34.png" style="width:6.5in;height:4.52639in"
alt="A screenshot of a computer Description automatically generated" />

2.  In a new code enter below prompts and enter after each prompt to
    accept the code and run it.

*\# Group the data by 'Country' and calculate the sum of 'Positive
Cases'*

total_positive_cases **=** data**.**groupby('Country')\['Positive
Cases'\]**.**sum()

*\# Create a new dataframe with the total positive cases for each
country*

df_total_positive_cases **=** pd**.**DataFrame({'Country':
total_positive_cases**.**index, 'Total Positive Cases':
total_positive_cases**.**values})

*\# Display the new dataframe*

df_total_positive_cases

<img src="./media/image35.png" style="width:6.5in;height:4.32778in"
alt="A screenshot of a computer screen Description automatically generated" />

3.  Ask Copilot to Sort the dataframe in descending order of the total
    number of positive cases Or type \# Sort the dataframe in descending
    order of the total number of positive cases In the new Code kernel
    press tag to accept the code and run it.

<img src="./media/image36.png" style="width:6.5in;height:2.92639in"
alt="A screenshot of a computer Description automatically generated" />

4.  Ask your Github Copilot chat to help you with Display the top ten
    countries with the most positive cases Or type \# Display the top
    ten countries with the most positive cases In new code kernel and
    runt it. Remember you just need to display.

<img src="./media/image37.png" style="width:6.5in;height:4.50069in"
alt="A screenshot of a computer Description automatically generated" />

**Task 6 : Identifying the Highest Positive Against Tested Cases**

1.  Ask your GitHub Copilot Chat to help you with thisCreate a new
    dataframe that contains the total number of tests conducted for each
    country or open new Code kernel and type \# Create a new dataframe
    that contains the total number of tests conducted for each country
    and press tab to accep the code. You can edit the code if required
    and run it.

*\# Group the data by 'Country' and calculate the sum of 'Total Tested'*

total_tests **=** data**.**groupby('Country')\['Total
Tested'\]**.**sum()

*\# Create a new dataframe with the total tests conducted for each
country*

df_total_tests **=** pd**.**DataFrame({'Country': total_tests**.**index,
'Total Tests': total_tests**.**values})

*\# Display the new dataframe*

df_total_tests

<img src="./media/image38.png" style="width:6.5in;height:3.82986in"
alt="A screenshot of a computer Description automatically generated" />

2.  Ask your Github Copilot Chat Sort the dataframe in descending order
    of the total number of tests conducted Or open a new code kernel
    ,type \# Sort the dataframe in descending order of the total number
    of tests conducted And press tab to caccep the code and run it.

> <img src="./media/image39.png" style="width:6.5in;height:4.04722in"
> alt="A screenshot of a computer program Description automatically generated" />

3.  Ask your Github Copilot Chat Display the top ten countries with the
    most tests conducted Or open a new code kernel ,type \# Display the
    top ten countries with the most tests conducted And press tab to
    caccep the code and run it.

> <img src="./media/image40.png" style="width:6.5in;height:4.24236in"
> alt="A screenshot of a computer program Description automatically generated" />

**Task 7 : Identifying top three countries that have had the highest
number of positive cases against the number of tests carried out**

1.  Ask your Github Copilot Chat Merge the two dataframes created in the
    previous steps Or open a new code kernel and type \# Display the top
    ten countries with the most tests conducted And press tab to caccep
    the code and run it.

<img src="./media/image41.png" style="width:6.5in;height:4.27778in"
alt="A screenshot of a computer Description automatically generated" />

2.  Ask your Github Copilot Chat Create a new column that contains the
    ratio of positive cases to the number of tests conducted Or open a
    new code kernel and type \# Create a new column that contains the
    ratio of positive cases to the number of tests conducted And press
    tab to accept the code and run it.

> <img src="./media/image42.png" style="width:6.5in;height:3.65764in"
> alt="A screenshot of a computer Description automatically generated" />

3.  Ask your Github Copilot Chat Sort the dataframe in descending order
    of the ratio of positive cases to the number of tests conducted Or
    open a new code kernel and type \# Sort the dataframe in descending
    order of the ratio of positive cases to the number of tests
    conducted And press the tab to accept the code and run it.

<img src="./media/image43.png" style="width:6.5in;height:3.27708in"
alt="A screenshot of a computer Description automatically generated" />

4.  Ask your Github Copilot Chat Display the top three countries with
    the highest ratio of positive cases to the number of tests conducted
    Or open a new code kernel and type \#Display the top three countries
    with the highest ratio of positive cases to the number of tests
    conducted And press the tab to accept the code and run it

> \#Display the top three countries with the highest ratio of positive
> cases to the number of tests conducted
>
> top_countries = merged_df.nlargest(3, 'Positive Test Rate')
>
> top_countries\[\['Country', 'Positive Test Rate'\]\]

<img src="./media/image44.png" style="width:6.5in;height:4.15972in"
alt="A screenshot of a computer Description automatically generated" />

**Task 8 : Displaying the Results**

1.  Ask your Github Copilot Chat to Display the results a chart that
    shows the top three countries with the highest ratio of positive
    cases to the number Or open a new code kernel and type \# Display
    the results a chart that shows the top three countries with the
    highest ratio of positive cases to the number And press the tab to
    accept the code and run it

\#Display the results a chart that shows the top three countries with
the highest ratio of positive cases to the number

import matplotlib.pyplot as plt

top_countries.plot(x='Country', y='Positive Test Rate', kind='bar')

<img src="./media/image45.png" style="width:6.5in;height:4.33056in"
alt="A screenshot of a computer program Description automatically generated" />

2.  Ask your Github Copilot Chat to Display the results in a chart that
    shows the top ten countries with the most positive cases Or open a
    new code kernel and type \# Display the results in a chart that
    shows the top ten countries with the most positive cases And press
    the tab to accept the code and run it

\#Display the results in a chart that shows the top ten countries with
the most positive cases

import matplotlib.pyplot as plt

df_total_positive_cases.head(10).plot(x='Country', y='Total Positive
Cases', kind='bar')

plt.xlabel('Country')

plt.ylabel('Total Positive Cases')

plt.title('Top Ten Countries with the Most Positive Cases')

plt.show()

<img src="./media/image46.png" style="width:6.5in;height:4.29861in"
alt="A screenshot of a computer screen Description automatically generated" />

3\. Ask your Github Copilot Chat to Display the results in a chart that
shows the top ten countries with the most tests conducted Or open a new
code kernel and type \# Display the results in a chart that shows the
top ten countries with the most tests conducted And press the tab to
accept the code and run it

<img src="./media/image47.png" style="width:6.5in;height:3.46042in"
alt="A screenshot of a computer Description automatically generated" />

**Task 9: Conclusion**

1.  What are your conclusions?

2.  What are the limitations of this analysis?

3.  What are the next steps you would take to improve this analysis?
