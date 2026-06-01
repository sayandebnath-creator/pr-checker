# Canada PR Eligibility Checker

A simple, responsive web widget that estimates basic eligibility for Canada Permanent Residency (PR) based on key factors.

[Web Ui](./ui.png)

## Features

- Three input parameters:
  - Age
  - Education Level
  - English Proficiency (IELTS)
- Instant eligibility feedback
- Mobile-responsive design
- Lightweight and embeddable (compatible with Elementor Custom HTML)

## Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)

## How It Works

Each input contributes to a basic score:
- Higher values (younger age, higher education, better English) increase the score
- The total score determines eligibility category:
  - High eligibility
  - Moderate eligibility
  - Low eligibility

This is a simplified estimation and not an official CRS calculation.

## Usage

1. Open the live link or `index.html`
2. Select values for all three fields
3. Click "Check Eligibility"
4. View the result instantly

## Deployment

This project is deployed using GitHub Pages.

To deploy manually:
1. Create a repository
2. Add `index.html`
3. Go to Settings → Pages
4. Select branch `main` and root folder
5. Save and access the generated URL

## Note

This tool is for demonstration purposes only and should not be used as an official immigration assessment.
