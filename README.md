# TSE_Research_Paper
**Project: GitHub Issue Analysis**

**Description:**
This project extracts and analyzes GitHub issues from multiple repositories using the GitHub API. It performs feature engineering, classification, duplicate detection, and filtering to generate a structured dataset for analysis.

---

**How to Run:**

1. Install required libraries:

   ```
   pip install pandas requests tqdm
   ```
2. Add your GitHub token inside the script.
3. Run the script:

   ```
   python main_script.py
   ```

---

**Output (Generated Files):**
The following dataset files will be automatically generated after running the code:

* `final_github_bug_dataset.csv` — complete dataset of all fetched issues
* `filtered_recent_active_bugs.csv` — filtered dataset (recent issues with more than 5 comments)

---

**Note:**
Make sure you have a valid GitHub API token to successfully fetch the data.
