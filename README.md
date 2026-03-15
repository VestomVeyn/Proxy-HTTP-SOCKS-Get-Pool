# ProxyBot Pro

**Ultimate Proxy Manager & Checker Bot**  
Fast, multi-threaded proxy scraper, checker, loader and rotator — perfect for automation, scraping, account creation, captcha bypass and any high-volume proxy-dependent tasks.

<p align="center">
  <img src="https://i.ibb.co/PZG6Bx7m/Screenshoytutyt-1.png" alt="ProxyBot Interface" width="820">
  <br>
  <sub>Dark modern UI • Proxy list loader • Checker • Scraper tabs • Real-time stats & filters</sub>
</p>

## ✨ Core Features

- **Proxy Sources** — Built-in scrapers for free/public proxy lists (multiple sites)
- **Proxy Checker** — HTTP/SOCKS4/SOCKS5 support • Speed test • Anonymity level • Geo check
- **Mass Loading** — Import from .txt, .csv, API endpoints or clipboard
- **Filters & Sorting** — By country, type (HTTP/SOCKS), speed (ms), uptime, anonymity (elite/anonymous/transparent)
- **Real-time Stats** — Working / Dead / Total • Average ping • Success rate
- **Export** — Save working proxies in multiple formats (txt, ip:port, user:pass)
- **Auto-Rotation** — For external tools (copy rotating list to clipboard or file watcher)
- **Multi-threading** — Check hundreds/thousands of proxies in seconds
- **Dark Igyx UI** — Clean animated interface with progress bars & live logs
- **Github Sync** — Pull latest proxy sources & checker configs

## 🚀 Quick Start

1. Launch ProxyBot
2. Choose your mode:

   - **Scrape** → Grab fresh proxies from public sources
   - **Load** → Import your own list (txt, clipboard, file)
   - **Check** → Start testing loaded proxies

3. Set checker options:

   - Timeout (ms)
   - Threads (recommended: 100–500)
   - Test URL (default: google.com or custom)
   - Proxy types to check (HTTP / SOCKS4 / SOCKS5)

4. Hit **Start** — watch live results in the table

<img src="https://i.imgur.com/SWVfEVg.gif" alt="Demo">

## ⚙️ Main Controls

| Feature / Tab       | What it does                                      | Best Setting Tip                  |
|---------------------|---------------------------------------------------|-----------------------------------|
| Scrape              | Fetch fresh proxies from multiple sites           | Run every 1–4 hours               |
| Load                | Import proxy list (ip:port or user:pass:ip:port)  | Use residential lists for best    |
| Check               | Test proxies for speed & working status           | 300–1000 threads on good PC       |
| Filters             | Country, type, speed, anonymity, uptime           | Elite + <800ms + US/CA/EU         |
| Export              | Save working proxies                              | Auto-save every 5 min             |
| Threads             | How many proxies to check at once                 | 200–800 depending on CPU          |
| Timeout             | Max wait time per proxy                           | 5000–10000 ms                     |
| Github Sync         | Update sources & patterns                         | Enable daily                      |

## 🛡️ Pro Tips for Maximum Performance

- Use **residential / mobile proxies** for serious tasks — free/public die fast
- Filter aggressively: **Elite** + **<500ms** + **country match** = gold
- Run checker in background while scraping new lists
- Combine with rotation scripts for captcha/account tools
- Save working proxies every few minutes — lists die quickly
- Monitor **success rate** — below 10%? Switch sources
- Avoid overloading threads — too many = false dead proxies

## 📸 Interface Preview

<p align="center">
  <img src="https://i.ibb.co/PZG6Bx7m/Screenshoytutyt-1.png" alt="ProxyBot Main Dashboard" width="820">
</p>

*(Proxy table, live ping bars, stats counters, source tabs, export button, etc.)*

## Notes

- Private / closed-source development
- Built for automation, testing & research use cases

Last updated: 2026