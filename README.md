# Hana White portfolio

Simple GitHub Pages portfolio using Jekyll, Tailwind (CDN), and markdown content editable via Prose.io.

## Run locally

1. Install Bundler (one-time, if needed):
   - `gem install bundler`
2. Install dependencies:
   - `bundle install`
3. Start the local server:
   - `bundle exec jekyll serve`
4. Open:
   - `http://127.0.0.1:4000`

## Edit content

1. Open your repository in Prose.io.
2. Edit these markdown files:
   - `index.md`
   - `writing.md`
   - `feedback.md`
   - `workshops.md`
3. Commit changes from Prose.
4. GitHub Pages rebuilds automatically.

## Images

Use `/assets` for all images.

## Contact links

Replace `hello@example.com` in `feedback.md` and `workshops.md` with your real email address.

## Deploy on GitHub Pages

1. Push repository to GitHub.
2. In repository settings, enable **Pages** and set source to **Deploy from a branch**.
3. Choose `main` branch and `/ (root)` folder.
4. Save. The site will publish to your GitHub Pages URL.

## To Push Changes

1. Make and save changes
2. Open new 'Terminal'
3. Run these commands:
- `git status` to check you've saved and the correct files have changed (modified in red)
- `git add .` adds all the files you've changed
- `git status` to check it's green
- `git commit -m "your commit message"` to save that change with a message
- `git push` to push to your github account, which syncs with your website
