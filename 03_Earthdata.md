
---

# Earthdata Search by NASA

This R Markdown document provides instructions on how to create an account and use **Earthdata Search** by NASA. 

For the practical, you will only need your **Earthdata Login** credentials (username and password); you **must create an account** following the first steps in this document, but you do **not** need to search for your own data. However, if you have extra time during the practical or want to explore your own **region of interest (ROI)** in the future, you can follow the steps in the second section of this R Markdown file.

---

## Creating an Earthdata Account (Mandatory for the practical!)

If you already have an Earthdata account, you can skip this section.

To create an account:  

1. Go to [Earthdata Login](https://urs.earthdata.nasa.gov/).


   ![image](https://github.com/user-attachments/assets/90504e32-5be3-42d3-806e-1c788a8e31f2)  

2. Click **Register**.  
3. Fill in the required fields and click **Register for Earthdata Login**.  
4. Make sure to **remember your username and password**, as you will need them for the practical.

After registering, return to [Earthdata Login](https://urs.earthdata.nasa.gov/) and log in with your new account.

Once logged in, click on this link [Earthdata Search](https://search.earthdata.nasa.gov/), you will see the following page:


![image](https://github.com/user-attachments/assets/dab757f9-84ed-4f81-b8f5-c86b15715109)

---

## What is Earthdata Search?

**Earthdata Search** is an online tool developed by NASA that allows users to find, visualize, and download satellite and environmental data. It provides access to a wide range of datasets related to **land cover, climate, vegetation, atmospheric conditions, and more**.  

With Earthdata Search, you can:
- Browse and filter datasets from multiple NASA missions.
- Search for data based on location, time range, and data type.
- Preview and download datasets for further analysis.
- Integrate the data with R or other geospatial analysis tools.

---

## Searching and Downloading GEDI Data (Optional for exploration)

Now that you have an account and understand the basics, you can explore how to search and download data for your own **region of interest (ROI)**. Note that this is **not required for the practical** but only for your own exploration after the practical or if you want an extra challenge!

1. Go to [Earthdata Search](https://search.earthdata.nasa.gov/).  
2. In the **"Search for collections or topics"** search bar, enter **GEDI**, then click on **Instrument → GEDI**.


   ![image](https://github.com/user-attachments/assets/28933ca6-1fee-4a35-b332-2df897b7f26e)  

3. Zoom into your **ROI** and on the right-hand side, click **Search by rectangle/polygon/circle**.


   ![image](https://github.com/user-attachments/assets/b2bdad23-7431-46d2-b4b1-c62f42270a59)  

4. **Draw a shape** over your ROI to define the search area. 


   ![image](https://github.com/user-attachments/assets/a926ec47-9d51-4106-a1c9-d657a9b27a17)  

5. You have now selected data only within your ROI. Choose the dataset you are interested in.  
   - In this practical, we use **GEDI L2B data**, but you can also select **L4A data**, which provides biomass information, **L2A data**, **L1A data**...  
   - This will now display **GEDI orbits** that pass over your ROI.


   ![image](https://github.com/user-attachments/assets/b4a18a19-87d4-4c19-aec1-285f632c213d)  

6. Select the orbit(s) you are interested in by clicking the **"+" sign (Add granule to project)**.  
   - You can add multiple orbits as needed.  
   - Once you have selected your orbits, click **Download**.


   ![image](https://github.com/user-attachments/assets/5deb36a5-89f9-444e-94a2-937c0e51a1e0)  

7. In the download window, make sure **"Download all data"** is selected, then click **Done**, followed by **Download Data**.


   ![image](https://github.com/user-attachments/assets/76b0eaee-a681-4093-b9f4-05c372763a50)  

8. This will take you to a download page. Do **not** click Download. Instead, **copy the link** of the granule and update the download link in the [Jupyter Notebook of the practical](https://github.com/gdeslo/GEDI_course/blob/main/04_GEDI_L2B_notebook.ipynb).


   ![image](https://github.com/user-attachments/assets/7352700b-04fa-468a-ae5f-ef5abdedfa96)  

---
