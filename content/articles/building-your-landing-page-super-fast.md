---
title: "Build and launch your startup landing page in a day, with little to no coding required"
date: 2019-02-01
draft: false
description: "A guide on how to build and launch a landing page for your new product. In very little time."
---

![Woman using MacBook Pro on her lap](/images/building-a-website.jpg)

## Building time

In this guide, we’re going walk through how to build a landing page that for your new product in ~ 1 day. It will convey your core offering, enable potential users to sign up to a waitlist, and elicit feedback on product direction.

We’re going to use existing tools and shortcuts as much as possible. So will only need very minimal coding knowledge, I’ll walk you through any edits you might need to make. You will end up with a foundation that can be built upon - so you won’t have to scrap it and start again when you’re ready to develop your full site.

I cover how to come up with your product messaging in A [previous post](https://simpleshapes.io/articles/launch-your-startup-landing-page-part-1/) if you need a hand on where to get started there.

## Who’s this for?

Anyone starting out on a new product or startup, that wants to get their name out there, start building a reputation - but doesn’t want to divert focus too much from developing the core product. You likely have limited developer time, so it makes sense not to spend time you don’t have on your site pre-launch.

But this is time you don’t want to waste. You can begin your early marketing and customer validation efforts now. A simple homepage can facilitate this. At all costs, you want to avoid spending any time and money building a product that people aren’t interested in. This will help you do that.

## Let's get going

Meet [Taco Button](https://infallible-borg-4ff1f6.netlify.com/), the (fictional) product that we will be building the site for in this guide. Taco Button is an app that delivers a daily selection of Tacos with a single touch of a button. The team are super excited to start bringing tacos to people, but they want to make sure there is sufficient demand to rent a kitchen and order the all-important swag.

In putting up a quick landing page, promoting it and gathering feedback - we can validate the concept, without investing any time building something that nobody wants. After all, no market need is the [number one reason startups fail](https://www.cbinsights.com/research/startup-failure-reasons-top/). Once we’re satisfied the product positioning is robust, we have a solid base to built out a full-featured marketing site.

## Options for doing this quickly

Seeing as speed is of the essence here, we’re going to lean on existing solutions that will do a lot of the hard work for us. There are more and more tools popping up each day helping you get started. If you have one, you may want to use your designer/frontend developer here, that’s fine; remember to aim for good enough for now, perfection paralysis is real. By limiting your choices to those provided you should be able to move much faster. When you design yourself, it’s super hard to not get drawn into tweaking and tweaking, worrying that everything has to be perfect. The time to spend more time over this will come, but it isn’t now.

### You have a few options here, depending on what you want most out of it.

[Product hunt](https://producthunt.com) has a tool called [ship](https://www.producthunt.com/ship), if you’re looking to the fastest way to a web presence this may be for you. You can throw together a preview page with signup and survey options build in, all in about 15 minutes. The drawback being you can’t host in under your own domain, so in all but the earliest stages, it probably won't suffice on its own. It does serve as a great way to drive traffic and get feedback as a complementary tool, however. Its free for the basic package, then $50/pm or $199/pm with subsequently increasing features.

[Carrd](https://carrd.co/) is the next step up in this set of tools. It is, in essence, a website builder, there are a number of free layout and widgets. To get the full suite of tools - forms, custom domains it is \$9/per year. You can put together a surprisingly attractive and powerful landing page in minutes. If you just want something to keep you going in the short term, this will probably do you for a good while. In our case, we want to create something that we can build upon to flesh it out into a full site over time. If you just want a quick effective page, this may well be the option for you.

If you are looking for an entirely managed solution, that you can edit yourself and can be built without a developer or designer, then you probably don't need to look any further than [Squarespace](https://www.squarespace.com/).

If you have a designer that is keen to put their stamp on the company brand, then [Webflow](https://webflow.com/) is a great option. It’s really designer-friendly and can output static sites or CMS hosted options. It is more in-depth than we need right now, but worth considering if the above describes your situation.

We are going to take a different approach here. We want to keep most of the speed of the above solutions, but give us the flexibility to adapt to our more specific needs over time. Enter [Uncicorn Platform](https://unicornplatform.com/). Unicorn Platform is a static file (HTML, CSS, JS) generator, that gives you various website components to chose from and piece together to create your site. The power of this is that you don’t have to spend the time designing and developing a site. You have the flexibility to tweak and edit as you like to take a proven format and personalise it enough to make it unique. You then have everything you need in place to build it into a full site when you need it.

It’s worth noting that there are also a number of free and paid template sites out there, if you have the skills to modify something, but don’t want to start from scratch. You are forced to fit your content to an existing layout a little so that probably isn’t a strong an approach to content strategy. [One page love](https://onepagelove.com/) has a nice selection of free and paid templates and inspiration for single page websites.

## Generate

First up we’re going to head on over to [Uncicorn Platform](https://unicornplatform.com/). You’ll be met with a big Try Generator button.

![Generator button screenshot](/images/generate-button-screenshot.png)
/Screenshot 2019-01-31 11.25.20.png

I’m then going to select App, the e-commerce - this will give me a selection of templates suited to the kind of product I want to build. There is a lot of cross-over here, so it doesn’t matter too much which you select. I’m going to go with “Simple Coming Soon I”, this gives me what I need to show off the potential app and capture eager taco fans email to gather their opinions and keep them in the loop.

![Template screenshot](/images/template-screenshot.png)

You’re not able to edit the content in the generator like other platforms, but it’s straightforward enough to do in the code - more on that later.

We don’t have a huge amount of content so far, but that’s ok - we just want to give a taste of what’s to come. I’m going to remove the second block that is there by default and just add a photo component - to really get the tacoistas salivating. You can delete by clicking the bin (trash) icon in the top right of the component. I’ll then click “add component” to select the features I want. There are quite a few free options, that we’re using here - but for \$120 you can get access to all of them. A reasonable fee considering what you would have to pay someone to build all this for you.

I’m pretty happy with this layout so far, so I’m going to go ahead and click “Export Page“ (bottom left). There are a couple of steps to follow to download the generated assets. I now have the basis of my site in all of about 5 minutes.

## Editing

Once you have downloaded and combined your assets, open up the `index.html` file in your favourite browser. You can refresh to keep an eye on your editing progress. Once you’ve got to grips with the layout of your site, open the index.html file in a text editor. If you’re not familiar with editing code, don’t worry - it should be ok to follow along. [VS code](https://code.visualstudio.com/), [Sublime text](https://www.sublimetext.com/3) and [Atom](https://atom.io/) are all good choices here.

You can follow the [Unicorn Platform guide](https://unicornplatform.com/blog/create-awesome-landing-page-for-startup/) if you need a hand in editing your new pages content. Check out the [previous post](https://simpleshapes.io/articles/launch-your-startup-landing-page-part-1/) in this series if you need a helping hand figuring out your approach to content.

Don’t forget to [update the email signup form](https://unicornplatform.com/blog/how-to-activate-mailchimp-integration/) if you have chosen one. You can find their guide [here](https://unicornplatform.com/blog/how-to-activate-mailchimp-integration/).

## Ship it!

Step 7 of the unicorn platform documentation lists a few options for uploading and hosting your new site. But we’re going to look at an alternative, and better option [Netlify](https://netlify.com). Netlify is an incredible platform for hosting and managing modern web apps and sites. It’s easy to upload and host your site, and you get a purpose-built scalable infrastructure optimised for performance. Things like asset minification and optimisation are baked in. It also comes with a suite of tools for enriching what may start out as a static site - such as forms, CMS support and cloud/lambda functions. Best of all you can go a long way using only the free platform.

[Signup](https://app.netlify.com/signup) and head to the dashboard. There you will be met with a screen where you can either choose “new site from git” - this is your best option, as you get all the benefits and safety that GitHub et al provide. But if you want to jump ahead, for now, you can just drop your site folder in the panel that says “Want to deploy a new site without connecting to Git? Drag and drop your site folder here”. Deploys are still version controlled, so you can easily roll back or download and inspect past deployments. But you won’t get the same sort of power and granularity that you would with Git.

If you already have a domain you can click “domain settings” and follow their [documentation for adding a custom domain](https://www.netlify.com/docs/custom-domains). You will already have a temporary URL provided such as the one I have generated for Taco Button. This is great for final testing purposes - [see it here](https://infallible-borg-4ff1f6.netlify.com/).

## Adding tools such as Analytics

Another great benefit to using Netlify is the snippet injection tool. This allows you to drop in any third party javascript snippets, such as analytics, without having to directly add it to your source code. To do this head to click `settings/deploys` - you can learn all about this in the [snippet injection documentation](https://www.netlify.com/docs/prerendering). You will also want to turn on asset optimisation (CSS, JS & image compression), this is also found in `settings/deploys`.

## That’s it!

If you’ve followed along, you should now have a launch page for your new product without having spent days and days on it. The great news is you now have a strong platform to amend and build upon as you launch, scale and conquer the world. When that time comes, you can leverage any of the static site generator tools ([Jekyll](https://jekyllrb.com/), [Hugo](https://gohugo.io/), [Gatsby](https://www.gatsbyjs.org/) etc) and combine with [Netlify CMS](https://www.netlifycms.org) to give you the power and control you may need as a growing organisation. But that’s for another day. For today, all that’s left is to congratulate yourself on a job well done.
