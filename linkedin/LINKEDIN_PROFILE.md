# LinkedIn profile rewrite: Priyanshu Gawlikar

Built from your CV and the screen recording of your profile. I couldn't open LinkedIn itself (login wall), so everything below is based on what was visible in the video.

## 0. Fix these first (they hurt you with recruiters)
1. **Headline says "Student at Dublin City University".** You graduated in Jan 2026. Replace it (section 1).
2. **Banner and photo:** upload `linkedin_banner.png` (3168x792, shown at 1584x396). The text is kept right of the profile photo so it isn't covered. The green #OpenToWork ring on your photo is fine; keep it.
3. **Your CV and LinkedIn disagree.** Recruiters and background checks compare them. Pick the true version and make both match:
   - Cognizant: CV says "Automation Test Engineer, 01/2022-06/2022"; LinkedIn says "Test Engineer" (Jan-Jun 2022) plus a separate "QA Engineer, Internship" (Dec 2021-May 2022) with skills "Selenium, Java". CV says Selenium + **Python**. Use one tool stack.
   - Prodeck: CV says "Operations Management Intern, 03/2023-09/2023"; LinkedIn says "**Automation Test Analyst**" using **Playwright**. This is a big gap. If the LinkedIn version is true, put Playwright on the CV (it's a strong keyword). If the CV is true, correct LinkedIn.
   - LinkedIn lists a "Deli Assistant, Applegreen" role (Sep 2025-Jun 2026) that isn't on the CV. That's fine to keep, but shorten it to one line.
4. **Skills section:** 28 skills, but the top two pinned are "UI Testing" and "Quality Assurance". Pin the top 3 as: Test Automation, Selenium WebDriver, Python. Add the others in section 5.
5. Turn on **Open to Work → Job titles: Automation Test Engineer, QA Automation Engineer, Software Test Engineer, SDET (junior), Business Analyst, Data Analyst; Location: Dublin / Ireland / Remote**.

## 1. Headline (220 characters max)
**Option A (recommended):**
`Automation Test Engineer | Selenium · Python · SQL · Playwright | MSc Management (DCU) | Business & Data Analyst skills | Dublin | Stamp 1G, no sponsorship needed`

**Option B (shorter):**
`Automation Test Engineer | Selenium · Python · SQL | I turn requirements into reliable, automated tests | Open to work in Dublin`

(Remove "Playwright" from the headline if it isn't true for you; see item 3.)

## 2. About section
> I'm an Automation Test Engineer who enjoys finding problems before users do, and then building the automated checks that stop them coming back.
>
> I started my career at Cognizant, where I wrote and ran 50+ automated test cases with Selenium WebDriver and Python, logged and tracked defects to closure (90%+ resolved within SLA), and rebuilt a company portal's clock functions to cut related downtime by 15%. I still enjoy that loop: read the requirement, find how it could break, automate the check, and report it clearly.
>
> I also bring an analyst's mindset. My MSc in Management (Business) from Dublin City University and my practicum on renewable-energy market feasibility trained me to gather requirements, analyse data, and present findings to non-technical stakeholders. That is a useful skill in QA, because the best tests come from understanding what the business actually needs.
>
> Recently I identified a problem in the field at Flogas / SCL Sales (agents spent most of each visit explaining tariffs), gathered requirements, built an Android prototype in Kotlin and wrote a costed proposal for it. I like owning a problem end to end.
>
> **What I work with:** Selenium WebDriver · Python · SQL · Playwright · Test case design · Functional / UI / UAT testing · Defect management · Requirements analysis · Process mapping · Tableau · Advanced Excel
>
> **What I'm looking for:** Automation Test Engineer / QA Automation roles in Dublin (also open to Business or Data Analyst roles). I have Stamp 1G Graduate permission, full-time and unrestricted, with no sponsorship required to start.
>
> 📩 priyanshu.gawlikar@gmail.com

(Check the "Flogas / SCL Sales" details and the Playwright mention against what you're happy to say publicly.)

## 3. Experience (rewrite the top entries)

**Automation Test Engineer, Cognizant Technology Solutions (Jan-Jun 2022)**
- Developed and executed 50+ automated test cases with Selenium WebDriver and Python to validate web application functionality and performance against documented requirements.
- Logged, triaged and tracked defects through to closure; achieved 90%+ resolution within SLA and reported status to the QA lead.
- Rebuilt and optimised the company portal's clock functions, reducing related system downtime by 15%.
- Skills: Selenium WebDriver · Python · Test automation · Defect management · Regression testing

**Automation Test Analyst, Prodeck Group (Mar-Sep 2023)** *(only if accurate; see item 3)*
- Analysed software requirements to design detailed test cases and scenarios; turned them into automated functional and UI tests (Playwright).
- Identified, documented and tracked defects, and worked with cross-functional teams to streamline operational workflows.
- Skills: Playwright · Test case design · Functional testing · UI testing

**Operations Management Associate, Nodal Defender Services (Feb-Oct 2024)**
- Planned deployments across 10+ sites and maintained audit-ready documentation against client SLAs.
- Analysed resource utilisation in Excel and changed scheduling to cut overtime costs by 15%.

**Energy Advisor, SCL Sales / Flogas (Jun-Aug 2026)**
- Gathered requirements from field agents, built an Android (Kotlin) prototype and produced a costed implementation proposal (hosting, timeline, resourcing).
- Handle high daily client volumes, explaining complex tariffs in plain language while meeting conversion targets.

**Applegreen, Deli Assistant:** keep as one line, or hide from the top of the profile if you want QA roles to be the first thing seen.

## 4. Education and the analyst angle
**Dublin City University: MSc in Management (Business), Jan 2025-Jan 2026**
- Activities and societies / description:
  > Coursework in data analysis, consulting and business strategy. Practicum: *Blue Economy Growth Strategies*, a feasibility analysis of the renewable-energy market (research, data analysis, structured recommendations to a client). Built requirements-gathering, stakeholder-reporting and problem-structuring skills that I apply to test strategy and analysis.
- Skills tagged: Data Analysis · Consulting · Business Analysis · Research

(Your practicum post says "Alpha Innovation"; mention the host organisation by name in the description if you are allowed to.)

**G.H. Raisoni College of Engineering, Nagpur: BE Electronics & Telecommunication, 2018-2022** (keep as is).

## 5. Skills to add/reorder (aim for 30+, pin the first 3)
1. Test Automation 2. Selenium WebDriver 3. Python
Then: Playwright · SQL · Manual Testing · Functional Testing · Regression Testing · UI Testing · Test Case Design · Defect Tracking · Quality Assurance · Agile · JIRA (only if used) · Git (only if used) · API Testing (only if used) · Requirements Gathering · Business Analysis · Data Analysis · Process Improvement · Stakeholder Management · Tableau · Microsoft Excel · Kotlin · JavaScript

Then ask 3-5 former colleagues/classmates to endorse the top 3.

## 6. Projects (Featured section)
- **Test automation sample project (recommended, create this on GitHub):** a Selenium + Python (pytest) framework with Page Object Model, run against a public demo site (e.g. saucedemo.com), with an HTML report and a GitHub Actions run. A recruiter can open it and see your skills in 30 seconds. This repository (`qa-automation-j`) is a good home for it; tell me and I'll scaffold it.
- Field sales pricing app (Android/Kotlin)
- Zira Voice Assistant (Python NLP)
- House Price Predictor (Python regression)
- Blue Economy Growth Strategies (DCU practicum)

## 7. Recommendation and activity
- You have one strong recommendation (Chetan S Jambhulkar, Apr 2026). Ask one more from a QA lead or manager at Cognizant.
- Post 1-2 times a month: a short note about a testing lesson or your sample project. Your graduation post got 3,000+ impressions, so your network does respond.
- Follow QA/automation companies and hiring managers in Dublin (you currently follow Hays and PetSafe Brands).

## 8. Quick checklist
- [ ] Upload banner · [ ] New headline · [ ] New About · [ ] Fix Cognizant/Prodeck titles · [ ] Pin top 3 skills · [ ] Open to Work titles · [ ] Add GitHub project to Featured · [ ] Ask for a second recommendation
