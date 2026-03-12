# jobgrep

> grep your next job — Google search query generator for job hunters

**https://jobgrep.github.io**

---

Tired of clicking through 20 job boards manually? jobgrep generates targeted `site:` Google search queries for 50+ ATS platforms and job boards in one click.

## How it works

Fill in a job title, location, optional keywords, and hit **Generate Links** —
jobgrep builds a precise Google query for each site:
```
site:boards.greenhouse.io AND "Rust Developer" AND "Berlin" AND "remote"
```

Open the ones that look promising. Everything else stays out of your way.

## Features

- **50+ sites** — Greenhouse, Lever, Ashby, Workday, LinkedIn, Wellfound, HN Hiring, DOU, Djinni, and more
- **Date filter** — past hour / 24h / week / month / year (via Google `tbs=qdr:` param)
- **Remote toggle** — appends `"remote"` to every query
- **Recently clicked** — last 5 opened sites are highlighted so you know where you've been
- **Hide sites** — collapse sites you never use; restore anytime
- **⭐ Recommended** — shows ReadyToTouch when searching for Go, Rust, Elixir, Clojure, Scala, or Erlang roles
- **Shareable URLs** — search state is saved to query params automatically; share with one click
- **Light / dark theme** — follows system preference

## No dependencies

Single HTML file. No frameworks, no build step.
Clone and open `index.html` — that's it.

## License

MIT
