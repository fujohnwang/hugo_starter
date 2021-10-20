# How to start

1. change names in config.toml
2. use `hugoc\`` or `hugo.new` snippets to create post to write on...
	- or use `hugo new posts/__post_file__.md` directly to create starter post file.

# how to preview

run `hugo server` will kick off [a local dev server](http://localhost:1313) with realtime preview.

# how to deploy

run `hugo -D` then rsync everything under `public` directory to your nginx site root.

