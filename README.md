# Revenue-Drop-Root-Cause-Analysi
>🔍 **Why did profit fall in some regions in 2019?**
> I used Excel to find out. Short answer: **high discounts** are the likely link.

---

## 🧭 What this project is about

Sales were growing for the company as a whole, but **profit dropped in Central and South** in 2019. 🤔

I wanted to answer three questions:

1. 📅 **When** did profit dip?
2. 🗺️ **Where** did it dip?
3. 🏷️ **Why** did it dip?

I also wrote a **one-page memo** for a sales manager, with a finding, a number, a recommendation and a risk. 📝

---

## 📦 The Data

- 🗂️ **Source:** [Superstore Sales dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- 🔢 **Size:** 9,994 order rows
- 📆 **Period:** January 2016 to December 2019
- 💲 **Currency:** US dollars

I never changed the original file. I worked on a copy. 🛡️

---

## 🛠️ Tools I Used

| Tool | What I did with it |
| --- | --- |
| 📊 **Excel** | Cleaning, helper columns, PivotTables, charts |
| 📝 **Word** | The one-page memo |

---

## 🪜 My Steps

1. 🔎 **Inspect:** Checked the rows, dates and blank cells.
2. 🧹 **Clean:** Added Month, Year, Margin and Discount_Level columns.
3. 📈 **Trend:** Charted sales and profit month by month.
4. 🧩 **Break down:** Split the drop by region, category, segment and discount.
5. 🧪 **Test guesses:** Tested three possible causes and ruled one out.

---

## 💡 Key Findings

- 🏚️ **Central:** Profit fell **62%** (from $19,899 to $7,551) while sales stayed flat (down 0.2%). Margin dropped from 13.5% to 5.1%.
- 🏚️ **South:** Profit fell **50%** (from $17,703 to $8,849) even though sales rose 31%. Margin dropped from 18.9% to 7.2%.
- 🏷️ **Discounts:** In these two regions, losses on discounts above 20% grew from **$12,687 to $31,078** in 2019. That is about **87%** of their combined profit drop.

### ❌ A guess I ruled out
- 📉 *"Central's profit fell because its sales fell."* → **False.** Sales barely moved, but profit collapsed.

### 📅 Seasonality
- Sales fall from March to April **every year**. That pattern is normal, so it does not explain the 2019 drop.

---

## 🎯 Recommendation

🛑 **Review and cap discounts above 20%** in Central and South, starting with the products that carry them. Then re-check their margins after one quarter.

---

## ⚠️ Limits (Please Read!)

- ⏳ Only **four years** of data.
- 💸 **No cost data**, so I could not check shipping or product costs.
- 🔗 Discounts are **linked** to the losses, but the data does **not prove** they caused the 2019 drop.
- 🗺️ Regional totals do not show exactly which products are responsible.

---

## 📁 Project Files

```text
Revenue-Drop-Root-Cause-Analysis/
│
├── 🗂️ data/
│   └── Superstore_Analysis.xlsx      ← my cleaned workbook
│
├── 📝 memo/
│   └── Superstore_Profit_Memo.pdf    ← one-page memo for the manager
│
├── 🖼️ images/
│   ├── profit_by_region.png          ← chart screenshots
│   └── discount_losses.png
│
└── 📖 README.md                      ← you are here!
```

---

## 🚀 How to Open the Project

1. ⬇️ Download the repository.
2. 📊 Open `data/Superstore_Analysis.xlsx` in Excel to see my PivotTables and charts.
3. 📝 Open `memo/Superstore_Profit_Memo.pdf` for the one-page summary.

---

## 👤 Author

**Nikhil Sharma** 🎓
Aspiring Data Analyst 💼 | Excel • SQL • Python • Power BI

⭐ If you enjoyed this project, please star the repository!
