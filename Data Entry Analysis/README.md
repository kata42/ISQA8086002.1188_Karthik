# ISQA8086002.1188_Karthik
**Issues with the 3 Files uploaded are as follows.**  
1. The excel files are named differently, two of the files mention that we are dealing with zoo Phyto plankton. Where as one of the other files is named as pond2010. 
2. Some of the data values are missing, which might lead to inconsistent results.
3. The columns in many of the files don’t have the measurement Units. The temperature, density, depth don’t have units in some files.
4. The charts in the excel files don’t have the x and y values mentioned.
5. Some of the values are highlighted but no description of the color is given.
6. The station names are given only in two files, one of the files is missing station name where the data was recorded.
7. The charts plotted in the two excel files are against different columns from the files. One of the charts is showing the change in temperature over time and the other is plotting the depth and #cuni/L.
8. Some of the columns are not defined, columns like ‘#cuni/L #chippo/L ,z’ is undefined. 


**Suggested Table Structure**

| Station Name | Species | Time (00:00 Hrs) | Date(mm/dd/yyyy) | Density (kg/m^3) | Colony Size(mm) | Temp(Faren/Cel) | Depth(Meters) |
|--------------|---------|------------------|------------------|------------------|-----------------|-----------------|---------------|
| Station A    | Cuni    |                  |                  |                  |                 |                 |               |
| Station B    | Chippo  |                  |                  |                  |                 |                 |               |



* The table can be structured as above. The important columns of the table are listed above.
* We can list the station name where the data is collected , and provide the units of the attributes in the columns in the table.
