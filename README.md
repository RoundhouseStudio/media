# Media Repository for Webflow Assets

This GitHub repository is used to host video files (under 20MB) for use in our Webflow website builds. These assets are served via the **jsDelivr CDN**, allowing for fast, reliable delivery of content on the web.

---

## 📁 How It Works

1. **Upload Video Files**  
   Upload any `.mp4` or `.webm` file under 20MB directly to this repo (e.g., in the `/media` folder). Smaller file sizes help ensure fast load times and compatibility with the CDN.

2. **Get the jsDelivr URL**  
   After uploading, copy the raw file path and convert it into a jsDelivr URL using this format:
   https://cdn.jsdelivr.net/gh/[username]/[repo-name]@latest/[path-to-file] OR
   https://cdn.jsdelivr.net/gh/[username]/[repo-name]/[path-to-file]

   _Example:_  
For a file at `media/ROU-wine-showreel.mp4` in a repo called `media`, the CDN URL would be:
https://cdn.jsdelivr.net/gh/RoundhouseStudio/media/ROU-wine-showreel.mp4

3. **Paste Into Webflow**  
Use this jsDelivr URL when embedding videos into Webflow — e.g., as a background video or inside a video element.

---

## ✅ Best Practices

- Keep file names short, lowercase, and hyphenated (e.g. `hero-loop.mp4`)
- Avoid special characters or spaces in filenames
- Compress videos before uploading to keep them below the 20MB limit
- Use `.mp4` for broad compatibility across browsers

---

## 💡 Why Use This Setup?

- **No hosting costs** — Free CDN with GitHub + jsDelivr
- **Global delivery** — jsDelivr is fast and reliable
- **Easy versioning** — You can roll back to older versions if needed

---

## 🔒 Important Notes

- This repo is public, so don’t upload sensitive or private media
- Changes to file names or paths will break any links already used in Webflow

---

## 🤝 Need Help?

If you need help uploading or generating URLs, feel free to reach out and I’ll assist.

