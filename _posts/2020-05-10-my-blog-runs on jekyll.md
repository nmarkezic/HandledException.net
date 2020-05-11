---
title: "My blog runs on Jekyll, but why?"
date: 2020-05-10T23:56:30+02:00
categories:
  - blog
tags:
  - Jekyll
  - GitHub Pages
  - Minimal Mistakes Jekyll Theme
---

I am a primarily .NET developer, nevertheless, I chose to run my blog with [Jekyll][jekyll-docs] on GitHub Pages!

From the beginning of my professional career my weapon of choice was .NET Framework. I enjoyed the old .NET, both framework and Visual Studio IDE, when there was no place for Microsoft and cross platform or open source in the same sentence. And I straight out love the new cross platform, open source Microsoft. Most of my time these days I work with .NET Core in some degree and I love every second of it, for blogging purposes I went with Jekyll.

Few reasons why I chose to do so:

- Fast but cheap to run
- It is simple and easy to setup
- Focus is on writing content

### Fast and cheap to run

I wanted to have control over my blog, so from day one going with one of the blog platforms did not felt right but having control did bring some costs to the picture. Those are not significant costs but there are some like hosting cost. And then I stumbled upon  [GitHub Pages][gh-pages].

GitHub Pages as the name says are hosted with GitHub for free. They are hosted directly form a GitHub repository. Changing the content for your site is simple as you can just edit and push changes to the repository and they are live on your site.

You can provide custom domain for your own custom URL and GitHub provides the SSL certificate for free.

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/1/gh-pages-custom-domain.jpg){: .align-center}

### It is simple and easy to setup

On the home page for the GitHub Pages there is a link that suggest using Jekyll for blogging on GitHub Pages. After following the link and googling about it I had my first blog up and running in under 30 minutes.

Then it came to find a good theme and configure it just right for my taste. And then I came upon [Minimal Mistakes Jekyll theme][mm]. I my opinion this theme is fantastic, it has many options and covers every use case for my blog. It was love on first sight. I only spent few hours to tweak and setup the theme and my blog was ready for publishing.

The guides and explanations that the author have provided are clear and to the point, everything I thought of is already covered and everything just worked.

I would recommend anyone that thinks of starting a blog to go and checkout this theme.

### Focus is on writing content

When it came to the realization of my wish to setup a blog first I explored the idea of .NET blog engine, then I thought of rolling my own blog engine using ASP.NET Core, but at the end I realized that the blog engine was just the tool for the job, and first step I took out of my own comfort zone led me to this beautiful discovery that is Jekyll.

The focus of any blog should always be on writing content and sharing something, and I made a mistake of complicating this simple thing and losing one or two years of writing content. Maybe it would be mediocre content, but maybe it would help some to handle one or two exceptions that popped out during development.  

**Do not do what I did and just start writing.**  

[jekyll-docs]: https://jekyllrb.com/docs/home
[gh-pages]:   https://pages.github.com/
[mm]: https://mmistakes.github.io/minimal-mistakes/
