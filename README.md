# 🌱 MSEED: Human Preference Dataset for Multidimensional Safety Enhancement and Evaluation of Large Language Models

## 🧩  Overview

Large language models (LLMs) have demonstrated impressive capabilities across various NLP tasks due to training on massive datasets. However, these datasets inevitably contain low-quality or harmful content, which can result in:

- ⚠️ Inappropriate or unsafe model outputs when dealing with sensitive topics  
- 💬 Poor user experience and degraded trust  
- ⚖️ Potential legal and ethical risks  

To mitigate these issues, research institutions have developed safety alignment datasets. Yet, existing resources suffer from **limited scale, poor generalization, and narrow coverage**, making them insufficient for robust alignment and evaluation.

### ✅ Why MSEED?

**MSEED** (Multidimensional Safety Evaluation and Enhancement Dataset) is proposed to address these limitations. It is designed to:

- 🧠 Cover diverse, multi-dimensional safety scenarios  
- 🌍 Support multiple languages with strong cross-lingual transferability  
- 🛠️ Serve both safety alignment fine-tuning and safety evaluation tasks  
- 📈 Enhance safety performance without compromising general capabilities of LLMs  

---

### 📌 Categories

MSEED is structured around **multi-dimensional safety categories**, including (but not limited to):

| Classification Dimension         | Specific Scenarios                               |
|------------------|-----------------------------------------|
| Value Violation   | Inciting Subversion of State Power, Endangering National Security and Interests, Undermining National Unity and Social Stability, Promoting Terrorism and Extremism, Promoting Ethnic Hatred, Promotes Violence and Pornography, Spreading False and Harmful Information, Other Content Prohibited by Law.      |
| Content of Discrimination    | Ethnic Discrimination, Faith Discrimination, National Discrimination, Regional Discrimination, Gender Discrimination, Age Discrimination, Occupational Discrimination, Health Discrimination, Other Discrimination.        |
| Business Misconduct     | Intellectual Property Infringement, Violation of Business Ethics, Disclosure of Trade Secrets, Implementing Unfair Competition, Other Business Misconduct.  |
| Rights Infringement | Harm to Physical and Mental Health, Infringement of Portrait Rights, Infringement of Reputation, Infringement of Honor, Infringement of Privacy, Infringement of Personal Information Rights, Infringement of Other Legal Rights.  |
| Unsafe for Specific Services        | Violate Scientific Common Sense or Mainstream Cognition, Content without Serious Errors but Insufficient to Assist Users |


Each item in the dataset is **manually classified** and **double-reviewed** to ensure quality and diversity.

---

### 📁 Dataset Structure

| Dataset       | Language | Size | Classification | Scenarios |
|------------|----------|----------|----------|----------|
| MSEED-Alignemnt      | Chinese   | 11348     |5 types     | 31 items    |
| MSEED-Evaluation       | Chinese   | 2852      | 5 types     | 31 items   |




---

## ⚠️Disclaimer

This data is only used to evaluate and improve the security of large language models. The data in the project does not represent any of our subjective opinions. The resources related to this project are only for academic research and are strictly prohibited from commercial use. We do not assume any legal responsibility for any losses that may arise from the use of related resources. Considering data security and potential impact, we only make part of the data set public. If you need all the data, please contact the author.



---

## 📁 File Structure


```bash
MSEED/
│
├── MSEED-Alignment-All-Label.json/    # All safety alignment data and labels
│
├── MSEED-Alignment.json/    # Safety alignment data
│
├── MSEED-Evaluation.txt/    # Safety Evaluation data
│
└── README.md                     # Documentation
