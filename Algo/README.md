# ⚙️ Algorithms

This folder contains **algorithm implementations** in multiple languages.  
Contributors can add classic or custom algorithms with clear explanations and working code.

---

## 📂 Folder Structure

Solutions should be organized as follows based on the language branch:

cpp/algo/<Algorithm_Name>.cpp
java/algo/<Algorithm_Name>.java
python/algo/<Algorithm_Name>.py

Copy code

> ⚠️ Ensure that your **commit and PR target the correct language branch**.  
> 💡 If the branch for a language doesn’t exist, create a new branch with the language name.

---

## 💻 How to Contribute

1. **Fork the main repository**  
2. **Clone** your fork locally:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
Checkout to the correct language branch:

bash
Copy code
git checkout cpp      # or java / python
# OR create new branch for other language
git checkout -b <language-name>
Add your algorithm implementation in the algo/ folder for your language

Include:

Algorithm name

Clear explanation of how it works

Time and space complexity analysis

Optional: example input/output

Commit your changes:

bash
Copy code
git add .
git commit -m "Added <Algorithm Name> in <Language> with explanation"
Push your branch:

bash
Copy code
git push origin <branch-name>
Raise a PR:

Base branch → the correct language branch

Provide a clear PR title and description including a summary of the algorithm and complexity analysis

Example PR title:

Copy code
Added: Dijkstra Algorithm in C++ with explanation
✅ PR Acceptance Criteria
Solution belongs to the correct language branch

Code is well-formatted, readable, and commented

Explanation is clear and thorough

Commit message and PR title are meaningful

No plagiarism or spam

💡 Contributors can use AI tools like ChatGPT or Gemini for explanations, but the implementation must be original.