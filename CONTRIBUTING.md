# Contributing

Thanks for helping grow this list. You can add a new data source, fix a broken link, or improve an existing entry — no coding required. GitHub’s web editor works fine.

## How to contribute

1. **Fork** this project (click “Fork” at the top right — this copies it to your account).
2. Open `README.md` in your fork and click the pencil icon to edit.
3. Make your changes, then click **Propose changes** → **Create pull request**.

One data source per contribution is preferred.

## Entry format

Add your entry under the best-fitting category. Copy this structure:

```markdown
### [Data Source Name](https://link-to-main-page)

Short description of what the data contains and why it’s useful for railways.

| Field    | Value                                      |
| -------- | ------------------------------------------ |
| Provider | Who provides the data                      |
| Region   | Country or region covered                  |
| Access   | How to get it (see below)                  |
| Format   | CSV, JSON, GTFS, GeoJSON, XML, etc.        |
| License  | License name or "Unknown"                  |
| Updated  | How often it’s updated                     |
```

**Required:** Name (with working link), description, and Access. Use `Unknown` or `—` for fields you can’t find.

**Access** — Be specific: direct download link, API docs, “registration required” + sign-up link, or how to request access (e.g. email).

## Before submitting

- Links work
- Data is actually obtainable (not paywalled with no free tier, not offline)
- Written in English
- Not a duplicate (check the README)

Improvements to existing entries (fixing links, adding fields) are welcome too. For a new category, open an [issue](https://github.com/railtoolkit/data-sources/issues) first or suggest it in your pull request.

Be respectful and constructive — this is a volunteer-maintained project.

## GitHub Pages (maintainers)

The public site is built from this repository with Jekyll (see `_config.yml`). To enable or change deployment:

1. Open the repository on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/** (root), then save.

The site URL is `https://railtoolkit.github.io/data-sources/` (replace `data-sources` if the repository name differs).
