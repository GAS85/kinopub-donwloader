# kinopub-downloader

This is simple shell Kinopub Downloader via Podcasts.

## Dependencies

- `curl`, `awk` (comes by default on most systems)
- `xmlstarlet` — install with:
```bash
sudo apt install xmlstarlet   # Debian/Ubuntu
brew install xmlstarlet       # macOS
```

## How to Use

Save the script as `kinopub_downloader.sh`.

Make it executable:

```bash
chmod +x download_podcast.sh
```

Replace the placeholder XML URL in `XML_URL` and `DOWNLOAD_PATH`.

Run it:

```bash
./kinopub_downloader.sh
# Or
./kinopub_downloader.sh s01e03 # to start downloading from Season 1 Episod 3
```
