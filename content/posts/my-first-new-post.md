---
title: "My First New Post"
date: 2021-08-29T18:49:47+03:00
draft: false
---

## I have installed Hugo. What is the next steps?

I have installed Hugo for the first time following to the guide on [Cloudflare](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site). What is the next step? There are two choices:

- Add some testing content,
- Try to instal a new theme.

I chose the first one. Then I had the following question:

## How to create new post in Hugo

There is two ways to create new content files:

- Manually, i.e. place `new-file.md` into `content/posts` folder and write metadata (front matter) in them manually too.
- Automatically, i.e. use the `new` command.

Of course, I chose automatic method: opened the terminal in my editor and wrote:

`hugo new posts/my-first-post.md`

And I immediately saw such an important advantage of creating new posts through the Terminal, as I received a new file with the already generated Frontmatter.

### How to insert an image in Hugo content

Content organization in Hugo can be done in different ways. More often I use the Page Bundles, that is Leaf Bundle (🔗📘[Hugo Docs](https://gohugo.io/content-management/page-bundles/)), because it allows me to gather all the elements of the post.

So, create a folder with the name of this new post - `new-post-with-images`, then add a file `index.md` to it and the desired images. The structure should look something like this:

```text
content/
   ├── posts/
   │   ├── new-post-with-images/
   │   │   ├── index.md
   │   │   ├── image1.jpg
   │   │   ├── image2.png
   │   └── my-other-post/
   │       └── index.md
```

## Нow i tried to create my first new page in Hugo

The page is not a post, but a slightly different type of post, I thought. Unexpectedly, the method of creating a new page was not so simple for me. I described my experience in the next post: [How to create new page in Hugo]({{< ref "new-page-in-hugo" >}})

---

## Useful links I used for creating the first new post in Hugo

- Basic syntax of Markdown: [The Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- Getting started with Hugo: [Hugo Docs](https://www.markdownguide.org/basic-syntax/)
