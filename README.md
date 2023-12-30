# Description
Phishing refers to a type of online scam where attackers create fake websites to trick individuals into providing sensitive information such as usernames, passwords, credit card details, or other personal information. The term "phishing" is derived from the analogy of fishing, as cybercriminals "fish" for unsuspecting victims by pretending to be trustworthy entities. Phishing websites often mimic the appearance of legitimate websites, such as online banking sites, email providers, or social media platforms. Once the attackers have obtained this sensitive data, they can use it for various malicious purposes, such as identity theft, financial fraud, or unauthorized access to accounts.

# Dataset
The dataset includes 11430 URLs with 87 extracted features. Features are from three different classes: 56 extracted from the structure and syntax of URLs, 24 extracted from the content of their correspondent pages, and 7 are extracted by querying external services. The dataset is balanced, it contains exactly 50% phishing URLs and 50% legitimate URLs. Source: Hannousse, Abdelhakim; Yahiouche, Salima (2021), “Web page phishing detection”, Mendeley Data, V3, doi: 10.17632/c2gw7fy2j4.3

# Models
The machine learning models used are Logistic Regression, Random Forest, and Support Vector Machines (SVM). The Random Forest classifier stood out as the best performing model.

# Prerequisites
- The latest version of Python.
- Python packages such as pandas, seaborn, matplotlib, and sklearn.
- Jupyter Notebook.

# Install
1. Open any terminal as administrator.
2. To install pandas, run 'pip install pandas'.
3. To install seaborn, run 'pip install seaborn'.
4. To install matplotlib, run 'pip install matplotlib'.
5. To install sklearn, run 'pip install scikit-learn'.
6. To install Jupyter Notebook, run 'pip install notebook'.

# View & Edit
1. Open any terminal.
2. Navigate to the path of the Python notebook and Excel sheet.
3. To view and edit the Python notebook, run 'jupyter notebook phishing_url_detection.ipynb'.
