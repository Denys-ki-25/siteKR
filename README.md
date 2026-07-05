# Contrast Landing Page

Курсова робота Яцківа Дениса Руслановича: адаптивний односторінковий сайт за Figma-макетом Contrast.

## Структура проєкту

```text
Yatskiv_Contrast_project/
  index.html
  README.md
  CHANGELOG.md
  decomposition.md
  .nojekyll
  .github/workflows/pages.yml
  assets/
    css/style.css
    js/main.js
    img/
      webinar-stage.png
      ai-preview.png
      engagement-preview.png
      feature-cloud.png
      logos/
      social/
        linkedin.svg
        youtube.svg
        x.svg
        dribbble.svg
```

## Секції сторінки

- `header` - логотип Contrast як зображення, навігація та CTA-кнопки.
- `hero` - головний екран і зображення інтерфейсу вебінару.
- `social-proof` - аватари та SVG-логотипи клієнтів.
- `ai-section` - блок AI-перепакування контенту.
- `engagement` - сценарії утримання аудиторії та окреме preview-зображення.
- `feature-cloud` - мозаїка можливостей одним зображенням `feature-cloud.png`.
- `final-cta` - фінальний заклик до дії.
- `site-footer` - футер із правильними SVG-іконками LinkedIn, YouTube, Twitter та Dribbble.

## GitHub Pages

Сайт статичний і не потребує збірки. Workflow `.github/workflows/pages.yml` публікує вміст кореня репозиторію через GitHub Actions. У налаштуваннях репозиторію потрібно вибрати `Settings -> Pages -> Build and deployment -> Source: GitHub Actions`.
