# Blog Content

This repository holds markdown posts.

## Structure

- content/blog/posts.json (index of posts)
- content/blog/<category>/ (markdown posts by category)

## posts.json fields

Each item in posts should include:

- slug (string)
-     itle (string)
- date (YYYY-MM-DD)
-     ags (string[])
- category (string, folder name)
- summary (string)
- path (string, relative to repo root, e.g. content/blog/architecture/my-post.md)
