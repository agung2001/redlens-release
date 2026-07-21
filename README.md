# RedLens 👁️✨

**A premium, high-contrast visual intelligence dashboard for modern content creators to audit YouTube video catalogs and extract viral insights.**

RedLens ingests your YouTube Studio CSV exports and performs deep, granular content intelligence audits — bridging the gap between raw data and actionable creative decisions. It reveals precisely how show format, upload timing, video length, title psychology, and guests impact your channel's performance.

---

## 🚀 Key Features

* **Channel Health Overview:** Tracks aggregate metrics — total views, average performance, upload frequency — with interactive high-performance trendline charts.
* **Post-Time Optimization:** Analyzes upload patterns by day and hour to identify your prime publishing window.
* **Duration Intelligence:** Groups videos into length brackets (Short-form, Mid-form, Long-form, Podcast) and correlates duration with viewership.
* **Title & Guest Psychology:** Measures UPPERCASE ratio, emoji usage, and title length impact on clicks. Automatically extracts and ranks guests/co-hosts by average views.
* **Virality & Outlier Detection:** Flags videos that performed 2x, 5x, or 10x above your channel median and decodes the exact combinations behind your most viral content.

---

## 📥 How to Download & Install (Windows)

1. Go to the **[Releases](https://github.com/agung2001/redlens-release/releases)** page of this repository.
2. Download the latest installer file (e.g., `redlens_x.x.x_x64-setup.exe` or `.msi`).
3. Run the downloaded file and follow the on-screen instructions to complete the installation.
4. Launch **RedLens** from your Windows Start Menu.

---

## 📋 How to Use

1. **Open the App:** Launch RedLens from your desktop or Start Menu.
2. **Upload Your CSV:** Click the upload button and select your YouTube Studio CSV export file.
3. **Explore the Tabs:** Navigate through Overview, Timing, Duration, Psychology, and Virality tabs to explore your channel's insights.
4. **Optional — YouTube API:** Paste a free YouTube Data API v3 key in the Settings tab to enrich your data with real-time likes, comments, and high-resolution thumbnails.

---

## 📁 CSV Data Format

Export your video catalog from YouTube Studio and upload it directly. The required columns are:

| Column | Type | Description |
|--------|------|-------------|
| `title` | string | Video title |
| `total_views` | integer | Lifetime view count |
| `duration` | string | Length in `HH:MM:SS` or `MM:SS` |
| `published_date` | string | ISO date (e.g. `2026-05-20T17:00:00Z`) |

Optional but recommended: `thumbnail` (URL), `url` (YouTube link).
