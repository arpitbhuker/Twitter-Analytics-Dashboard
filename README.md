# 📊Real-Time Twitter Analytics Dashboard using Power BI

## 🚀 Project Overview

This project features a **robust, fully-interactive Power BI dashboard** built to monitor and decode live Twitter activity. It offers a granular view into how users interact with tweets by visualizing metrics like impressions, engagement rate, retweets, clicks, and hashtag performance — empowering stakeholders with **real-time, data-driven insights**.

---

## 📌 Key Features

### 🧠 Real-Time Data Intelligence

* Captures and processes key performance indicators (KPIs) from Twitter including:

  * **Tweet Text, Tweet ID, Time**
  * **Impressions, Engagements, Engagement Rate**
  * **Retweets, Replies, Likes**
  * **User Profile Clicks, URL Clicks, Hashtag Clicks**
  * **Date Hierarchy**: Year, Quarter, Month, Day, Date

### 📈 Insightful & Interactive Visualizations

* **Weekly Tweet Volume Trends** with deep-dive comparison into engagement spikes
* **Impressions vs. Engagements Benchmarking** to decode viewer interaction patterns
* Click-through insights across:

  * Profile views
  * URLs
  * Hashtags
* **Engagement Rate Analysis** to track content resonance
* Seamless use of **date-based slicers** for customized temporal filtering

### 📱 Responsive Design for Mobile & Desktop

* Architected with a **mobile-optimized layout** to ensure high usability on smartphones and tablets
* Maintains consistent visual experience across platforms
* Enables **real-time decision-making on the go**

---

## 🧾 Dataset Columns Used

| Column Name           | Description                                |
| --------------------- | ------------------------------------------ |
| `tweet`               | Text content of the tweet                  |
| `id`                  | Unique Tweet Identifier                    |
| `time`                | Timestamp of the tweet                     |
| `impressions`         | Number of times the tweet was seen         |
| `engagements`         | Total user interactions                    |
| `engagement rate`     | Ratio of engagements to impressions (%)    |
| `retweets`            | Number of retweets                         |
| `replies`             | Number of replies                          |
| `like`                | Number of likes                            |
| `user profile clicks` | Clicks on the profile from the tweet       |
| `url clicks`          | Clicks on any links in the tweet           |
| `hashtag clicks`      | Clicks on hashtags used in the tweet       |
| `year`                | Year of tweet                              |
| `quarter`             | Fiscal quarter of tweet                    |
| `month`               | Month of tweet                             |
| `day`                 | Day of the week                            |
| `date`                | Full date field (for slicing and grouping) |

---

## 🛠️ Tech Stack

* **Power BI Desktop**
* **Power BI Service (Mobile Optimization)**
* **Power Query M Language**
* **DAX (Data Analysis Expressions)**
* **CSV/Excel File as Data Source** *(for demo or actual Twitter exports)*

---

## 📸 Dashboard Snapshots

> ![image](https://github.com/user-attachments/assets/741be154-3f92-403f-b9eb-aabafce013db)


---

## 💡 Business Impact

* Provides **social media analysts** and marketing teams with real-time performance metrics.
* Tracks what drives engagement at a **tweet-level granularity**.
* Highlights peak activity windows and **content optimization opportunities**.
* Enhances campaign reporting and strategic planning via **data-backed storytelling**.

---

## 📂 How to Use

1. Clone/download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Load your Twitter data (CSV or Excel export with the columns listed above).
4. Customize visual themes or filters as per your brand or project needs.
5. Publish to Power BI Service for real-time access across devices.

---

## 📞 Contact

**Arpit**

B.E CSE (AI & ML) | Chandigarh University
> 📧 \[arpitkumarbhuker@gmail.com]
> 🌐 \[https://www.linkedin.com/in/arpitbhuker/]

---

## 📌 Future Enhancements

* Integrate direct Twitter API using Power Automate or Azure Data Factory
* Auto-refresh scheduling for hourly data sync
* Sentiment analysis of tweet content
* Geo-location-based tweet mapping


