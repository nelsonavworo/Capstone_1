Capstone_1 is a covid_19_data.csv flat file which was loaded into the postgres for simulation..
"C:\Users\USER\Downloads\Capstone Project 1.ipynb" -  this contains all my queries.
COPY covid_19_data(SerialNumber, ObservationDate, Province, Country, LastUpdate, Confirmed, Deaths, Recovered) FROM('C:/Users/USER/Downloads/covid_19_data.csv') WITH (FORMAT CSV, HEADER TRUE, DELIMITER','); - this was the code for loading into postgres
