# BMC Product Review Scrapping & Sentiment Analysis

This project performs **Web Scrapping** & **Sentiment Analysis** on verified Gartner reviews of popular **BMC Software Products**, using **Python NLP Techniques** and **Data Visualization**.

It includes:
- Web scraping from [Gartner Peer Insights](https://www.gartner.com/reviews)
- Preprocessing text with NLP
- VADER-based sentiment scoring
- Charts, word clouds, and Excel exports

## 🌐 Products Covered

We scrape verified reviews from the following Gartner pages:

| Product Name | Review Page |
|--------------|-------------|
| 🧠 BMC Helix ITSM | [Link](https://www.gartner.com/reviews/market/software-asset-management-tools/vendor/bmc/product/bmc-helix-itsm/reviews) |
| 📈 BMC Helix Operations Management | [Link](https://www.gartner.com/reviews/market/aiops-platforms/vendor/bmc/product/bmc-helix-operations-management-with-aiops/reviews) |
| ⚙️ TrueSight Server Automation | [Link](https://www.gartner.com/reviews/market/integrated-systems/vendor/bmc/product/bmc-truesight-automation-for-servers/reviews) |
| 📊 Control-M | [Link](https://www.gartner.com/reviews/market/service-orchestration-and-automation-platforms/vendor/bmc/product/bmc-control-m/reviews) |

---

## 📁 Output Format

Your final analysis should look like this (in Excel or CSV):

| Product Name | Review Title | Overall Rating | Industry | Function | Date | Other Vendors | Country | Pros | Cons | Overall Comment | Sentiment |
|--------------|--------------|----------------|----------|----------|------|----------------|---------|------|------|------------------|-----------|

Visuals like pie charts and word clouds should be stored in the `outputs/` folder.

---

## Example Directory Structure
   ```bash
📦 BMC-Product-Review-Scrapping-and-Sentiment-Analysis/
│
├── 📂 data/                   # Sample scraped data files (Excel/CSV)
├── 📂 notebooks/             # Jupyter notebooks for quick experimentation
├── 📂 scripts/
│   ├── scraper.py            # Scraper module
│   ├── nlp_preprocessing.py  # Text cleaning + POS + lemmatization
│   ├── sentiment.py          # VADER-based sentiment scoring
│   └── visualize.py          # Wordclouds, pie charts, bar graphs
│
├── 📂 outputs/               # Saved images, processed files
│
├── requirements.txt          # Install dependencies
├── README.md                 # Project overview
├── CONTRIBUTING.md           # Contribution guidelines
├── LICENSE                   # Open-source license
└── .gitignore
   ```

---

### IMP Features

🧠 Features
1. Robust product review scraper for BMC products
2. Clean text with:-
   Tokenization
   Lemmatization
   POS Tagging
   Stopword Removal
3. Sentiment classification using VADER
4. Generate sentiment reports and dashboards
5. Modularized structure for easy expansion and contributions
6. Export analysis to Excel and visual graphs

## 🚀 Tech Stack

- **Python 3.x**
- **Selenium / Playwright** (for scraping)
- **NLTK, VADER** (for sentiment)
- **Pandas, Matplotlib, WordCloud**
- **Excel output (xlsxwriter/openpyxl)**
- **Any**
---

## 🛠️ Getting Started

### 🔧 Installation

```bash
git clone https://github.com/YOUR_USERNAME/BMC-Product-Review-Scrapping-and-Sentiment-Analysis.git
cd BMC-Product-Review-Scrapping-and-Sentiment-Analysis
pip install -r requirements.txt
````

### 📊 Run Sentiment Analysis

1. Scrape reviews using the `scraper.py` script.
2. Clean and preprocess with `nlp_preprocessing.py`.
3. Analyze sentiment using `sentiment.py`.
4. Visualize using `visualize.py`.

---

## 🤝 How to Contribute (for GSSoC'24)

We welcome contributions from **GSSoC contributors and all open source enthusiasts**!

### 🔁 Steps to Contribute

1. **Fork** the repository
2. **Clone** your fork

   ```bash
   git clone https://github.com/YOUR_USERNAME/BMC-Product-Review-Scrapping-and-Sentiment-Analysis.git
   ```
3. Commit your changes

   ```bash
   git commit -m "✨ Added sentiment model for XYZ"
   ```
4. Push to your fork

   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a **Pull Request** with a clear explanation.


## 🧠 Contribution Ideas

| Type                          | Ideas                                   |
| ----------------------------- | --------------------------------------- |
| 🔄 Add new BMC products       | Expand the scraper                      |
| 🎨 Streamlit UI               | Upload reviews & analyze sentiment      |
| 🧾 PDF/Excel report generator | Auto reports for each product           |
| 🤖 Add BERT                   | Use HuggingFace transformer models      |
| 🌐 Multi-language support     | Translate & analyze non-English reviews |
| 🛠 Docker Support             | Add Dockerfile for easy setup           |

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Credits

* Built with ❤️ by [Yash Shirsath](https://www.linkedin.com/in/yash-shirsath-cr49/)
* Proudly open for contributions under GSSoC 2025

```
