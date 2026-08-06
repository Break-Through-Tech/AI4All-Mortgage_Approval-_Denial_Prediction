

---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The tech stack is centered on Python, with prominent libraries for machine learning and interpretability included (e.g., scikit-learn, SHAP, LIME). |
| Data Readiness | 🟢 | The HMDA data is under 1GB, readily available in commonly used formats (CSV/TSV), and can be accessed easily for preprocessing without extensive cleaning requirements. |
| Resource Check | 🟢 | The project uses free-tier tools (Google Colab), so there are no hardware constraints that would impede students' access or capabilities. |

**Student Fit Score:** 9/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** APPROVE

**Advisor Feedback Draft:**
Strength: The project addresses a socially significant issue with technology; aligning ethical AI with business needs is commendable. Technical Adjustments: 1. Optimize the choice of evaluation metrics by emphasizing those that assess both performance and fairness more rigorously. 2. Increase focus on interpretability methods to ensure model results are understandable to diverse stakeholders, not just technical audiences. Next Steps: Consider revising the project scope to involve more advanced feature engineering techniques to enhance model robustness.

---

# Mortgage Approval & Denial Prediction

**Company / Org:** AI4All  
**Challenge Advisor:** David Taiwo Balogun, balogundavid98@gmail.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About AI4All

AI4All focuses on using artificial intelligence to foster inclusivity and fairness in technology applications across various sectors. Our organization works to educate and empower underrepresented groups in the tech industry, promoting the responsible development of AI.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use Home Mortgage Disclosure Act (HMDA) public loan application data, including applicant financial profiles, property details, and lender information, and supervised machine learning techniques such as logistic regression, decision trees, and gradient boosting to build a model that predicts mortgage approval or denial outcomes. This will help our company address the challenge of identifying key drivers of lending decisions, surfacing potential bias across demographic groups, and improving transparency and fairness in the mortgage approval process.

### Success Criteria
AUC-ROC Score of 0.80 or above, F1 Score/Precision-Recall balance, Fairness Metrics (demographic parity, equalized odds), and a clear, interpretable model with a bias audit report.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|---|---|---|
| September | Data & Exploration | • Download and understand the HMDA public dataset<br>• Perform exploratory data analysis (EDA): distributions, missing values, class imbalance<br>• Clean and preprocess data (encoding, normalization, handling nulls)<br>• Define the target variable and finalize feature set<br>• Establish a simple baseline model (e.g. logistic regression) |
| October | Modeling & Iteration | • Train and compare multiple ML models (decision trees, random forest, gradient boosting)<br>• Tune hyperparameters and evaluate using appropriate metrics (AUC-ROC, F1, precision/recall)<br>• Conduct fairness/bias analysis across demographic groups (race, gender, income)<br>• Identify the most predictive features via feature importance analysis<br>• Document findings and iterate on model performance |
| November | Insights & Delivery | • Finalize the best-performing model and validate on held-out test data<br>• Build a clear summary of bias findings and their business implications<br>• Create visualizations and a stakeholder-friendly dashboard or report<br>• Prepare and deliver a final presentation with recommendations<br>• Document the full pipeline for reproducibility and handoff |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Home Mortgage Disclosure Act (HMDA) public loan application data sourced from Kaggle  
**Format:** CSV, TSV, or Excel  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Home Mortgage Disclosure Act (HMDA) public loan application data, including applicant financial profiles, property details, and lender information, sourced from Kaggle. Data types include numerical, categorical, and time series in CSV/TSV or Excel formats.
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification

**Recommended Libraries:**
- [e.g., pandas, scikit-learn, TensorFlow, Hugging Face]

**Evaluation Metrics:**
- Accuracy
- Precision/Recall
- AUC-ROC Score

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [e.g., Link to an article or blog post about the problem domain]
- [e.g., Link to an industry report or case study]

**Technical Tutorials:**
- [e.g., Link to a free tutorial on the ML technique(s) involved]
- [e.g., Link to documentation for a key library or tool]

**Code Examples:**
- [e.g., Link to a relevant GitHub repo]
- [e.g., Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* [e.g., Your team's channel within Break Through Tech’s Discord space]
* [e.g., Email; please copy your teammates and AI Studio Coach]
* [e.g., Request a team check-in on Zoom]
* [Note: I will aim to respond within 48 hours. Please reach out to your AI Studio Coach with urgent questions.]

> 💡 **Challenge Advisor: Please update the above based on your availability and preference. If you are not able to answer questions or meet with fellows outside of the biweekly Lab Section check-ins, simply write in "N/A (only available during the official check-in times)"**

**Recommended free coding / collaboration tools**
* […]
* […]

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I’m excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session C). 
