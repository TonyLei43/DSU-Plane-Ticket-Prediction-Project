# Plane-Ticket-Prediction-Project
## DSU Winter 23 Internal Project

We will be exploring what factors contribute to a single plane ticket price with a linear regression model that predicts the price of a plane ticket to a certain destination of interest. We wish to hopefully uncover hidden factors that may lead to a “better” time to book your next dream vacation. 

This project aims to train a **linear regression model** that inputs a month and location and other qualitative attributes and outputs the flight price prediction. The attributes include but are not limited to: season of travel, time of booking, airline, layovers, time of delay, passenger count, etc…
We wish to answer the following questions :

**Q:**
- How much do specific airlines affect ticket prices?
- Are there trends within airlines from year to year for ticket prices
- How has flying changed pre-covid to post?
- Are there benefits to having a layover for a cheaper ticket?
- What season is actually the cheapest time to travel to {Asia, Europe, etc…}
- Is it usually cheaper to book in advance? If so, how “early” should one book their tickets?
- Does departing from a city within a certain distance drastically affect ticket prices?
- And more…

## Datasets
We will be primarily utilizaing this [dataset](https://www.kaggle.com/datasets/dilwong/flightprices) (31.1 GB).
> "This dataset is a CSV file where each row is a purchasable ticket found on Expedia between 2022-04-16 and 2022-10-05, to/from the following airports: ATL, DFW, DEN, ORD, LAX, CLT, MIA, JFK, EWR, SFO, DTW, BOS, PHL, LGA, IAD, OAK. **_Each row represents a record for a flight found on Expedia. The same flight will appear on multiple rows, as the price may change day-to-day._** " 

### Sub-Datasets

- [LAX Flights Departures](https://drive.google.com/file/d/18uAXZ7Md2p9vZSrz2kkBSXpTm3I-OW0I/view?usp=sharing) (2.43 GB)
- [LAX Flights Departures Nonstop](https://drive.google.com/file/d/1iA1FFoIx920PLKBkx-cspIYW7QRVTSV7/view?usp=sharing) (388 MB)
- [LAX Flights Arrivals](https://drive.google.com/file/d/1OkqonUhuHyXKd7-WW8BLqRLeahNU80Gg/view?usp=sharing) (2.41 GB)
- [LAX Flights Arrivals Nonstop](https://drive.google.com/file/d/11E_jTiEUE10RLbWG3HGAGWrmTRzzJp3D/view?usp=sharing) (395 MB)
- [LAX Flights](https://drive.google.com/file/d/1CFBEN8dQhKZZrJrLm2TjrIn3Z-CGSkjk/view?usp=sharing) (4.84 GB)
- [LAX Flights Nonstop](https://drive.google.com/file/d/1siQeCQ_OHa2xKVikY5WkcLclL7eJ03gS/view?usp=sharing) (783 MB)

### Others
- [Consumer Airfare Report](https://data.transportation.gov/Aviation/Consumer-Airfare-Report-Table-5-Detailed-Fare-Info/bkh6-tj42) (2.37 MB)
