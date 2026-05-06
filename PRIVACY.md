# Privacy Policy — Codigo Executivo Analytics

**Last updated:** 2026-05-05

This Privacy Policy describes the data practices of "Codigo Executivo Analytics" (the "App"), an internal analytics tool operated by André Kimura for the sole purpose of monitoring the performance of his own social media content on the @codigoexecutivo accounts (YouTube, Instagram, TikTok).

## 1. Data we access

The App is authorized to access, via the official APIs of YouTube, Instagram, and TikTok, only data belonging to accounts owned by the operator. This includes:

- Public profile information of the connected account (username, follower count, profile photo)
- Statistics of videos and posts published by the connected account (views, likes, comments, shares, saves, watch time, reach, retention)
- Metadata of those videos and posts (title, description, publication date, URL, duration)

The App does not access data of third-party users, followers, or any account other than those of the operator.

## 2. How we use the data

The data is used exclusively to:

- Generate private HTML dashboards stored locally on the operator's machine
- Identify performance trends across platforms
- Inform content strategy decisions

The data is never displayed publicly, shared with third parties, used for advertising, or sold.

## 3. Data storage and retention

- Data is stored locally on the operator's machine in JSON files inside `assets/metricas/`
- No data is transmitted to any external server, database, or cloud service operated by the App
- Data is retained at the operator's discretion and may be deleted at any time by removing the local files

## 4. Third-party services

The App communicates only with the official APIs of YouTube (Google), Instagram (Meta), and TikTok (ByteDance) to retrieve the operator's own data. No data is sent to other third parties.

## 5. Security

API access tokens are stored in a local `.env` file that is excluded from version control via `.gitignore`. Tokens are not logged, transmitted, or shared.

## 6. User rights

Since the App processes only the operator's own data, no third-party user has data within the App. The operator may revoke API access at any time via the respective platform's developer console.

## 7. Changes to this policy

This policy may be updated at any time. Changes will be reflected by updating the "Last updated" date above.

## 8. Contact

For any questions about this Privacy Policy, contact: amkimura2011@gmail.com
