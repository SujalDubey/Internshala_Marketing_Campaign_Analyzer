# INTERNSHALA LEADS ANALYSIS: CASE STUDY


## I OBJECTIVE

  To analyze a dataset that contains information about how leads are acquired, categorized, and converted, and also
  highlighting trends, patterns, or any other meaningful observations that could help the organization understand
  how leads are generated and how they interact with courses.

## PREREQUISITE

  Imagine you are working for an organization that offers advanced certifications in various courses.

## DATA SOURCE:
  Data is publicly available. I have attached it [here](https://github.com/SujalDubey/Internshala_Leads_Analysis-CaseStudy/blob/main/raw_data.csv).
  
## II DATASET OVERVIEW:
    1. Channel_group: Acquisition channel of the lead.
    2. Course: The course of interest to the lead.
    3. lead_id: Unique identifier for each lead.
    4. Lead_type: Type of interaction for lead generation.
    5. lead_date: Date of lead creation.
    6. graduation_year: Year of graduation.
    7. amount_paid: Amount paid by the lead (if applicable).
    8. paid_at: Date of payment (if applicable).


## DATA SUMMARY:
    1. Total Leads: 16,460.
    2. Total Unique Leads: 16,460 (No duplicates in lead_id).
    3. Total Leads Converted: 648 leads have payment information.
    4. Total Channel Groups: 13.
    5. Total Courses: 7

https://github.com/user-attachments/assets/dc739988-adff-43c7-9f11-c51fe7faea6c



## III KEY PERFORMANCE INDICATORS(KPIs) & INSIGHTS: [Live Dashboard](https://public.tableau.com/app/profile/lunistic/viz/Internshala_data_analysis/Analysis_dashboard?publish=yes) 
  1. ### Top Channels performance:
         1. A: 7,932 leads
         2. M: 1,647 leads
         3. F: 1,586 leads
         4. D: 1,294 leads
         5. E: 1,080 leads
     
  _Channel A dominates lead generation and conversion (313 successful payments)._

  2. ### Most Popular Courses:
[pie_chart](https://github.com/user-attachments/assets/350f584d-53e4-427e-9c9f-dcdaed34c9cf)

     1. Python: 4,323 leads
     2. Java: 4,250 leads
     3. CRM: 2,565 leads
     4. Guitar: 2,164 leads
     5. Google Analytics: 1,358 leads

  3. ### Top Courses Converted:
         1. Java: 181 payments
         2. Python: 132 payments
         3. CRM: 125 payments
         4. Guitar: 99 payments
         5. Google Analytics: 44 payments
  
  _Python and Java are the most popular courses among leads, bringing more than
50% of Total Leads._

  4. ### Payment Trends:
         1. Out of 16,460 leads, only 648 paid, with Java and Python being the most
          purchased courses(313).
         2. Leads generated through interacting with EFG gripped over 50% of the total
          payments.
         3. Only 3.9% of overall leads purchased the courses.
         4. Leads generated through interacting with EFG gripped over 50% of the total
          payments.

  6. ### CONVERSION RATIOS:
[Screenshot (82)](https://github.com/user-attachments/assets/42e03a45-6abc-4792-aab3-24967df8a0ad)

      1. Channel B has a conversion rate of over 15% for leads turning into paid leads.
      2. CRM has the highest conversion ratio of 5% w.r.t. Leads acquired.
  
[Screenshot (84)](https://github.com/user-attachments/assets/8ba2d288-b24f-4fb2-8471-6abaea0de85d)

  8. A slight peak was observed for 2024 graduates (569 leads).
  9. As per the data, on average, leads purchase the course within 8 to 10 days from the
      'Lead Date'.(Min. 1 day or Max. 28 days)

# [Stophisticated report](https://github.com/SujalDubey/Internshala_Leads_Analysis-CaseStudy/blob/main/Internshala_data_analysis_project.pdf)

## IV RECOMMENDATIONS:
    1. The Python Course should be included in Channel Group J, as it has proven highest lead generation.
    2. Promote Python, Java, and CRM courses, as they show high lead interest and conversion potential.
    3. Prioritize Channel A for both lead generation and conversion.
    4. Customize marketing strategies for 2024 graduates, as they represent a slightly larger share.
    5. Analyze low-performing channels and adjust strategies to optimize them.
    6. If we had dates for when the channel_group was created, we could compare the performances of the groups.

## V Conclusion:
  This report demonstrates a data-driven approach to lead analysis, providing actionable insights into acquisition channels, course preferences, and conversion rates. By leveraging these findings, businesses can refine their marketing efforts, optimize lead nurturing, and improve overall sales performance. The analysis highlights significant patterns in lead acquisition, interest, and conversion.

## VI ASSUMPTIONS:
  To enhance insights and refine our findings, several assumptions were made about the dataset:
    
    1. Assuming, Data is available for when the “channel_group” is created.
    2. Assuming, May 2024 had the highest leads recorded throughout the year 2024.
    3. Assuming, Every course is offered in every channel.
    4. Assuming the availability of data for “paid_at” is from May,1st to June, 1st.

## VII APPENDIX:

  1. To see the 1st raw analysis in Microsoft Excel [click here](https://github.com/SujalDubey/Internshala_Leads_Analysis-CaseStudy/blob/main/Data_analysis_in_excel.xlsx).
  2. Insights are also generated and analyzed in SQL language using PostgreSQL, here is the [link](https://github.com/SujalDubey/Internshala_Leads_Analysis-CaseStudy/blob/main/data_analysis_in%20SQL.txt) to queries
      used.
  3. Combined link to Google Drive is [here](https://drive.google.com/drive/folders/1lGV_NYDtJ6sEOxwiBUMSV5KYJnvGT2Cz?usp=sharing).
