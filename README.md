# wildfire-publishing

To run the site, make sure `zola` is installed and working.
Download this repository locally and navigate within it. From there, run `zola serve`.

# How to add a new post
To add a new post, create a new file in the `content/posts` directory. The filename should be in the format `YYYY-MM-DD-title.md`. For example, `2023-10-01-my-first-post.md`.
The content of the file should start with a header in TOML format, like this:

```toml
+++
title = "My First Post"
date = 2023-10-01
draft = false
tags = ["example", "post"]
+++
```
Then, write your post content in Markdown below the header. You can use standard Markdown syntax for formatting.

# How to add a new page
To add a new page, create a new file in the `content/pages` directory. The filename should be descriptive, like `about.md` or `contact.md`.
The content of the file should also start with a header in TOML format, like this:

```toml
+++
title = "About Us"
date = 2023-10-01
draft = false
+++
```
Then, write your page content in Markdown below the header. You can use standard Markdown syntax for formatting.

# How to add images
To add images, place them in the `static/images` directory. You can then reference them in your posts or pages using Markdown syntax:

```markdown
![Alt text](/images/my-image.jpg)
```

# Zola Links
For more information on how to use Zola, refer to the [Zola documentation](https://www.getzola.org/documentation/).