# 🎬 Netflix Content Strategy & Viewership Analysis (2023)

## 👋 Overview

This project involves a comprehensive data analysis of Netflix's global viewership trends during 2023. By examining a dataset containing thousands of titles, I aimed to identify the factors that drive high viewership, such as content type (TV shows vs. Movies), global availability, and the impact of holiday-timed releases on audience engagement.

## 🚀 Key Features & Analysis

  * **Viewership Distribution:** Analyzed the total hours viewed to distinguish between "Viral Hits" and niche content.
  * **Content Type Benchmarking:** Compared the performance of multi-season TV shows against standalone feature films.
  * **Global Accessibility Study:** Quantified the impact of "Global Availability" on total viewership hours to prove the ROI of international licensing.
  * **Holiday Release Impact:** Conducted a specialized study on content released near major holidays (New Year's, Valentine's Day, Independence Day, Halloween, and Christmas).
  * **Language Performance:** Segmented viewership based on language indicators to identify trends in non-English content success.

## 🛠️ Technical Toolkit

  * **Language:** Python
  * **Data Manipulation:** **Pandas** for filtering, cleaning, and time-series conversion.
  * **Time-Series Analysis:** Utilized `pd.to_datetime` and window functions to analyze release dates relative to significant holidays.
  * **Data Visualization:** (Typically Matplotlib/Seaborn) for identifying viewership peaks and content distribution.

## ⚙️ How It Works

1.  **Phase 1: Data Pre-processing** – Cleaned the Netflix dataset, handled language indicators, and formatted the `Hours Viewed` and `Release Date` columns.
2.  **Phase 2: Holiday Windowing** – Created a logic to identify content released within a **3-day window** of major 2023 holidays.
3.  **Phase 3: Aggregation** – Grouped viewership data by release dates and content types to calculate cumulative performance metrics.
4.  **Phase 4: Comparative Study** – Analyzed the "Night Agent: Season 1" and other top-tier titles to establish benchmarks for high-performance content.

## 📂 Project Structure

```plaintext
Netflix-Analysis-2023/
│── netflix_data.csv       # Raw viewership dataset
│── NF_analysis.ipynb      # Complete Python analysis and code cells
│── Visualizations/        # Exported charts of viewership trends
└── README.md              # Project documentation
```

## 📈 Key Business Insights

  * **The Holiday Boost:** Analysis suggests that content released near significant holidays (like Christmas and New Year's) sees a concentrated spike in viewership hours within the first week.
  * **Global Advantage:** Titles tagged with "Available Globally" consistently out-performed regionally restricted content by a significant margin.
  * **Series Dominance:** Multi-episode seasons (e.g., *The Night Agent*) tend to generate higher total "Hours Viewed" compared to films, due to longer total duration and binge-watching behavior.
  * **Timing Strategy:** Identified a "3-day window" around major events as the most effective period for maximizing initial release impact.

## 🤝 Connect

💼 **LinkedIn:** [linkedin.com/in/nitishkumar-khavekar](https://www.google.com/search?q=https://www.linkedin.com/in/nitishkumar-khavekar)  
💻 **GitHub:** [github.com/Nitishkumarkhavekar](https://www.google.com/search?q=https://github.com/Nitishkumarkhavekar)
