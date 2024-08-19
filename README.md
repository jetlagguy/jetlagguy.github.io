# The Jet Lag Guy website

Source code for the website [The Jet Lag Guy](https://thejetlagguy.com).  Built with [Hugo](https://gohugo.io) and the [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke) theme.

## Adding Content

* Start the server to preview your changes as you go, and open [http://localhost:1313/](http://localhost:1313/) in your browser.
  See `RUNME.runme`
* Create folder in the appropriate section (e.g. `content/en/blog`, `content/en/olympics`)
* Create a new markdown file in that folder, `index.md`
* Add front matter to the file
  * `title`: the title of the post
  * `date`: the date of the post
  * `tags`: a list of tags for the post
  * `featured_image`: the path to the featured image for the post
  * `aliases`: it the post has moved, the old URL(s); see game of zones fos example
  * `draft: true` or `published: false` to keep in-progress posts from being published, or to unpublish a post
* Add content to the file
* Add images to the folder
* Add featured_image to the front matter
* Commit the changes
* Push the changes

## Tags

Here are some tags I anticipate you will use.  Add more as needed.

* articles
* interviews
* jet lag
* travel fatigue
* olympic games
* olympics
* Paris 2024
* Tokyo 2021
* LA 2028
* Los Angeles 2028
* re-timer glasses
* re-timer
* business travel
* olympic winter games
* winter olympics
* Milano Cortina 2026

## Including Media

The following [shortcodes](https://gohugo.io/content-management/shortcodes/) are available for including media in your posts.

Images: `{{< figure src="photo.jpg" alt="" title="" caption="" link="" attr="" attrlink="" >}}`

* src: the path to the image, local or remote
* alt: the alt text for the image, used for accessibility, e.g. screen readers
* title: the title text for the image, used for hover text
* caption: the caption for the image, displayed below the image
* link: the URL to link to when the image is clicked
* attr: the attribution text for the image
* attrlink: the URL to link to when the attribution text is clicked

Youtube: `{{< youtube id=123456789 start="" end="" title="" >}}`

* `id`: the YouTube video ID from the video URL.  Optional, but if you add other tags (e.g. start time) it will help prevent confusion
* `start`: the start time for the video, in seconds
* `end`: the end time for the video, in seconds
* `title`: the title text for the video, used for hover text

Instagram: `{{< instagram 123456789 >}}`

Twitter: `{{< twitter user="username" id="123456789" >}}`

Full documentation for these and other shortcodes is available [here](https://gohugo.io/content-management/shortcodes/)
