# mit-resume-reviewer

A Claude skill that reviews a resume against MIT CAPD's official resume writing guidelines and checklist.

## What it does

Upload a resume (PDF, DOCX, or paste as text) and the skill scores it across 8 categories, flags specific issues, and gives concrete improvement suggestions.

**Categories scored:**
1. General Format
2. Contact Information
3. Education
4. Experience
5. Skills
6. Activities / Honors / Leadership
7. ATS Optimization
8. Action Verb Strength & Variety

Each criterion is rated **Aligned**, **Partially Aligned**, or **Not Aligned**, followed by a prioritized list of fixes.

## Sources

Built from four MIT CAPD resources:

- [Resume guide for first-year undergraduates](https://capd.mit.edu/blog/2023/09/01/enhance-your-resume-a-guide-for-first-year-undergraduates/)
- [Resume checklist and worksheet](https://capd.mit.edu/resources/resume-checklist/)
- [Make your resume ATS-friendly](https://capd.mit.edu/resources/make-your-resume-ats-friendly/)
- [Power verbs for your resume](https://www.dice.com/career-advice/power-verbs-for-your-resume-and-cover-letter) (Dice)

## Installation

Download `mit-resume-reviewer.skill` and install it in Claude.
