# TVBox Personal Config Repository

My TVBox configuration, hosted on GitHub and served via jsdelivr CDN for fast access in China.

## Files

- `tvbox.json` - TVBox config entry (points to source.json)
- `source.json` - TVBox source (contains site definitions)

## Usage

Fill this URL in your TVBox config address:

```
https://cdn.jsdelivr.net/gh/<your-github-username>/<repo-name>@main/tvbox.json
```

## Modifying config

1. Edit `tvbox.json` or `source.json` directly on GitHub web
2. Commit, wait 1-2 minutes for jsdelivr CDN to sync
3. Refresh on TVBox to see new content

## Adding real video sources

Edit `source.json`, replace `sites[0].api` with a working video API URL,
or add more site elements:

```json
{
  "sites": [
    {
      "key": "site_id",
      "name": "Site Name",
      "type": 3,
      "api": "https://example.com/api.php/provide/vod",
      "searchable": 1,
      "filterable": 1,
      "quickSearch": 1
    }
  ]
}
```

## Live TV

`tvbox.json` already includes aggregated live TV (CCTV, satellite, HK/Macau/TW).
You can replace the m3u link in `lives` field with your own.
