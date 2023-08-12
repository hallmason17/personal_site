---
title: "Pivot Tables"
date: 2023-08-06T16:50:28-04:00
draft: true
---

## What is a Pivot Table?

A pivot table is a tool in Excel that makes it easy to quickly summarize a dataset. More powerful tools are required to work with huge sets of data, but pivot tables work great to quickly gather insights about smaller sets.

### Getting Started

#### Step 1. The Dataset

In the example today, I am working with the [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales) dataset from [Kaggle](https://www.kaggle.com). Kaggle is a great place to get data to practice on. The video game sales dataset shows sales data for over 16,000 games. This is a great size to use pivot tables on, depending on your processor, I suppose.  

#### Dataset must haves:
- Must be organized in columns (headers across the top), rather than in rows (headers down the side).
- All columns must have names (these must be unique). 
&nbsp;
&nbsp;
  
![Video Game Sales Data](/vgsalesdataset.png)


#### Step 2. Creating the Pivot Table

With your dataset prepped. Go ahead and select all of the cells you wish to include in the pivot table. To select all the data in the current sheet, which is what I usually do, you can either click the top left corner (left of the A column and above the 1 row) or you can press Ctrl-A once or twice to select all of the data in the sheet.  
&nbsp;
Next, go to the Insert tab at the top ribbon and click Pivot Table right underneath it. This will open up a pop-up window with prompts about data and the desired location of the pivot table. For most cases, you can just press OK since you already selected the data before hand. You should now be at a new excel sheet.

&nbsp;
&nbsp;

![Pivot Table Create](/pivot_table_create.png)

#### Step 3. Adding Data to the Pivot Table

Now we actually get to the fun part of summarizing the data. To add things to the pivot table, simply click and drag from the Field Names section into the configuration that you want. For example, to see video game sales in North America by genre in total (all years combined) drag Genre into the columns section and NA_Sales into the Values section. To see it by year as well, drag Year into either the rows or columns depending on your preference. These can also be sorted and filtered to your liking. I'll have a few examples below:

&nbsp;
&nbsp;

#### Total sales in North America by publisher & genre for all years:
![Pivot Table 1](/pivot_table1.png)


&nbsp;

#### Total sales in North America by publisher & genre by year for the PS3:
![Pivot Table 2](/pivot_table2.png)

