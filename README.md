

# AirPollution-Analysis-SatelliteImagery #

**Overview**
------------
Understanding Air Pollution Using Satellite Imagery is a project that explores persistent air pollution levels in India despite various control measures. The project focuses on analyzing satellite data to compare pollutant levels across Indian cities, particularly highlighting differences before and after Diwali.

**Developed using:**
------------
1. **Language**: Python
2. **Data Manipulation and Analysis**: Pandas (pandas), NumPy (numpy)
3. **Data Visualization**: Matplotlib (matplotlib), Seaborn (seaborn), Plotly (plotly)
4. **Geospatial Data Processing**: Geopandas (geopandas)
5. **Data Sources**: Sentinel(via Copernicus Open Access Hub)

**Using Copernicus Data Space OAuth Credentials**
-------------
1. Clone the Repository
2. Install packagages in requirements.txt
3. Get OAuth ID and Secret Key

- Go to the Copernicus Data Space login page as shown in the image (https://shapps.dataspace.copernicus.eu/dashboard/#/).
- Sign in or create an account.
- Once logged in, click on "OAuth clients" on the sidebar, then click the + Create button to generate your OAuth credentials.
  <img width="587" alt="image" src="https://github.com/user-attachments/assets/d8fc8ec5-a1f0-44ea-80d0-38956955dc06">

 - Copy the Client ID and Client Secret, add the credentials in the **demo.ipynb**
 <img width="468" alt="image" src="https://github.com/user-attachments/assets/289b01f7-63a0-49b9-80f4-bbcd35bbccc0">

**Comparison of Air Quality Indicators in Kolkata and Chennai**
-------------
<img width="635" alt="Screenshot 2024-11-29 at 5 19 53 PM" src="https://github.com/user-attachments/assets/f897b8e5-5c44-4d14-9afb-5abf2fae8035">
<img width="635" alt="Screenshot 2024-11-29 at 5 19 53 PM" src="https://github.com/user-attachments/assets/fcb5a5ea-61bc-48f0-85a5-8bbd7a808d7d">

The air quality data for Kolkata and Chennai shows stable pollutant levels (SO2, NO2, CO), with minimal fluctuations. Ozone levels in both cities vary slightly but remain generally steady. Overall, the air quality indicators exhibit consistent trends across the observed period.


**Overall AQI Visualization**
-------------
![image](https://github.com/user-attachments/assets/cf701688-c858-4b24-b8e9-761b3ba68dec)
![image](https://github.com/user-attachments/assets/df8087c1-4502-487b-90b8-a685717a51bf)





 


