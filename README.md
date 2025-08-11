# 📰 WackyFlip-CMS

**Content Management System Integration for Wacky Flip**

`WackyFlip-CMS` powers the **dynamic content updates** across [wackyflip.com](https://wackyflip.com), enabling non-technical team members to update homepage features, event banners, and promotional assets without deploying new code.

---

## 🎯 Features

| Feature                  | Description                                                       |
| ------------------------ | ----------------------------------------------------------------- |
| 🖼 Homepage Hero Control | Easily update the main carousel, banners, and highlight sections  |
| 📅 Event Scheduling      | Schedule promotions, tournaments, and seasonal content in advance |
| 📢 Promo Asset Manager   | Upload, organize, and replace marketing images, videos, and CTAs  |
| 🎨 Theme Variations      | Apply seasonal themes and styling overrides without code changes  |
| 🔍 Preview Mode          | Safely preview edits before publishing live                       |
| 👥 Role-Based Access     | Manage permissions for marketers, designers, and admins           |
| 🌐 Localization Support  | Update content for multiple languages and regions                 |

---

## 🛠 Tech Stack

* **Frontend Framework:** Next.js (React)
* **UI Library:** TailwindCSS or Chakra UI
* **Backend:** Node.js + GraphQL API integration with CMS backend
* **CMS Platform:** Strapi / Contentful / Sanity (configurable)
* **Image Hosting:** Integrated with WackyFlip-CDN for optimized asset delivery

---

## 📁 Repository Structure

```
WackyFlip-CMS/
├── components/
│   ├── HeroBannerEditor.tsx
│   ├── EventScheduler.tsx
│   ├── PromoAssetUploader.tsx
│   └── ThemeSwitcher.tsx
├── pages/
│   ├── index.tsx
│   └── preview.tsx
├── hooks/
├── utils/
├── styles/
├── public/
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/wackyflipgame/WackyFlip-CMS.git
cd WackyFlip-CMS
npm install
```

2. Configure environment variables in `.env.local`:

```
CMS_API_URL=https://cms.wackyflip.com
CMS_ACCESS_TOKEN=your-access-token
```

3. Start the development server:

```bash
npm run dev
```

4. Access the CMS dashboard UI at `http://localhost:3000`

---

## 📬 Contribution Guidelines

* Follow `CONTRIBUTING.md` for branching and commit standards
* Keep CMS API calls optimized to avoid slow load times
* Test changes in **Preview Mode** before merging to production
* Ensure responsiveness and accessibility for all content editing tools

---

## 🔗 Related Repositories

* [`WackyFlip-Landing`](https://github.com/wackyflipgame/WackyFlip-Landing) – Website marketing page where CMS content is displayed
* [`WackyFlip-ContentPipeline`](https://github.com/wackyflipgame/WackyFlip-ContentPipeline) – Asset packaging & publishing system
* [`WackyFlip-CDN`](https://github.com/wackyflipgame/WackyFlip-CDN) – CDN service for fast asset delivery

---

## 📜 License

MIT © 2025 Wacky Flip Studios
