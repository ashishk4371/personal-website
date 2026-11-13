# Personal website

A simple 4-page Jekyll site: Home, Blog, Projects, Resume.

## Running it locally

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## Editing content

- **Home**: edit [index.html](index.html). Replace `assets/images/profile.jpg`
  with your real photo (same filename, or update the path in index.html),
  and update the bio text and links.
- **Blog**: add a new file to `_posts/`, named `YYYY-MM-DD-title.md`, e.g.

  ```
  ---
  title: "My New Post"
  date: 2026-12-01
  ---

  Write your post here in Markdown.
  ```

  It will show up on the blog page automatically, newest first.
- **Projects**: edit [_data/projects.yml](_data/projects.yml). Add a new
  entry with `title`, `description`, and `github` for each project.
- **Resume**: replace `assets/files/resume.pdf` with your actual resume
  (keep the same filename, or update the link in
  [resume/index.html](resume/index.html)).

## Publishing with GitHub Pages

1. Push this folder to a GitHub repo.
2. In the repo settings, go to Pages, and set the source to the `main`
   branch (root).
3. GitHub builds and publishes the Jekyll site automatically — no extra
   build step needed.
