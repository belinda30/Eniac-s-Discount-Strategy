

# Data Analysis: Eniac’s Discount Strategy Evaluation

This project analyses the effectiveness of Eniac's current discounting model. By evaluating the relationship between discount percentages, order volume, and seasonal revenue peaks (Black Friday & Christmas), this study identifies a "Sweet Spot" for maximising revenue without sacrificing brand value.

⚠️[! CAUTION !]⚠️

Data Quality Warning: During the initial cleaning phase, it was determined that over 80% of the original dataset was corrupted or contained null values. The following insights were derived from the remaining validated data. Consequently, significant focus was placed on identifying necessary database optimisations to prevent future data loss.

## 📋 Executive Summary

The primary recommendation of this analysis is to **adopt a targeted discount strategy centered around 20%**. The data shows that while Eniac currently discounts nearly its entire inventory, there are significant diminishing returns beyond the 20% mark.

---

## 🔍 Key Findings

### 1. The 20% "Sweet Spot"

Data visualisation of completed orders reveals that the highest volume and strongest revenue are achieved at a specific discount level.

* **Peak Performance:** 20% discounts generated the highest number of completed orders (875 orders).


* **Revenue Impact:** This specific tier produced a strong revenue of **78,125.98€**.


* **Diminishing Returns:** Increasing discounts to 30%, 40%, or 50% resulted in a sharp decline in order volume and overall inefficiency.



### 2. Inventory Distribution

The current strategy relies almost exclusively on price cuts.

* **Discounted Products:** 96% of the inventory.


* **Full-Price Inventory:** Only 4% of products are sold at original price.


* **Strategic Note:** The analysis suggests that "discounts aren't everything" and recommends "working smarter" rather than discounting the entire catalog by default.



### 3. Seasonality & Timing

Timing is critical for revenue spikes, specifically during Q4.

* **Black Friday (Nov 2017):** Revenue peaked at approximately **350,000€** during the late November period.


* **Christmas (Dec 2017):** Multiple revenue peaks occurred in December, hitting highs of over **60,000€** per spike.



### 4. Pricing Variations by Category

Product categories show vastly different median prices, suggesting that a "one size fits all" discount may not be effective.

* **High-End:** Computers (Median: 880€) and Mobile Devices (Median: 529€).


* **Low-End:** Audio (35€), Mounts & Stands (35€), and Repairs (26€).



---

## 🛠 Proposed Data Improvements

To enhance future analysis, the project recommends several database optimisations:

* **Database Normalisation:** Clean up SKUs and remove redundant/useless columns.


* **Product Categorisation:** Implement a 2-level taxonomy and a clear rule hierarchy to avoid overlapping categories.


* **Data Integrity:** Fix inconsistent naming conventions and date/currency formats.



## 👥 Contributors

**Team: Mastodon Meetup**

* Jake, Barbara, Tatiana, and Belinda.
