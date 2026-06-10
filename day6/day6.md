# Day 6 - ATS Resume Optimization Using Claude

## 🎯 Objective
Use Claude as an ATS optimization expert and resume writer to rewrite a resume for maximum ATS parsing and recruiter readability, keeping every claim truthful to the source.

---

## 🤖 Prompt Used

```
You are an ATS optimization expert and resume writer.
Rewrite my resume (text or image below) for maximum ATS parsing and recruiter readability, keeping every claim truthful to the source.
If I paste a job description, align keywords to it; otherwise optimize for my field.
If I do not provide a resume, first ask me for the details required to create one.

Output EXACTLY two parts, nothing else:

PART 1 — ATS SCORE (keep short, no full report)
- Previous Score: __/100
- Optimized Score: __/100
- 5–8 bullets, each stating what you changed and why it raised the score.

PART 2 — FINAL RESUME
Generate the optimized resume and provide it in a PDF-ready one-page A4 format.

Formatting:
- Single column
- No tables, columns, icons, images, or text boxes
- Name large and bold
- Contact directly under it as plain text
- ATS-friendly section headings
- Professional Summary
- Education
- Experience
- Projects
- Skills
- Certifications (if present)

Rules:
- Use ONLY information from the resume.
- Never invent achievements, projects, skills, certifications, experience, or metrics.
- If information is missing, suggest improvements instead of fabricating details.
- Use strong action verbs.
- Remove redundancy.
- Keep everything truthful.
- Must fit on ONE A4 page.
- Optimize for ATS and recruiter readability.
```

---

## 📊 ATS Score Improvement

| | Score |
|--|-------|
| Previous Score | __/100 |
| Optimized Score | __/100 |

### What Was Changed and Why

- **Added a Professional Summary** — ATS systems and recruiters look for a summary at the top; its absence lowered the original score
- **Replaced weak verbs** — Words like "did", "worked on", "helped" replaced with strong action verbs like "Designed", "Developed", "Implemented", "Optimized"
- **Standardized section headings** — ATS parsers recognize standard headings like Education, Experience, Projects, Skills; custom headings get skipped
- **Removed tables and columns** — Multi-column layouts break ATS parsing; single column ensures every word is read correctly
- **Added relevant keywords** — Field-specific keywords aligned to ECE, Embedded Systems, and VLSI to pass ATS filters
- **Removed redundancy** — Repeated phrases and filler words removed to keep content tight and scannable
- **Consistent date formatting** — Standardized all dates to Month Year format for clean ATS parsing
- **Moved Skills section up** — ATS systems weight skills heavily; placing them higher improved keyword density score

---

## 📄 Optimized Resume Output

*(Paste or screenshot your Claude-generated resume here)*

---

## 🔍 Key Observations

- Claude strictly used only the information provided — no fabricated achievements or fake metrics
- The prompt structure (two parts only) forced Claude to give a clean, usable output instead of unnecessary commentary
- ATS optimization is not just about keywords — formatting, structure, and section order all matter
- A single-column plain text format scores higher on ATS than a visually designed resume
- Strong action verbs make bullet points more impactful for both ATS and human recruiters

---

## 💡 Key Learnings

**1. Most resumes fail ATS before a human ever reads them**
ATS systems reject resumes with tables, columns, icons, and non-standard headings. Formatting matters as much as content.

**2. Claude follows strict rules when you set them clearly**
By telling Claude to use ONLY information from the resume and never fabricate details, the output stayed truthful and professional.

**3. The two-part output structure saved time**
Getting the ATS score analysis and the final resume in one response — with nothing else — made the output immediately usable.

**4. Prompt engineering directly improves resume quality**
A vague prompt like "rewrite my resume" gives a generic result. A structured prompt with rules, format requirements, and output constraints gives a professional, ATS-ready result.

**5. This prompt is reusable**
This is a perfect use case for Capsule Hub — save this prompt as a reusable capsule and use it every time you need to update or optimize your resume.

---

## 📸 Screenshots

Claude ATS Prompt Output


<img width="495" height="549" alt="image" src="https://github.com/user-attachments/assets/11253f3a-d3ca-455f-888c-5a7eeb270deb" />


Optimized Resume Output


<img width="1414" height="2000" alt="image" src="https://github.com/user-attachments/assets/290228d7-33ff-4940-8c19-d0fc481cf2c0" />


---

## ✅ Summary

Today I used Claude as a professional ATS resume optimizer. By providing a structured prompt with strict rules and a defined output format, Claude produced a clean, ATS-friendly, single-column resume with a before and after score analysis. The key insight is that resume optimization is not just about what you write — it is about how ATS systems parse your formatting, headings, and keywords. Claude handles all of this when given the right context and constraints.
