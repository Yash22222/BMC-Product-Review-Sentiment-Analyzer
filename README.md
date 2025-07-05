# 🔍 BMC Product Review Scrapping & Sentiment Analysis

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
git clone https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer.git
cd bmc-review-sentiment-analyzer
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
   git clone https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer.git
   ```
3. Create your feature branch

   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Commit your changes

   ```bash
   git commit -m "✨ Added sentiment model for XYZ"
   ```
5. Push to your fork

   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a **Pull Request** with a clear explanation.

### 🏷️ Good First Issues

Check the [Issues tab](https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer/issues) for tasks marked as:

* `good first issue`
* `documentation`
* `feature request`

---

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

* Built with ❤️ by [Yash Shirsath](https://github.com/YashShirsath)
* Proudly open for contributions under GSSoC 2024

```

---

## 🔧 What You Should Do Now

1. ✅ **Create GitHub repo**: `bmc-review-sentiment-analyzer`
2. ✅ Add this `README.md`
3. ✅ Push your starter code (`scraper.py`, etc.)
4. ✅ Add `requirements.txt`
5. ✅ Submit your project on [GSSoC Portal](https://gssoc.girlscript.tech)
6. Optional: Create 3–5 beginner issues tagged with `good first issue`

---

If you want, I can:
- Generate `requirements.txt` and starter files for you.
- Suggest 5 good starter issues for GSSoC contributors.

Would you like that?
```
Perfect, Yash! Here is your **final polished version** of the `README.md` that includes:

* ✅ All features you requested
* 🔗 Direct **links to the 4 Gartner product review pages**
* 📤 Clear contribution instructions with forking
* 📄 Output format expectations
* 💬 Simple, inviting language for contributors

---

## 🔥 Final `README.md` for Your GSSoC Project

````markdown
# 🔍 BMC Review Sentiment Analyzer

This project performs **sentiment analysis** on verified Gartner reviews of popular **BMC Software products**, using **Python NLP techniques** and **data visualization**.

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

## 🚀 Tech Stack

- **Python 3.x**
- **Selenium / Playwright** (for scraping)
- **NLTK, VADER** (for sentiment)
- **Pandas, Matplotlib, WordCloud**
- **Excel output (xlsxwriter/openpyxl)**

---

## 🛠️ Getting Started

### 🔧 Installation

```bash
git clone https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer.git
cd bmc-review-sentiment-analyzer
pip install -r requirements.txt
````

### 📊 Run Sentiment Analysis

1. Scrape reviews using the `scraper.py` script.
2. Clean and preprocess with `nlp_preprocessing.py`.
3. Analyze sentiment using `sentiment.py`.
4. Visualize using `visualize.py`.

---

## 🤝 How to Contribute (for GSSoC'24)

We welcome contributions from **GSSoC contributors and all open-source enthusiasts**!

### 🔁 Steps to Contribute

1. **Fork** the repository
2. **Clone** your fork

   ```bash
   git clone https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer.git
   ```
3. Create your feature branch

   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Commit your changes

   ```bash
   git commit -m "✨ Added sentiment model for XYZ"
   ```
5. Push to your fork

   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a **Pull Request** with a clear explanation.

### 🏷️ Good First Issues

Check the [Issues tab](https://github.com/YOUR_USERNAME/bmc-review-sentiment-analyzer/issues) for tasks marked as:

* `good first issue`
* `documentation`
* `feature request`

---

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

* Built with ❤️ by [Yash Shirsath](https://github.com/Yash22222)
* Proudly open for contributions under GSSoC 2025

```

---

## 🔧 What You Should Do Now

1. ✅ **Create GitHub repo**: `bmc-review-sentiment-analyzer`
2. ✅ Add this `README.md`
3. ✅ Push your starter code (`scraper.py`, etc.)
4. ✅ Add `requirements.txt`
5. ✅ Submit your project on [GSSoC Portal](https://gssoc.girlscript.tech)
6. Optional: Create 3–5 beginner issues tagged with `good first issue`

---

If you want, I can:
- Generate `requirements.txt` and starter files for you.
- Suggest 5 good starter issues for GSSoC contributors.

Would you like that?
```
