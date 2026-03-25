 **complete step-by-step process from scratch** 

---

## STEP 1 — Django Forum (Already on correct page)
 ![image alt](https://github.com/Manjunatha-kv01/Django/blob/4654df4ea5da84f5bbd1e7c9c31eaaa57096fb60/WhatsApp%20Image%202026-03-25%20at%2011.51.43%20AM.jpeg)
1. Click **Create Topic**
2. Fill details:

Title box:
GSoC 2026 Aspirant – Interested in Contributing to Django

Body (paste your content as-is)

3. Select category:
   Google Season of Code (or Mentorship)

4. Click **Create Topic**

---

## STEP 2 — Immediately After Posting

Do these 3 actions:

1. Open 2–3 existing GSoC threads
2. Click **Reply**
3. Post this:

Hi, I am also interested in this project and currently exploring Playwright and Django testing. Could you guide me on how to begin contributing?

---

## STEP 3 — Go to Django GitHub

1. Open Django repository

2. Click **Issues**

3. Search:
   playwright OR selenium OR testing

4. Open one issue (like you already did)

---

## STEP 4 — Interact on GitHub Issue

1. Click **Subscribe** (right side)
2. Scroll down
3. Click **Leave a comment**
4. Paste:

Hi, I am interested in contributing to this Playwright integration testing project for GSoC 2026.

I have experience with Python and Django and am currently learning Playwright.

Could you guide me on where to start and any beginner-friendly tasks?

5. Click **Comment**

---

## STEP 5 — Setup Django Project Locally

Open terminal:

```
git clone https://github.com/django/django.git
cd django
```

If `python` not working → use `python3`

```
python3 -m venv venv
source venv/bin/activate
pip install -e .
```

---

## STEP 6 — Install Playwright

```
pip install playwright
playwright install
```

---

## STEP 7 — Run Django Tests

```
python tests/runtests.py
```

This helps you understand project structure.

---

## STEP 8 — Find Your Starting Point

Search inside project:

* selenium
* LiveServerTestCase

These are the tests you will convert.

---

## STEP 9 — First Contribution (IMPORTANT)

Do NOT try big changes.

Start with ONE small task:

Option 1:
Convert 1 Selenium test → Playwright

Option 2:
Write 1 new Playwright test

---

## STEP 10 — Create Branch

```
git checkout -b playwright-test-setup
```

---

## STEP 11 — Push Code

```
git add .
git commit -m "Add initial Playwright test"
git push origin playwright-test-setup
```

---

## STEP 12 — Create Pull Request

1. Go to GitHub
2. Click **Compare & Pull Request**
3. Submit PR

---

## YOUR DAILY PLAN (Follow this)

Day 1:
Forum post + GitHub comment

Day 2:
Learn Playwright basics

Day 3–5:
Run Django tests + explore code

Day 6–7:
Submit first PR

---

## FINAL STRATEGY (MOST IMPORTANT)

* Don’t wait for mentors
* Start contributing immediately
* Small PR > no PR

---

This entire flow is exactly what you need for GSoC Django contribution 

---

If you want next:
I can give you **exact first test file + Playwright code to write your first PR**.
