# Free weekly datasets: YouTube trends, channel stats, SSL certificates

Updated **2026-11-02** (weekly). Open data in CSV and JSON under [`data/`](data/), produced with low-cost pay-per-result [Apify](https://apify.com) Actors. Only factual metadata (titles, counts, dates, certificate status); no comments, transcripts or personal data. Free to use with attribution (CC BY 4.0).

## YouTube: most viewed videos uploaded this week, by topic

| Topic | Title | Channel | Views | Published |
|---|---|---|---|---|
| iPhone | iPhone Duo Teardown – APPLE SHOULD APOLOGIZE | JerryRigEverything | 12,607,613 | 2026-10-26 |
| iPhone | Tanya Ke Liye Book Kiya Uska Favourite iPhone! / @MrFaisu | Mr. Faisu | 6,099,538 | 2026-10-26 |
| Formula 1 | Qualifying Highlights / 2026 Mexico City Grand Prix | FORMULA 1 | 5,448,331 | 2026-10-31 |
| iPhone | Mera iPhone Duo Nikla Expectations Se Alag! Tanya Ka IPhone Superhit!  | Mr. Faisu | 4,516,536 | 2026-10-27 |
| iPhone | iPhone Duo Problem is Getting Worse | penguinz0 | 3,412,664 | 2026-10-27 |
| iPhone | The iPhone Duo Situation is Getting Bad | SAMTIME | 3,169,740 | 2026-10-26 |
| iPhone | SML Movie: Brooklyn Guy's iPhone Duo! | SML | 3,116,770 | 2026-10-28 |
| Formula 1 | Race Highlights / 2026 Mexico City Grand Prix | FORMULA 1 | 2,727,412 | 2026-11-01 |
| artificial intelligence | China's AI Bubble Has Burst. Who Will Pay The Price? / The Palki Sharm | India Global Review | 2,515,708 | 2026-10-27 |
| artificial intelligence | Did the AI bubble just pop? | Fireship | 2,384,165 | 2026-10-28 |

Full data: [`data/youtube_trending_by_topic.csv`](data/youtube_trending_by_topic.csv) · [`.json`](data/youtube_trending_by_topic.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## YouTube: tech & science channel leaderboard

| Channel | Subscribers | Videos | Total views |
|---|---|---|---|
| TED | 27,900,000 | 5877 | 3,269,532,289 |
| Kurzgesagt – In a Nutshell | 25,800,000 | 397 | 3,993,432,523 |
| Marques Brownlee | 21,400,000 | 1863 | 5,857,906,431 |
| Veritasium | 21,400,000 | 545 | 4,713,162,480 |
| Apple | 21,100,000 | 228 | 1,231,119,072 |
| Linus Tech Tips | 16,900,000 | 7973 | 9,958,303,372 |
| 3Blue1Brown | 8,730,000 | 247 | 791,053,863 |
| Fireship | 4,320,000 | 859 | 795,938,386 |
| Google for Developers | 2,680,000 | 6125 | 372,693,372 |
| NVIDIA | 2,260,000 | 2791 | 657,695,713 |
| OpenAI | 2,100,000 | 910 | 287,980,163 |
| Two Minute Papers | 1,840,000 | 1106 | 173,687,593 |

Full data: [`data/youtube_channel_leaderboard.csv`](data/youtube_channel_leaderboard.csv) · [`.json`](data/youtube_channel_leaderboard.json) · refresh it yourself for any topic: [admirala/youtube-scraper](https://apify.com/admirala/youtube-scraper)

## SSL certificates of 50 popular websites (soonest expiry first)

| host | daysLeft | validTo | issuerOrg | tlsVersion |
|---|---|---|---|---|
| facebook.com | 7 | 2026-11-09T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| instagram.com | 7 | 2026-11-09T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| whatsapp.com | 7 | 2026-11-09T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| tiktok.com | 31 | 2026-12-03T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| aliexpress.com | 31 | 2026-12-03T11:16:15+00:00 | GlobalSign nv-sa | TLSv1.2 |
| medium.com | 32 | 2026-12-04T21:48:00+00:00 | Google Trust Services | TLSv1.3 |
| cloudflare.com | 32 | 2026-12-04T23:29:33+00:00 | Google Trust Services | TLSv1.3 |
| openai.com | 42 | 2026-12-15T05:59:47+00:00 | Google Trust Services | TLSv1.3 |
| apple.com | 51 | 2026-12-23T19:10:23+00:00 | Apple Inc. | TLSv1.3 |
| x.com | 55 | 2026-12-27T20:09:53+00:00 | Let's Encrypt | TLSv1.3 |
| zoom.us | 57 | 2026-12-29T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| google.com | 58 | 2026-12-30T19:07:41+00:00 | Google Trust Services | TLSv1.3 |
| youtube.com | 58 | 2026-12-30T19:07:41+00:00 | Google Trust Services | TLSv1.3 |
| yahoo.com | 58 | 2026-12-30T23:59:59+00:00 | DigiCert Inc | TLSv1.3 |
| wikipedia.org | 61 | 2027-01-02T18:34:50+00:00 | Let's Encrypt | TLSv1.3 |

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
