# calientes-plus.github.io

This is a minimal static portfolio to showcase YouTube videos.

How to add videos
- Open `index.html` and find the `videos` array near the bottom of the file.
- Add a new object with the keys: `id`, `title`, and optionally `description` and `date`.
- To make a video the featured "latest" video, either put it first in the array or set `latest: true` on the object.

Example entry:

```
{ id: 'YOUR_YOUTUBE_ID', title: 'My new video', description: 'Short description', date: '2025-12-01', latest: true }
```

After editing, save `index.html` and refresh the page. The newest/marked video will be shown prominently and the thumbnails will appear on the right (or below on narrow screens).

Deployment
- This is a static page — it can be hosted on GitHub Pages, Netlify, Vercel, or any static file server.

If you'd like, I can add a simple script to load videos from a JSON file or a small admin UI for easier updates.