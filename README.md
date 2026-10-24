# Free weekly datasets: YouTube trends, channel stats, SSL certificates

Updated **2026-10-24** (weekly). Open data in CSV and JSON under [`data/`](data/), produced with low-cost pay-per-result [Apify](https://apify.com) Actors. Only factual metadata (titles, counts, dates, certificate status); no comments, transcripts or personal data. Free to use with attribution (CC BY 4.0).

## YouTube: most viewed videos uploaded this week, by topic

| Topic | Title | Channel | Views | Published |
|---|---|---|---|---|
| iPhone | iPhone Duo Review: First Generation Fun! | Marques Brownlee | 10,574,484 | 2026-10-21 |
| iPhone | iPhone Duo is Messier Than You Think | Mrwhosetheboss | 8,022,311 | 2026-10-21 |
| iPhone | iPhone Duo Review: After 3,000 Folds, Here’s What We Found | HTX Studio | 3,600,229 | 2026-10-21 |
| Formula 1 | Enfrentamos Al Dueño De La S1000RR Utilizando Un Formula1 | RDjavi | 2,485,906 | 2026-10-17 |
| iPhone | BUYING THE NEW iPHONE DUO! | IShowSpeed | 2,245,264 | 2026-10-23 |
| personal finance | Who the FAQ is Albert? / Albert Commercial | Albert | 2,090,518 | 2026-10-21 |
| Formula 1 | Team Verstappen Racing at GT World Challenge Europe Finale / LIVE | Red Bull Motorsports | 2,080,960 | 2026-10-17 |
| iPhone | iPhone Duo Durability: Destroyed | JerryRigEverything | 1,953,396 | 2026-10-23 |
| artificial intelligence | Did Google just dethrone OpenAI and Anthropic? | Fireship | 1,826,561 | 2026-10-20 |
| Formula 1 | FP1 Highlights / 2026 United States Grand Prix | FORMULA 1 | 1,799,580 | 2026-10-23 |

Full data: [`data/youtube_trending_by_topic.csv`](data/youtube_trending_by_topic.csv) · [`.json`](data/youtube_trending_by_topic.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## YouTube: tech & science channel leaderboard

| Channel | Subscribers | Videos | Total views |
|---|---|---|---|
| TED | 27,900,000 | 5867 | 3,262,671,309 |
| Kurzgesagt – In a Nutshell | 25,700,000 | 394 | 3,969,525,522 |
| Marques Brownlee | 21,400,000 | 1861 | 5,822,734,699 |
| Veritasium | 21,400,000 | 543 | 4,689,286,756 |
| Apple | 21,100,000 | 222 | 1,165,743,225 |
| Linus Tech Tips | 16,900,000 | 7964 | 9,934,332,016 |
| 3Blue1Brown | 8,720,000 | 246 | 788,183,470 |
| Fireship | 4,310,000 | 857 | 787,094,178 |
| Google for Developers | 2,680,000 | 6120 | 366,512,479 |
| NVIDIA | 2,250,000 | 2776 | 631,504,804 |
| OpenAI | 2,100,000 | 880 | 279,613,527 |
| Two Minute Papers | 1,840,000 | 1104 | 172,979,318 |

Full data: [`data/youtube_channel_leaderboard.csv`](data/youtube_channel_leaderboard.csv) · [`.json`](data/youtube_channel_leaderboard.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## SSL certificates of 50 popular websites (soonest expiry first)

| host | daysLeft | validTo | issuerOrg | tlsVersion |
|---|---|---|---|---|
| facebook.com | 7 | 2026-10-31T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| instagram.com | 7 | 2026-10-31T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| whatsapp.com | 7 | 2026-10-31T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| paypal.com | 32 | 2026-11-25T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| bol.com | 35 | 2026-11-28T09:56:27+00:00 | Let's Encrypt | TLSv1.3 |
| github.com | 36 | 2026-11-29T23:59:59+00:00 | Sectigo Limited | TLSv1.3 |
| tiktok.com | 40 | 2026-12-03T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| aliexpress.com | 40 | 2026-12-03T11:16:15+00:00 | GlobalSign nv-sa | TLSv1.2 |
| medium.com | 41 | 2026-12-04T21:48:00+00:00 | Google Trust Services | TLSv1.3 |
| cloudflare.com | 41 | 2026-12-04T23:29:33+00:00 | Google Trust Services | TLSv1.3 |
| openai.com | 51 | 2026-12-15T05:59:47+00:00 | Google Trust Services | TLSv1.3 |
| google.com | 58 | 2026-12-21T18:38:32+00:00 | Google Trust Services | TLSv1.3 |
| youtube.com | 58 | 2026-12-21T18:38:32+00:00 | Google Trust Services | TLSv1.3 |
| apple.com | 60 | 2026-12-23T19:10:23+00:00 | Apple Inc. | TLSv1.3 |
| x.com | 64 | 2026-12-27T20:09:53+00:00 | Let's Encrypt | TLSv1.3 |

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
