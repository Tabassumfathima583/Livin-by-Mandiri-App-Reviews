# 📊 Sentiment Analysis of *Livin’ by Mandiri* App Reviews

This project analyzes user reviews of the **Livin’ by Mandiri** mobile banking app, collected from the Google Play Store between **February and June 2024**. The goal is to evaluate user satisfaction, detect common issues, and identify how different app versions impacted user ratings.

---

## 📁 Dataset

- **Source:** [Kaggle - Livin' by Mandiri App Reviews Dataset](https://www.kaggle.com/datasets/itanium/livin-by-mandiri-app-reviews)
- **Records:** 10,000 user reviews
- **Fields:** `date`, `review`, `rating`, `thumbs_up`, `app_version`
- **Language:** Indonesian

---

## 🔍 Objectives

- Perform sentiment analysis on user review texts
- Track changes in average ratings over time and by app version
- Identify commonly mentioned complaints and praised features
- Analyze the relationship between thumbs-up votes and review ratings
- Provide actionable insights to improve app experience

---

## 🧪 Methodology

- **Data Cleaning & Preprocessing:** Python (Pandas, NumPy)
- **Natural Language Processing (NLP):** Tokenization, stopword removal, sentiment tagging (TextBlob)
- **Visualization Tools:** Matplotlib, Seaborn, WordCloud
- **Environment:** Jupyter Notebook (Anaconda)
- **Language Translation:** Google Translate API (manual checks for key insights)

---

## 📊 Visualizations Included

1. **Average Rating Over Time**  
2. **Average Rating by App Version**  
3. **Word Cloud of Frequent Terms**  
4. **Rating Distribution per App Version**  
5. **Thumbs-Up Votes vs. Ratings**

---

## 💡 Key Insights

- Ratings were mostly positive (average ~4.2), but some versions (e.g., 5.2) caused dips in satisfaction.
- Frequent user issues included login problems, app crashes, and slow performance after updates.
- Positive feedback focused on the app’s ease of use and modern interface.
- Some 1–2 star reviews received high thumbs-up counts, indicating helpful criticism.

---

## ✅ Conclusion

The *Livin’ by Mandiri* app is generally well-received. However, performance issues tied to specific updates led to temporary dissatisfaction. Monitoring review sentiment by version and responding to high-impact user feedback (especially highly "liked" reviews) can improve the app’s reputation and functionality.

---

## 📂 Files in This Repository

| File/Folder             | Description                                  |
|-------------------------|----------------------------------------------|
| `livin_reviews.csv`     | Cleaned dataset (if shared)                  |
| `notebook.ipynb`        | Main Jupyter Notebook for analysis           |
| `poster.png`            | Final poster visual (A1 or A3 format)        |
| `presentation.pptx`     | Summary slide deck (optional)                |
| `README.md`             | Project documentation                        |

---

## 📚 References

- Itanium. (2024). *Livin’ by Mandiri App Reviews Dataset*. Kaggle.  
  [https://www.kaggle.com/datasets/itanium/livin-by-mandiri-app-reviews](https://www.kaggle.com/datasets/itanium/livin-by-mandiri-app-reviews)

- Mendeley Data. (2024). *User Reviews of Livin’ by Mandiri App (Feb–Jun 2024)*.  
  [https://data.mendeley.com/datasets/h8p5v6r6dn](https://data.mendeley.com/datasets/h8p5v6r6dn)

- Chrome Stats. (2024). *Livin’ by Mandiri App Review Summary*.  
  [https://chrome-stats.com/d/id.bmri.livin/reviews](https://chrome-stats.com/d/id.bmri.livin/reviews)

- Academic studies using this dataset (Naive Bayes, SVM, MLP):  
  [Zenodo](https://zenodo.org/records/15559669),  
  [KINETIK Journal](https://kinetik.umm.ac.id/index.php/kinetik/article/view/2248)


  

