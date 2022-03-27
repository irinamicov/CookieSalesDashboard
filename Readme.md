# Cookie Sales Dashboard 

## Project description
Interactive dashboard in **Excel** built using cookie company data.

## The process
I started with a sample of the data (Sheet: *Data*) and created three **pivot tables**:

- Profit by Market & Cookie Type
- Units Sold Each Month
- Profit by Month

After cleaning and ordering the data in the pivot tables, I created charts from each, that I then copied to the **Dashboard** sheet.  

### To make this dashboard interactive, I added:

- A timeline to enable selecting data by month
- Two slicers to allow views by country and cookie type

The interactivity is applied to all charts.

Note: Selecting only one month from the timeline will generate nothing in the line graphs since we need at least two points for this type of chart.

### Adding new data
The sheet *New Data* contains additional data with the same characteristics (data columns, data types, column order) as the original data. I copied these records into the original table and refreshed the data in the Dashboard to make sure that the charts were updated.

## Project inspiration
I built this project by following [this video](https://youtu.be/MTlQvyNQ3PM) from [Kevin Stratvert](https://www.youtube.com/c/KevinStratvert).