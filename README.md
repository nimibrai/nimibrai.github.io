# Oshioma Brai | Portfolio

Personal portfolio site for Oshioma Brai, a Mathematics and Computer Science graduate (University of Birmingham) working in data analysis, automation and machine learning.

**Live site:** https://nimibrai.github.io

## About this site

A single-page portfolio built with plain HTML and CSS. It covers:

- **Projects:** including an open-source LLaMA fine-tune on Nigerian proverbs, and a research report on prime numbers and the Riemann Hypothesis
- **Experience:** banking operations, quantitative research and data analytics
- **Skills:** Python, SQL, Power BI, Excel, Git and machine learning

It has no build step and no dependencies, apart from two Google Fonts loaded from the web. It switches between light and dark themes to match the visitor's system setting, and it works on mobile.

## Featured project

[Nigeria-Proverbs-LLM](https://github.com/nimibrai/Nigeria-Proverbs-LLM): a LoRA fine-tune of a LLaMA model on Yoruba, Igbo and Hausa proverbs, with a Gradio demo. I first built this in 2024 and rebuilt it in 2026 after the original files were lost.

## Run it locally

```bash
git clone https://github.com/nimibrai/nimibrai.github.io.git
cd nimibrai.github.io
open index.html
```

On Windows, use `start index.html`. On Linux, use `xdg-open index.html`.

## Update and deploy

The site is hosted with GitHub Pages from the `main` branch. After editing `index.html`:

```bash
git add .
git commit -m "Update site"
git push
```

Changes go live within a couple of minutes.

## Contact

- Email: braioshioma@gmail.com
- LinkedIn: [linkedin.com/in/oshioma-brai](https://linkedin.com/in/oshioma-brai)
- GitHub: [@nimibrai](https://github.com/nimibrai)
