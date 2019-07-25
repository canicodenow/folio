+++
categories = ["updates"]
date = "2019-07-25T20:15:23+01:00"
image = "/uploads/coder-default.jpeg"
series = []
slug = "portfolio-hugo"
tags = []
title = "I created a portfolio site with Hugo"

+++
I got sick of looking at my Wordpress site. It just **screamed** "this is a blog theme and this person doesn't know what he's doing". To me, anyway.

I wanted a site that looked like so much more than a Wordpress theme, but I had a couple of issues:

* I wanted to do it quickly
* I don't have enough coding knowledge to do it entirely from scratch

## Step up Hugo

I'd read about Hugo during one of my _going down the rabbit hole_ sessions. I knew it was a [static site generator](https://dev.to/ruthreyer/what-are-static-site-generators-356p "What is a static site generator?") and I knew it was fast. But I needed to try it out to know more. So I did. And you're reading the result - which I'm pretty happy with.

To get it going, I just needed to decide on a theme (credit to [Luiz de Pra](https://github.com/luizdepra/hugo-coder/ "coder Hugo theme") for his one) and follow the quickstart guide - [Hugo's documentation](https://gohugo.io/documentation/ "Hugo's documentation") is handy, though for my experience level the learning curve is steep so there was a lot of winging it.

### Personal styling

Once the theme is up and running, it's straightforward to add custom SCSS, or edit the original, to get things looking more personal.

For some reason I like bright backgrounds to header text, so as you can see I've made H1s black on yellow and H3s black on a partially highlighted turquoise background. I liked that at the time, but suspect I won't for long.

Particularly I like my custom links for pages and posts - they transition from blue to red with a thicker, lower underline. Here's the code for them:

      a {
        font-weight: 300;
        color: $link-color;
        text-decoration: none;
        border-bottom: 1px solid;
        transition: all .3s ease-in;
        &:focus,
        &:hover {
          padding-bottom: 4px;
          border-bottom: 2px solid;
          color: rgb(255, 0, 0);
        }
      }

### Things I learned

There was plenty of reading of the documentation to get some things working. Using Google and various blogs on the topics I was able to add:

* a default image for blog posts - I may or may not keep this because adding images this way doesn't seem to include alt-text ([Forestry](https://app.forestry.io/ "Forestry CMS") is the CMS I've hooked up and I can't get alt-text to work - I'm aware it's probably me...).
* a comments section to blog posts. This was an incredible faff as I opted against the default for the theme, Disqus. In the end I managed to hook up [utteranc.es](https://utteranc.es/ "utterances comments") - the main downside being commenters must have a Github account, which rules out the internet users who haven't decided to learn how the whole bloody web works like I have.
* a [contact form](https://canicodenow.github.io/folio/contact/ "contact me") - styled with some custom CSS and HTML and using [Getform](https://getform.io/ "Getform") to access the data.

Naturally, I won't be happy with this for long and as soon as I know how I'll be setting up my site from scratch. I think you'll agree that this is an improvement on my [Wordpress one](https://canicodenow.wordpress.com/ "Wordpress blog"):

Now to make some more things _for_ my portfolio...