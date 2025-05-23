# Hotel Booking Data Analysis

## 📌 Overview

This project analyzes booking cancellation patterns at two major hotel types — City Hotel and Resort Hotel — using real-world data from 2015 to 2017. With a significant cancellation rate impacting both revenue and room utilization, this analysis aims to uncover insights and propose actionable solutions to minimize cancellations and boost profitability.

## 💼 Business Problem

City Hotel and Resort Hotel are suffering from high cancellation rates, leading to:

* Reduced revenue
* Poor room utilization

### Objective

Reduce booking cancellations and provide strategic business insights to optimize revenue generation.

## 🎯 Assumptions

* No major external events influenced the data between 2015–2017.
* Data is relevant and reflects the hotels' operations accurately.
* Hotels aren't already using our proposed strategies.
* Cancellation is the biggest revenue challenge.
* A canceled booking leads to a vacant room.
* Cancellations and bookings occur in the same year.

## ❓ Research Questions

1. What factors influence hotel booking cancellations?
2. How can cancellation rates be minimized?
3. How can this data help hotels with pricing and promotional decisions?

## 🔬 Hypotheses

* Higher prices result in more cancellations.
* Longer waiting lists increase cancellation likelihood.
* Most bookings come from offline travel agents.

## 📸 Analysis and Findings

### Reservation status Chart
![Screenshot 1](screenshot/Screenshot%201.png)

* The accompanying bar graph shows the percentage of reservations that are canceled
and those that are not. It is obvious that there are still a significant number of
reservations that have not been canceled. There are still 37% of clients who canceled
their reservation, which has a significant impact on the hotels' earnings.

### Reservation status in different hotels
![Screenshot 2](screenshot/Screenshot%202.png)

* In comparison to resort hotels, city hotels have more bookings. It's possible that resort
hotels are more expensive than those in cities.

### Average Daily Rate in City and Resort Hotel
![Screenshot 3](screenshot/Screenshot%203.png)

* The line graph above shows that, on certain days, the average daily rate for a city hotel
is less than that of a resort hotel, and on other days, it is even less. It goes without
saying that weekends and holidays may see a rise in resort hotel rates.

### Reservation Status per month
![Screenshot 4](screenshot/Screenshot%204.png)

* We have developed the grouped bar graph to analyze the months with the highest and
lowest reservation levels according to reservation status. As can be seen, both the
number of confirmed reservations and the number of canceled reservations are largest
in the month of August. whereas January is the month with the most canceled
reservations.

### ADR for each month
![Screenshot 5](screenshot/Screenshot%205.png)

* This bar graph demonstrates that cancellations are most common when prices are
greatest and are least common when they are lowest. Therefore, the cost of the
accommodation is solely responsible for the cancellation.

### Top 10 countries with reservation cancelled
![Screenshot 6](screenshot/Screenshot%206.png)

* The top country is Portugal with the highest number of cancellations.

### Let’s check the area from where guests are visiting the hotels and making reservations.
Is it coming from Direct or Groups, Online or Offline Travel Agents? Around 46% of the
clients come from online travel agencies, whereas 27% come from groups. Only 4% of
clients book hotels directly by visiting them and making reservations.

### Average Daily rate
![Screenshot 7](screenshot/Screenshot%207.png)

* As seen in the graph, reservations are canceled when the average daily rate is higher
than when it is not canceled. It clearly proves all the above analysis, that the higher
price leads to higher cancellation

## 📊 Key Findings

* **37%** of bookings were canceled.
* City Hotels saw more bookings than Resort Hotels.
* Resort Hotels charge more during weekends and holidays.
* **August** had the highest number of bookings and cancellations.
* **January** had the highest cancellation rate.
* Cancellations peak when **prices are highest**.
* **Portugal** had the highest number of cancellations by country.
* **46%** of reservations came via **online travel agencies**, and **27%** from groups.
* Higher **average daily rate (ADR)** correlates with more cancellations.

## 🧠 Insights

* Price sensitivity is a key driver of cancellations.
* Guests prefer online and group booking channels.
* Seasonal trends and country-specific behavior matter.

## ✅ Recommendations

1. **Revise pricing strategies** — Introduce dynamic pricing and offer discounts for price-sensitive periods or locations.
2. **Resort Hotel discounts** — Offer weekend/holiday deals to reduce cancellations.
3. **January campaigns** — Promote targeted offers and campaigns to reduce cancellations in high-risk months.
4. **Portugal-specific solutions** — Improve service quality and communication in Portugal.

## 🛠 Technologies Used

* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook
* Git & GitHub for version control

## 📁 Project Structure

```
hotel-booking-data-analysis/
├── Data Analysis (Hotel Booking).ipynb
├── Report.pdf
├── hotel_bookings 2.csv
└── README.md
```

## 📸 Visual Highlights

>

>

>

## 🙌 Conclusion

This project provides crucial insights into booking behaviors, cancellation patterns, and pricing effects, helping hoteliers optimize revenue and reduce cancellations with data-backed strategies.

---

### 🔗 [Project Repository](https://github.com/deepaklokh/hotel-booking-data-analysis)

> *Developed by Deepak Lokhande*

> \*For collaboration, feel free to connect on \*[*LinkedIn*](https://www.linkedin.com/in/deepak-lokhande-82a887342/)
