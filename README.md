# Hawlader Law — Website

Static site. Each page is a self-contained HTML file; Vercel serves them on clean routes (`cleanUrls`).

| Route | File |
|---|---|
| / | index.html |
| /results | results.html |
| /the-firm | the-firm.html |
| /team | team.html |
| /car-accidents | car-accidents.html |
| /blog | blog.html |
| /blog-post | blog-post.html |
| /faqs | faqs.html |
| /contact | contact.html |
| /legal | legal.html |
| /case-review | case-review.html (ad landing) |
| /free-case-review | free-case-review.html (ad landing) |
| /deadline | deadline.html (ad landing) |
| /es | es.html (Spanish ad landing) |
| any unknown path | 404.html |

Deploy: import this repo in Vercel — no build step, framework "Other", output directory = root.
