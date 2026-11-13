### Hi, I'm Mert 👋

**Senior Software Engineer** in **Ottawa** who builds things people use every day: full-stack web apps, mobile apps, data pipelines and AI automation. My thesis at the **University of Ottawa** was on machine learning for social media geolocation.

I also run a real-estate practice, and most of my recent work is the software behind it: production systems with real users, real data and real money moving through them.

#### 🔭 Featured

- **[LeaseLens](https://github.com/mertmetin/leaselens) · [try it live ↗](https://mertmetin.github.io/leaselens/):** paste an Ontario lease and see which clauses the Residential Tenancies Act makes void, each explained in plain English with the exact section of the law (verified against the official statute). 26 rules, 136 tests, and fully private: it runs in your browser and the page is blocked from making any network request. TypeScript, Vite, GitHub Pages.
- **[RESO IDX](https://github.com/mertmetin/reso-idx) · [try it live ↗](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/mertmetin/reso-idx/main/blueprint.json):** a WordPress plugin that syncs MLS® listings from any RESO Web API feed and shows them with a search block, a map and SEO-friendly listing pages, with the board's IDX display rules built in. Incremental keyset sync with retries and a safety guard against broken feeds; tested against a live Ontario feed (about 3,400 Ottawa listings with photos in three minutes). 52 tests, PHPStan, WordPress coding standards, and an end-to-end test in WordPress Playground on every push. PHP 8.1+, no build step.
- **[Geolocation-Prediction](https://github.com/mertmetin/Geolocation-Prediction):** my uOttawa thesis, rebuilt in 2026. Predicts where Canadian Twitter users live from their tweets (61% within 161 km) and their social graph (88%). I found and fixed 7 bugs in the original research code, moved it to a stricter evaluation, and added a web demo with a map.
- **[searchbench](https://github.com/mertmetin/searchbench):** my 2014 Django + Elasticsearch product search, rebuilt as an evaluated search engine. Keyword, semantic and hybrid retrieval scored on 480 human-labelled queries: hybrid search improves NDCG@10 from 0.706 to 0.772. FastAPI web app with facets and a 2014 vs 2026 side-by-side view.
- **Rabbit: grocery delivery in Ottawa.** A full delivery platform I built end to end: [backend](https://github.com/mertmetin/rabbit-server) (Next.js + Prisma API and admin dashboard on AWS ECS, Stripe authorise-then-charge payments, 107 tests, OIDC deploys), [customer app](https://github.com/mertmetin/rabbit-app) (React Native/Expo, live store status, order tracking) and [driver app](https://github.com/mertmetin/rabbit-driver) (shopping list, spoken turn-by-turn navigation, photo hand-off). It started in 2020 as a [Laravel API](https://github.com/mertmetin/rabbit-api).
- **[mertmetin.dev](https://github.com/mertmetin/mertmetin.dev):** my personal site in Ruby on Rails 8. A working terminal in the hero, two browser games, and an AI lab where a Deep Q-Network I wrote from scratch (backprop, Adam, experience replay) learns to play one of them: 73 points on average vs 18.8 for a Q-table. Plus a writing section, and browser tests in CI.
- **[flask-microblog](https://github.com/mertmetin/flask-microblog):** my unfinished 2014 Flask blog, finished in 2026. Hashed passwords, CSRF, sanitised Markdown, comments with an explainable spam filter and moderation queue, and related posts and search from a from-scratch TF-IDF index.

#### 🏗️ Built and running in production (private repos)

- **Real-estate IDX platform:** WordPress + custom PHP listing search, synced with the PropTx MLS data feed, with saved searches, email alerts and a client account area. A general version of its listing sync and search is public as [RESO IDX](https://github.com/mertmetin/reso-idx).
- **Market report engine:** Python pipeline producing monthly neighbourhood reports, delivered behind registration and login to meet MLS data rules.
- **Offer writer:** turns an MLS listing into a pre-filled Ontario purchase agreement package, downloadable as a PDF.
- **Rental application portal:** secure applicant login, document upload and credit-check workflow.
- **Twilio dialer and CRM automations:** a browser-based calling tool and Follow Up Boss integrations that run scheduled client reports.
- **AI agents in daily use:** Claude-based skills and scheduled routines that write market posts, newsletters and listing shortlists from live data.

#### 🧰 Tools I use

`Python` · `TypeScript` · `Ruby` · `PHP` · `React` / `React Native` · `Next.js` · `Rails` · `WordPress` · `Flask` · `FastAPI` · `Prisma` · `MySQL` · `scikit-learn` · `pandas` · `LLM APIs (Claude)` · `Stripe` · `Twilio` · `Docker` · `GitHub Actions`

#### 📫 Get in touch

- Open to **software engineering** and **ML / AI engineering** roles in Ottawa or remote.
