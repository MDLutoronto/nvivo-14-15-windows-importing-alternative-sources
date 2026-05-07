---
created_date: 2023-11-20
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Survey Data
parent: Importing Alternative Sources in NVivo 14/15 for Windows
nav_order: 2
layout: default
---
**Survey Data**
---------------

Another common data type that you might want to use NVivo to analyze is survey data. NVivo can import survey data in directly from SurveyMonkey and Qualtrics, so if you use those tools, just select those options from the Import Ribbon. However, you may have your survey data just stored in a spreadsheet, where each row is a survey respondent’s answers and each column is a question. We can also import this type of data into NVivo.

Note: This activity assumes you are familiar with case classifications and cases in NVivo. If case classifications and cases in NVivo is new to you, you can learn more in our [Introduction to NVivo 14/15 tutorial](https://mdlutoronto.github.io/nvivo-14-15-windows-intro/)!

1. To start, let's download a small sample of survey data called the [Millennial Sentiment Interview Transcript Dataset](https://www.kaggle.com/parmarmanojkumar/msitd?select=Interview_Database.xlsx). This data set is hosted on Kaggle, which is an public data platform. To download this data you’ll first have to register for a free account (or sign in if you already have one). Click Register at the top right of the website.

    <img src="{{ '/assets/images/NVivo_Import_Data_Win_B_000.1.png' | relative_url }}" alt='Kaggle page with Millennial Sentiment Interview Transcript Dataset. Register button in the top right highlighted.' title='' width='1000' height='634' />

  
 

    After you’ve signed in, click the little download arrow next to the file name and save it somewhere you can find it, such as the Desktop.

    <img src="{{ '/assets/images/DownloadMillennialDatasetv2.png' | relative_url }}" alt='There is a download arrow highlighted next to the name of the dataset' title='' width='1237' height='744' />

2. Go to NVivo. From the top menu, under Import, select **Survey \> Excel.**

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0005.png' | relative_url }}" alt='Under the import ribbon, survey is selected and Excel is selected. ' title='' width='942' height='291' />

3. Browse to the folder where the Millennial Sentiment Interview Transcript Dataset (file Interview\_Database.xlsx) was saved. Select the file, and then click on Open.

    <img src="{{ '/assets/images/Survey_2.png' | relative_url }}" alt='Survey Import file browser with the file "Interview_Database.xlsx" selected and the "Open" button highlighted.  ' title='' width='844' height='508' />

4. NVivo’s Survey Import Wizard will open up to help you import your data. For each row, it will create a case for the survey respondent. For each closed\-ended question that it detects, it will capture that information about the survey respondent as case attributes. Then it will import each open\-ended question as spreadsheet content that can be coded, and automatically code each question’s response with a new code for that question. Let’s go through the wizard together to see this in action. Click on Next.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0006.png' | relative_url }}" alt='Survey Import Wizard Step 1 with Next highlighted. ' title='' width='647' height='644' />

  
 

5. First it checks the data format. Our first row is our column headers, so we can keep the default. We don’t have any dates in our survey, so again we can keep the default, but if you are working with dates, then take a look at this option. It will also present you with a preview of the data. Click on Next.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0007.png' | relative_url }}" alt='Survey Import Wizard Step 2 with Next highlighted. ' title='' width='653' height='648' />

  
 

6. The next screen asks for information about creating cases and case classifications for our survey respondents (i.e., rows) in our dataset. In this case, we can keep all the defaults, as it will create a new case classification called Survey Respondent, and it will use the column Sr No as the unique ID for each case, which makes sense. Click on Next.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0008.png' | relative_url }}" alt='Survey Import Wizard Step 3 with Next highlighted. ' title='' width='654' height='648' />

  
 

7. The next screen automatically detects which questions are closed\-ended and will be used for attributes in this case classification. You can correct NVivo if there are any mistakes. You can also choose any columns that you don’t want to import. In our case, it looks good, so click on Next.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0009.png' | relative_url }}" alt='Survey Import Wizard Step 4 with Next highlighted. ' title='' width='656' height='647' />

  
 

8. The next screen provides you an option to autocode responses by sentiment (i.e., positive or negative), and by themes, meaning NVivo tries to come up with themes based on the content of the text. Sentiment can be useful, especially if you have a huge amount of survey responses and won’t be manually coding all the answers, but want to get a sense of the content. For example, a survey question might be – did you like a particular product, and then NVivo can code for sentiment to see if generally people liked it or didn’t like it. Thematic coding is trickier and may not result in a lot of useful information. You can always give it a try if you like and then not use those codes if they don’t make sense. In our case, let’s keep both checked to see the results.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0010.png' | relative_url }}" alt='Survey Import Wizard Step 4 with Auto code Themes and Auto code Sentiment checked off and highlighted. ' title='' width='652' height='647' />

  
 

9. Then click finish to complete importing in our data. Note: The first time you do this in NVivo, it may say it needs to first download additional components in order to complete the task, and so it could take longer to run than normal.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0011.png' | relative_url }}" alt='Survey Import Wizard Step 4 with Finish highlighted. ' title='' width='648' height='645' />

  
 

    You will see a progress screen. Auto coding will take a bit of time to complete depending on the size of your survey. When it is finished, click on Close.

 

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0012.png' | relative_url }}" alt='Survey Import Wizard processing window with close highlighted. ' title='' width='651' height='650' />

  
 

10. NVivo will open up a number of tabs with different views of the data. The first tab (on the far right) you will see is your survey data in spreadsheet format. This is where you can read through the responses and code the data.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0013.png' | relative_url }}" alt='NVivo data tabs opened. The "Interview_Database" tab selected and highlighted.' title='' width='1036' height='829' />

  
 

11. Moving from right to left, the next tab shows you a visualization of sentiment, but I don’t find it very useful, so I would close this tab.

    <img src="{{ '/assets/images/Survey_11_0.png' | relative_url }}" alt='NVivo data tabs opened. The "Composed by number of sentiments" tab selected and highlighted.' title='' width='1115' height='1133' />

  
 

12. The next tab shows a matrix of sentiment by each survey respondent case. Here you can see generally if the survey respondent’s answers were fairly positive or negative, and spot some outliers.

    <img src="{{ '/assets/images/Survey_12.png' | relative_url }}" alt='NVivo data tabs opened. The "Auto code sentiment results" tab selected and highlighted.' title='' width='1081' height='506' />

  
 

13. The next tabs shows a visualization of themes found in the survey data responses, where the boxes and sub\-boxes are autogenerated codes, and the size of the box is how frequent that code occurred.

    <img src="{{ '/assets/images/Survey_13.png' | relative_url }}" alt='NVivo data tabs opened. The "Compared by number of coding references" tab selected and highlighted.' title='' width='1087' height='970' />

  
 

14. The final tab shows a matrix of the themes by survey respondent.

    <img src="{{ '/assets/images/Survey_14.png' | relative_url }}" alt='NVivo data tabs opened. The "Auto code sentiment results" tab selected and highlighted.' title='' width='1087' height='459' />

  
 

15. Using the left menu, under Coding, expand Codes, to explore the autogenerated nodes. First click on the Autocoded Themes folder to explore the autogenerated codes identified by NVivo in your content and their references.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0014.png' | relative_url }}" alt='In the left menu, under coding, Codes is expanded and autocoded Themes is selected and highlighted.' title='' width='914' height='875' />

  
 

16. Next click on the Interview\_Database folder to explore the codes that were autogenerated for each question.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0015_0.png' | relative_url }}" alt='In the left menu, under coding, Codes is expanded and Interview_Database is selected and highlighted.' title='' width='906' height='877' />

  
 

17. Finally, click on the Sentiment folder under Coding, to explore the positive and negative codes and references. For any newly created Code, you can double click on it to see the references.

    <img src="{{ '/assets/images/NVivo_NCapture_Windows_0016.png' | relative_url }}" alt='In the left menu, under coding, sentiment is selected and highlighted.' title='' width='908' height='882' />

**Technique:** [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tool:** [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo) 
 