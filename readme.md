### Airbnb Listings EDA Project: New York 2024

[Click here to view the full repository and notebook](https://github.com/Devadharshni04/Airbnb-NYC-EDA-project)

---

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like **Pandas, Numpy, Matplotlib, Seaborn** for cleaning, visualization, and analysis.

---

## Objective

1. Analyze **room types, prices, and availability** across neighborhoods.
2. Understand **host behavior** and listing patterns.
3. Detect **outliers** in prices.
4. Estimate **potential annual revenue** for listings.
5. Provide **recommendations** for guests and hosts.

---

## Dataset

- **20,765 entries, 22 features**
- Features include: `id`, `name`, `host_name`, `neighborhood_group`, `latitude/longitude`, `price`, `room_type`, `reviews_per_month`, `availability_365`

---

## Steps and Workflow

### 1️⃣ Data Cleaning

- Handle missing data in `price`, `neighborhood`, `beds`
- Fix data types (`last_review` to datetime)
- Remove outliers (prices > \$1,000 capped)

### 2️⃣ EDA

- **Room Type Distribution**: bar plots show Entire home/apt is most common
- **Neighborhood Insights**: price variations by borough — Manhattan is highest
- **Availability Trends**: heatmaps for `price`, `availability_365`, `number_of_reviews`
- **Price Distribution**: histograms show most listings \$50–\$300
- **Host Listings**: boxplots show multiple listings per host
- **Review Behavior**: pair plots for reviews, price, availability
- **Revenue Estimation**: estimated annual revenue by `price * availability_365`

### 3️⃣ Data Visualization

- Pairplot
- Heatmap
- Histograms, Boxplots
- Bar charts
- Revenue charts by neighborhood

---

## Key Findings and Insights

- **Manhattan** has the highest prices and revenue potential
- **Entire home/apt** listings dominate; private rooms are cheaper
- **Outliers** above \$10,000 exist — need filtering
- **High availability** = lower prices, more reviews
- **Professional hosts** have multiple listings
- **Revenue potential**: Manhattan premium neighborhoods generate highest annual revenue

---

## How to Run

```bash
git clone https://github.com/Devadharshni04/Airbnb-NYC-EDA-project.git
```

Run the notebook in **Jupyter** or **Colab**.

---

## Recommendations

**Guests**: choose listings with high availability & good reviews, private rooms in Brooklyn are cheaper.\
**Hosts**: optimize availability, manage prices, target high-revenue neighborhoods.

---

## Future Work

- ML models to predict prices
- Sentiment analysis on reviews
- Interactive dashboards (Plotly, Tableau)

---

## 🔑 Skills Demonstrated

- Python (Pandas, Numpy)
- Data Cleaning, EDA
- Seaborn, Matplotlib
- Revenue estimation
- Business insights
- Git & GitHub

---

## Conclusion

This EDA reveals valuable insights for Airbnb guests & hosts. The project demonstrates practical data skills, strong business sense, and opportunities for deeper analysis.

---

## License

MIT License — open-source, free to use.

---

## Contact

- **GitHub**: [Devadharshni04](https://github.com/Devadharshni04)
- **LinkedIn**: [Devatharshini Elango](https://www.linkedin.com/in/devatharshini-elango-b03091231)

