# Extensions Repository

Anime extension repository for **Aniyomi**, **Tadami**, and compatible clients.

## Add repository

Paste this URL in your app under extension repositories:

```
https://raw.githubusercontent.com/ox666577-droid/extentions-repo/main/index.min.json
```

| Client | Path |
|--------|------|
| Aniyomi | Settings → Browse → Anime extension repos |
| Tadami | More → Settings → Browse → Extension Stores (Anime) |

## Repository structure

```
.
├── index.min.json   # Catalog (used by the app)
├── index.json       # Catalog (pretty-printed)
├── apk/             # Extension APKs
├── icon/            # Extension icons
├── index.html       # Optional web browser
└── repo.json        # Repository metadata
```

## Requirements

- Repository must remain **public** so clients can fetch the index and APKs without authentication.
- HTTPS raw GitHub URLs are required for in-app installation.

## License

Extension packages retain their respective upstream licenses. This repository only distributes compiled APKs and catalog metadata.
