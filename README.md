# Cyber Write-Up Fetcher

This project automatically scrapes cybersecurity-related write-ups from **Medium** and **Freedium** every 10 minutes.
It focuses on the following topics:

* 🛡️ Cybersecurity
* 📰 Cyber News
* 🧰 Security Tools

## 🔧 Features

* Scrapes recent articles from Medium/Freedium
* Filters for relevant cybersecurity keywords
* Saves results in `output/articles.json`
* Can be scheduled via cron (every 10 minutes)

## 🧠 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run manually:

```bash
python3 fetcher.py
```

Schedule with cron (every 10 minutes):

```bash
crontab -e
# Add this line:
*/10 * * * * /path/to/scheduler.sh
```

## 📂 Output

Scraped articles are stored in:

```
output/articles.json
```

## 📜 License

MIT License — feel free to fork and improve.
