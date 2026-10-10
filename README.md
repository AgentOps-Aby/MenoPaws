# MenoPaws

**Turning menopause stories into evidence.**

MenoPaws is a guided storytelling app for women in perimenopause and menopause. Paws, a friendly cat guide, helps a woman tell her story in her own words. She leaves with a summary to bring to her doctor and a personal self-care toolkit. If she chooses, a de-identified version of her story joins an open research dataset with a patterns dashboard.

Built at **Build For Her**, SF Tech Week 2026.

![MenoPaws home](docs/screenshots/01-home.png)

## The problem

Women in the menopause transition are often told their symptoms are "just stress." Their experiences rarely become evidence: most menopause data comes from company-owned apps, one brand of smartwatch, or clinic patients, and women get little back for sharing.

## What it does

| Step | What she gets |
|---|---|
| **Learn** | A plain-language, step-by-step intro to perimenopause and menopause: hormones, timing, symptoms and when to see a clinician |
| **Prepare** | Evidence-based habits for bones, heart, hot flashes and sleep, pelvic health and mood, collected into her own plan |
| **Tell your story** | A guided chat with Paws: her story in her own words, plus quick-tap questions on symptoms, pregnancy history, health background, daily life and wellbeing. A live panel shows her story turning into structured data. |
| **Your summary** | An editable doctor summary with "things to consider together" (for example, short sleep or a thyroid condition that can mimic menopause symptoms), questions to ask, and a personal toolkit with helplines |
| **Patterns** | An open dataset dashboard: world map, symptoms by age, ethnic background with subgroups, pregnancy history, sleep and symptoms, and more |
| **Discussion** | "Paws Goss," a doctor-moderated community with a path to direct-pay doctors |
| **Resources** | Vetted organizations, care platforms, tracking apps, helplines and research studies |
| **Profile** | A demo account showing symptom check-ins, appointment prep, a self-advocacy timeline and research consent settings |

| | |
|---|---|
| ![Story chat](docs/screenshots/02-story-chat.png) | ![Doctor summary](docs/screenshots/03-summary.png) |
| ![Patterns dashboard](docs/screenshots/04-patterns.png) | ![Learn](docs/screenshots/05-learn.png) |

## Privacy and safety by design

- **Private by default.** Her doctor summary stays with her. Nothing is shared until she switches it on.
- **Layered consent.** Separate switches for her answers, her own words (de-identified), background details (ethnicity, pregnancy history, health and daily life) and study invitations. She sees the exact record researchers would receive.
- **De-identification.** Names, places, dates and other identifying details are removed before anything joins the dataset. Location is shared at country level only.
- **Never shared.** Wellbeing and safety answers, medication names, and name, email and city.
- **No one singled out.** A group appears on the dashboard only when at least 10 women share it. Smaller groups are combined.
- **Immediate support.** If she reports frequent low mood or not feeling safe at home, Paws shows the 988 Suicide & Crisis Lifeline or the National Domestic Violence Hotline right away.
- **Not a diagnosis.** MenoPaws helps her ask; her clinician answers.

## Run it

No build step and no dependencies. Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works). Fonts load from Google Fonts, so an internet connection gives the intended look.

```
menopaws/
├── index.html                  # the whole app: HTML, CSS and JavaScript in one file
├── assets/paws-character.svg   # original Paws character art
└── docs/screenshots/           # screenshots used in this README
```

To publish with GitHub Pages: push this folder to a repository, then go to **Settings → Pages** and deploy from the main branch.

## What's mocked in this prototype

- The patterns dashboard uses **1,247 synthetic stories** generated in the browser. They are not real people.
- Discussion posts, doctor profiles, prices and the demo account ("Maya") are **examples**.
- **Nothing is stored or sent.** Answers live only in the open browser tab and disappear on refresh. Login does not create an account.

## Survey design notes

- Ethnicity follows the 2024 US federal race and ethnicity standard (SPD 15), with optional subgroups, because menopause timing and symptoms differ within groups.
- Question domains map to those of validated menopause instruments such as the Women's Health Questionnaire. A future version would add a validated scale, such as the Menopause Rating Scale, so the data is comparable with existing research.
- Questions were reviewed with a family medicine physician on the team.

## Next steps

- A university research partner, with ethics review
- A moderated community to learn and speak up together
- Return visits to track change over time
- Spanish-language support
- Secure storage and a real consent and withdrawal workflow

## Team

- **Cristina Cojocaru**, family medicine physician
- **Apoorva Patil**, senior product manager
- **Vanessa Lew**, cybersecurity, communications and technology leader
- **Esha Menon**, business development and marketing, Mission Minded
- **Sonia Tiwari**, character designer and education researcher, creator of Paws

## Key sources

- 2025 Perimenopause Focus survey of 1,005 US working women ages 30 to 60, reported in *Patient Care* (Nov 2025)
- Faubion et al., "Impact of menopause symptoms on women in the workplace," *Mayo Clinic Proceedings*, 2023
- Study of Women's Health Across the Nation (SWAN)
- National Institute on Aging; The Menopause Society; NHS; Bone Health & Osteoporosis Foundation
- US Office of Management and Budget, SPD 15 race and ethnicity standards (2024)

*General information only, not medical advice.*
