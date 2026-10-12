# Clean Player

Ad-free player for free, legal video: web page links, stream links and M3U playlists.

## Files

- `index.html` : the app.
- `api/find.js` : the video finder. It opens a web page and returns the video the page openly shares. It never logs in, gets round paywalls or breaks copy protection.

## Put it online (free, works on phone and laptop)

The finder needs a host that runs code, so use Vercel (free Hobby plan).

1. Create a free GitHub account, then a new repository called `clean-player`.
2. Choose "Add file", then "Upload files", and drag in `index.html`, `README.md` and the whole `api` folder. Commit.
3. Sign in at vercel.com with GitHub. Choose "Add New", then "Project", import `clean-player` and press Deploy.
4. Vercel gives you an address like `clean-player-yourname.vercel.app`.

## Use it

- Laptop: open the address and bookmark it.
- Phone: open the address, then Share, then "Add to Home Screen". It opens full screen like an app.
- Jump straight to a video: `your-address/?url=` followed by the page link.

## Updating

Change a file in GitHub and Vercel republishes it automatically within a minute or so.

## What won't work

- Pages that need a login or subscription, or use copy protection (DRM).
- Some sites build their player in a way the finder can't read. Use "Open the original page instead".
- Favourites and playlists are saved separately on each device.
