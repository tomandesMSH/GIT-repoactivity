# Repo Activity Calendar

A GitHub-style contribution calendar for any single repository.

Enter `owner/repo` (or paste a GitHub URL) and it shows commits per day over the last year, plus stats: total commits, active days, best day, longest and current streak, and busiest weekday.

## Use

- Open `index.html` in a browser, or host it on GitHub Pages.
- Link straight to a repo with `?repo=owner/name`.
- Optional token: raises the API rate limit (60/hour without one) and works with private repos. It's stored only in your browser.

Data comes from GitHub's `stats/commit_activity` API, so it counts commits on the default branch only.
