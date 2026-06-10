---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

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
|-------|-----------|----------------|
| **September** | Data Understanding | Explore dataset, handle missing values, document findings |
| **October** | Model Development | Train baseline model, experiment with approaches, iterate |
| **November** | Evaluation & Presentation | Finalize model, prepare presentation, document results |

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
- Logistic regression
- Decision trees
- Random forest
- Gradient boosting
- SHAP
- LIME
- Streamlit
- Gradio
- Google Colab

**Evaluation Metrics:**
- Accuracy
- Precision/Recall
- AUC-ROC Score

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).
