# Our Story

Anniversary website. Put photos and videos in the `media` folder and they appear on the site by themselves.

## Put it online (GitHub Pages)
1. Make a repository (public) on github.com, for example `our-story`.
2. Upload `index.html`, `song.m4a` and `media.json` to the main page of the repository.
3. Create the media folder: Add file > Create new file, type `media/README.txt` as the name, paste anything, Commit.
4. Open the `media` folder > Add file > Upload files, and add your photos and videos.
5. Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`, Save.
6. After about a minute your site is at `https://YOUR-USERNAME.github.io/our-story/`.

## Adding more later
Upload more files into `media`. Refresh the site and they are in the mix.

## Notes
- Keep each file under 25 MB (GitHub's limit for web uploads). Trim long videos first.
- Use mp4 or webm videos. iPhone videos work best as "Most Compatible" (Settings > Camera > Formats).
- If the site doesn't list new files (GitHub limits how often it can be asked), also add the file name to `media.json`, like `["01-first-date.jpg","dance.mp4"]`.
- A free GitHub Pages site and its repository are public: anyone with the link can see the photos and videos.
