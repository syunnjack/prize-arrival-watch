# Prize Arrival Watch

プライズ景品の入荷・在庫通知

## Repository

Recommended repository name: `prize-arrival-watch`

## Domain candidates

First candidate: `prizearrival.jp`

Other candidates:

- `prizearrival.jp`
- `prizewatch.jp`
- `charanyuka.jp`
- `getalert.jp`

## Concept

景品名、キャラ名、店舗名で入荷、在庫、再入荷を通知し、ゲームセンター掲載とEC送客へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 入荷通知課金
- 店舗掲載課金
- ECアフィリエイト
- 景品スポンサー
- 動画広告

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
