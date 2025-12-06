# Aviation_flight_Project
Created dashboards on aviation flight dataset using Power BI, Excel, SQL, and Tableau to analyze flight performance and trends.
## Dataset
The aviation flight dataset used in this project can be accessed here:  
[Download AviationFlights Dataset](https://drive.google.com/drive/folders/1IriCtz7h92-w-PgGRzZDOdYZ6CyzK-CG?usp=sharing)
## ✈️ Aviation Flights Dashboard 
This dashboard summarizes the performance of various flights, highlighting issues like cancellations, diversions, and on-time status
### 🎯 Overall Key Performance Indicators (KPIs)

The header section provides the top-level operational summary:

* **Total Cancelled:** **$41K$**
* **Diverted Flights:** **$2544$**
* **On-Time Flights:** **$65K$**

---

### 📉 Analysis of Flight Delays

#### 1. Average Arrival Delay by Airline

This bar chart shows the average arrival delay in minutes for several airlines:

* **F9** has the highest average arrival delay at **24 minutes**.
* **MQ** follows closely with an average delay of **20 minutes**.
* Other airlines like **NK**, **B6**, and **EV** show lower but still significant average delays of **15, 14, and 10 minutes**, respectively.

#### 2. Count of Late Aircraft Delay by Airline and Day Status

This dual-bar chart compares late aircraft delays between **weekdays** and **weekends**:

* **WN** has the highest overall count of late aircraft delays, with **$31K$** on weekdays and **$12K$** on weekends.
* Most airlines (e.g., **WN, EV, DL**) experience more late aircraft delays on **weekdays** compared to weekends.
* **DO** and **OO** also show high delay counts, primarily on weekdays.

#### 3. Sum of WeekNo and Avg Delay by Airline

This area chart shows a relationship between the volume of flights (Sum of WeekNo) and the Average Delay (Avg Delay) for each airline:

* Airlines like **WN** have the highest volume (Sum of WeekNo), indicating a larger presence or more frequent flights.
* The chart generally shows that as the Sum of WeekNo decreases (moving right), the **Avg Delay (purple line)** remains variable, but airlines like **F9** and **EV** (seen in other charts) may contribute to the higher end of the delay scale.
### 🛑 Analysis of Cancellations and Diversions

#### 1. Airline-wise Top 5 Cancelled

This bar chart highlights the airlines with the most total cancellations:

* **MQ** has the highest number of cancellations at **$7.7K$**.
* **WN** and **EV** also have high cancellation counts at **$6.6K$** and **$6.3K$**, respectively.
* **AA** ($4.7K$) and **US** ($3.1K$) round out the top five.

#### 2. Top 5 Airport by Diverted Flights

This horizontal bar chart identifies the airports that handle the highest number of diverted flights:

* **ATL (Hartsfield-Jackson Atlanta)** leads significantly with **169** diverted flights.
* **DFW (Dallas/Fort Worth)** and **ORD (Chicago O'Hare)** follow with **144** and **133** diverted flights, respectively.
* **IAH (George Bush Intercontinental)** and **LAX (Los Angeles International)** also feature in the top five, with **112** and **104** diverted flights.
