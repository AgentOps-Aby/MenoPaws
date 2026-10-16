# MenoPaws

**Turning menopause stories into research data, self-advocacy and guided community.**

MenoPaws is a place for education, self-advocacy and community building around perimenopause and menopause. Paws, a friendly menopausal cat in a pink beret, guides each woman through her story in her own words. She leaves with an editable summary to bring to her doctor and a personal toolkit. If she chooses, a de-identified version of her story joins an open research dataset with a patterns dashboard.

Built in one day at **Build For Her**, a women's health hackathon during SF Tech Week 2026.

**Project page and design notes:** [okipie.com/lab/menopaws](https://www.okipie.com/lab/menopaws)

## The problem

Women in the menopause transition are often told their symptoms are "just stress." Their experiences rarely become evidence: most menopause data comes from company-owned apps or clinic patients, and women get little back for sharing.

## What it does

1. **Welcome** - Why MenoPaws exists, the pain points women recognize, and one clear "Start my story" button.
2. **Learn** - A plain-language, step-by-step intro to perimenopause and menopause.
3. **Prepare** - Evidence-based habits for bones, heart, hot flashes and sleep, pelvic health and mood, collected into her own plan.
4. **Tell your story** - A guided chat with Paws: her story in her own words, then quick questions on symptoms, pregnancy history, health background, daily life and wellbeing. A live panel shows her story turning into structured data.
5. **Your summary** - An editable doctor summary with "things to consider together," questions to ask, a personal toolkit and helplines.
6. **Patterns** - An open dataset dashboard: world map, symptoms by age, ethnic background with subgroups, pregnancy history, sleep and more.

Also: **Discussion** ("Paws Goss," a doctor-moderated community), **Resources** (vetted organizations, care platforms, apps, helplines and studies), **About us**, and a demo **Log in / Profile**.

## Meet Paws

Paws reacts to what she hears: she talks with an opening mouth, flushes during a hot flash, gets sleepy, foggy or shivery when those symptoms are picked, and pops her beret when clicked. On the homepage her eyes follow the cursor, and when the page loads she does a joyful jump that releases a burst of hearts on landing.

## Privacy and safety by design

- **Private by default.** Her doctor summary stays with her. Nothing is shared until she switches it on.
- **Layered consent.** Separate switches for her answers, her own words (de-identified), background details and study invitations. She sees the exact record researchers would receive.
- **De-identification.** Names, places, dates and identifying details are removed before anything joins the dataset.
- **Never shared.** Wellbeing and safety answers, medication names, and name, email and city.
- **No one singled out.** A group appears on the dashboard only when at least 10 women share it.
- **Immediate support.** Reporting low mood or feeling unsafe at home shows the 988 Suicide & Crisis Lifeline or the National Domestic Violence Hotline right away.
- **Not a diagnosis.** MenoPaws helps her ask; her clinician answers.

## Run it

No build step and no dependencies. Open `index.html` in a browser, or serve the folder with any static host. Fonts load from Google Fonts, so an internet connection gives the intended look.

To publish with GitHub Pages: push this folder to a repository, then go to **Settings → Pages** and deploy from the main branch.

```
menopaws/
├── index.html                    # the whole app: HTML, CSS and JavaScript in one file
└── assets/
    ├── paws-character.svg        # original Paws character art
    ├── paws-eyes-closed.svg      # closed-eye pose
    ├── paws-mouth-resting.svg    # resting mouth
    ├── paws-mouth-talking.svg    # open, talking mouth
    ├── menopaws-poster.png       # 9:16 announcement poster
    └── logo/                     # primary, stacked, reverse and icon logos
```

## What's mocked in this prototype

- The patterns dashboard uses **1,247 synthetic stories** generated in the browser. They are not real people.
- Discussion posts, doctor profiles and the demo account ("Maya") are **examples**.
- **Nothing is stored or sent.** Answers live only in the open browser tab and disappear on refresh. Login does not create an account.

## Next steps

- A university research partner, with ethics review
- A moderated community to learn and speak up together
- Return visits to track change over time
- Spanish-language support
- Secure storage and a real consent and withdrawal workflow

## Team

- **Cristina Cojocaru** - Provided medical expertise for the narrative survey.
- **Apoorva Patil** - Led product management towards final deliverables.
- **Vanessa Lew** - Shared menopause experience for product honesty.
- **Esha Menon** - Contributed group leadership and user testing.
- **Sonia Tiwari** - Designed the character and user experience.
- **Paws** - Kept us cutely motivated.
- **Claude** - Supported vibe coding.

## Key sources

- 2025 Perimenopause Focus survey of US working women ages 30 to 60, reported in *Patient Care* (Nov 2025)
- Faubion et al., "Impact of menopause symptoms on women in the workplace," *Mayo Clinic Proceedings*, 2023
- Kling et al., menopause training survey of residents, *Mayo Clinic Proceedings*, 2019
- Avis et al., Study of Women's Health Across the Nation (SWAN), *JAMA Internal Medicine*, 2015
- US Office of Management and Budget, SPD 15 race and ethnicity standards (2024)

*General information only, not medical advice.*
