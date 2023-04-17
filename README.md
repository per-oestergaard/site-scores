# site-scores
Scan lego.com, lego.cn, lego.&lt;tld> and legogroup.io with securityheaders.com and present a dashboard

# What it does

1. Find relevant domains using Certificate Transparency Logs (CTL) (crt.sh)
2. Filter domains using DNS lookup
3. Filter domains using port test (to save licensed scans)
4. Find 200 domains prioritizing not yet filtered and then sorted by last-scan
5. Call securityheaders to scan
6. Save result in where?
7. Render dashboard, CSV and JSON
8. Display dashboard on github pages, publish CSV and JSON

