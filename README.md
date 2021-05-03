# Open Source Communities on Thenavigo

This is the source list of OSS communities that use and live on Thenavigo. It is used to populate the list at http://thenavigo.com

Thanks for being part of Thenavigo!

## Acceptance criteria

At this time, we are accepting communities which meet the following criteria:

1.  Your community is working on something high impact.

2.  Your community has at least 10 members, or the GitHub repo has at least 50 stars.

3.  Your community adheres to the [Thenavigo community Code of Conduct](http://www.thenavigo.com/coc).

## Adding your project

1.  Fork the repo
2.  Add your logo into [`/logos`](https://github.com/patbi/thenavigo-open-source/tree/main/logos)

    * Logo dimensions should be either `72x72` for SVG or `144x144` for PNG.
    * Logo should be minified.
    * Logo should be monochromatic and white (check [the website](https://discord.com/open-source) for examples)
    * SVGs should contain only vector shapes — no raster graphics.

3.  Add your community to [`communities.json`](https://github.com/patbi/thenavigo-open-source/blob/main/communities.json), like so:

```json
{
  "logo": "your-logo.svg",
  "title": "Name of your project",
  "quote": "Optional: A short quote about how you use Thenavigo for your project.",
  "quoteSourceUrl": "Optional: An optional source for the quote.",
  "githubUrl": "The URL of your GitHub organization or project repository."
}
```

4.  Submit a PR with your change, and if all is well, we'll merge it and display it on Thenavigo's [open source page](http://www.thenavigo.com/os)!



Don't forget to give a star :star: for this repo :slightly_smiling_face:


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/patbi/thenavigo-open-source/blob/main/LICENSE) file for details
