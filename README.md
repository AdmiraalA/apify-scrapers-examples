# Free weekly datasets: YouTube trends, channel stats, SSL certificates

Updated **2026-10-26** (weekly). Open data in CSV and JSON under [`data/`](data/), produced with low-cost pay-per-result [Apify](https://apify.com) Actors. Only factual metadata (titles, counts, dates, certificate status); no comments, transcripts or personal data. Free to use with attribution (CC BY 4.0).

## YouTube: most viewed videos uploaded this week, by topic

| Topic | Title | Channel | Views | Published |
|---|---|---|---|---|
| iPhone | iPhone Duo Review: First Generation Fun! | Marques Brownlee | 11,949,171 | 2026-10-21 |
| iPhone | iPhone Duo Durability: Destroyed | JerryRigEverything | 10,175,805 | 2026-10-23 |
| iPhone | iPhone Duo is Messier Than You Think | Mrwhosetheboss | 9,558,448 | 2026-10-21 |
| iPhone | Tanya Aur Maine apna iPhone Change Kiya@MrFaisu | Mr. Faisu | 7,058,969 | 2026-10-25 |
| Formula 1 | Qualifying Highlights / 2026 United States Grand Prix | FORMULA 1 | 5,219,977 | 2026-10-24 |
| iPhone | iPhone Duo Review: After 3,000 Folds, Here’s What We Found | HTX Studio | 4,579,442 | 2026-10-21 |
| Formula 1 | Race Highlights / 2026 United States Grand Prix | FORMULA 1 | 3,002,195 | 2026-10-25 |
| iPhone | 역대급 가격 329만원. 애플 아이폰 듀오 일주일 사용기! | ITSub잇섭 | 2,618,195 | 2026-10-21 |
| iPhone | BUYING THE NEW iPHONE DUO! | IShowSpeed | 2,617,065 | 2026-10-23 |
| Formula 1 | FP1 Highlights / 2026 United States Grand Prix | FORMULA 1 | 2,362,942 | 2026-10-23 |

Full data: [`data/youtube_trending_by_topic.csv`](data/youtube_trending_by_topic.csv) · [`.json`](data/youtube_trending_by_topic.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## YouTube: tech & science channel leaderboard

| Channel | Subscribers | Videos | Total views |
|---|---|---|---|
| TED | 27,900,000 | 5869 | 3,263,718,426 |
| Kurzgesagt – In a Nutshell | 25,800,000 | 395 | 3,973,107,227 |
| Marques Brownlee | 21,400,000 | 1861 | 5,827,538,761 |
| Veritasium | 21,400,000 | 543 | 4,695,846,306 |
| Apple | 21,100,000 | 222 | 1,166,151,695 |
| Linus Tech Tips | 16,900,000 | 7965 | 9,938,181,851 |
| 3Blue1Brown | 8,720,000 | 247 | 788,590,037 |
| Fireship | 4,320,000 | 857 | 789,007,136 |
| Google for Developers | 2,680,000 | 6120 | 367,758,838 |
| NVIDIA | 2,250,000 | 2780 | 640,724,492 |
| OpenAI | 2,100,000 | 880 | 279,830,578 |
| Two Minute Papers | 1,840,000 | 1104 | 172,997,598 |

Full data: [`data/youtube_channel_leaderboard.csv`](data/youtube_channel_leaderboard.csv) · [`.json`](data/youtube_channel_leaderboard.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## SSL certificates of 50 popular websites (soonest expiry first)

| host | daysLeft | validTo | issuerOrg | tlsVersion |
|---|---|---|---|---|
| facebook.com | 7 | 2026-11-02T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| instagram.com | 7 | 2026-11-02T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| whatsapp.com | 7 | 2026-11-02T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| bol.com | 33 | 2026-11-28T09:56:27+00:00 | Let's Encrypt | TLSv1.3 |
| github.com | 34 | 2026-11-29T23:59:59+00:00 | Sectigo Limited | TLSv1.3 |
| tiktok.com | 38 | 2026-12-03T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| aliexpress.com | 38 | 2026-12-03T11:16:15+00:00 | GlobalSign nv-sa | TLSv1.2 |
| medium.com | 39 | 2026-12-04T21:48:00+00:00 | Google Trust Services | TLSv1.3 |
| cloudflare.com | 39 | 2026-12-04T23:29:33+00:00 | Google Trust Services | TLSv1.3 |
| openai.com | 49 | 2026-12-15T05:59:47+00:00 | Google Trust Services | TLSv1.3 |
| google.com | 56 | 2026-12-21T18:38:32+00:00 | Google Trust Services | TLSv1.3 |
| youtube.com | 56 | 2026-12-21T18:38:32+00:00 | Google Trust Services | TLSv1.3 |
| apple.com | 58 | 2026-12-23T19:10:23+00:00 | Apple Inc. | TLSv1.3 |
| x.com | 62 | 2026-12-27T20:09:53+00:00 | Let's Encrypt | TLSv1.3 |
| zoom.us | 64 | 2026-12-29T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |

Full data: [`data/ssl_expiry_popular_sites.csv`](data/ssl_expiry_popular_sites.csv) · [`.json`](data/ssl_expiry_popular_sites.json) · refresh it yourself for any topic: [admirala/ssl-certificate-expiry-checker](https://apify.com/admirala/ssl-certificate-expiry-checker)

## AI image upscaling: before / after (Real-ESRGAN, 4x)

| Before: 160×120 (shown enlarged, pixelated) | After: 640×480, AI-upscaled in 2.2 s |
|---|---|
| ![before](upscaling/before_enlarged.png) | ![after](upscaling/after.png) |

Original input: [`upscaling/before.png`](upscaling/before.png) (crop of Van Gogh, *The Starry Night*, public domain).
Upscale your own images in bulk: [admirala/ai-image-upscaler-realesrgan](https://apify.com/admirala/ai-image-upscaler-realesrgan)
($0.0165 per image).

---
*Disclosure: I build the Apify Actors used to collect this data.*
