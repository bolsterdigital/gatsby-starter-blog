---
title: Taking off the mittens – running a digital agency from an iPad Pro
date: 2019-01-24
---
As of 2019, dismissing the iPad as ‘unfit for real work’ or even ‘just for consuming content’ can safely be considered a tired cliché. But is the iPad Pro ready for prime time? Is it ready to be used as a sole means of production by anyone who does Serious Computing for a living? 

Well, I found myself sitting in front of a MacBook Pro setup with an external display, ignoring it, whilst frantically programming Shortcuts on my comparatively tiny iPhone screen, creating automated workflows for jobs I would otherwise be performing manually on my MacBook. I needed a new iPad. 

Moreover, in a less practical, more gut-feel-y sense, I wanted to experience *delightful computing* - the feeling you get when using FaceID, for example. The “whoa, I am living in the future” kind of feeling that only iOS seems to be able to provide. 

Now that my late-2016-era MacBook Pro with TouchID is in for repairs (its *third* keyboard replacement) I decided to dive into the deep end and switch to iOS. So, I bought an iPad Pro.

![](https://bureaubolster.s3-eu-west-1.amazonaws.com/Photo-2019-01-24-10-20.jpeg)

## Mittens 
I was weary of the idea of doing Real Work on an iPad. iOS gives me fewer but *better* tools. As for workflow automation, I love Hazel, Keyboard Maestro and Alfred on iOS, but I’m not enough of a programmer to figure out how to do API calls to Airtable, Netlify or other services I depend on and use the results for further processing. All that is a breeze on iOS, thanks to Shortcuts.

![Mittens](https://bureaubolster.s3-eu-west-1.amazonaws.com/20r1edd2g168bhky6tuwwfq33bn2arkg.jpeg)

Everyday task pose a challenge, though. 
Downloading an image from Unsplash, cropping and resizing it, optimizing it on [Tinypng.com](https://tinypng.com) and uploading it to a webserver can be a cumdersome task on any platform, but it’s easy on MacOS if you know how to use websites. 

On iOS, however, the same procedure feels considerably slower – unless you automate it (using the TinyPNG API and [Dropshare](https://dropshare.app) which sends images to your Amazon S3 bucket and places the url on your clipboard). 

Another example: creating a new Markdown file inside its enclosing folder in Working Copy felt like a chore. So I created a shortcut (see [my Twitter thread](https://twitter.com/jaapstronks/status/1088352712138391552?s=21) to automate this.

So, whenever I feel like as if I’m ‘wearing mittens’ on my iPad Pro, I usually take a step back and think how I can automate whatever it is I’m trying to accomplish. 


## Going in: recommended hardware
If you’re running a digital agency, doing content creation, marketing or consultancy work, the iPad Pro will probably be well-suited to your needs. You will need a couple of things, though. Here’s a list of my suggestions for necessary hardware:

- Let’s start with the actual iPad Pro. I’d suggest the 11” with 256GB of storage. That’s plenty of room for local files, photos and some media - I keep most of my files in the cloud, including my media library, thanks to Dropbox and [Infuse](https://firecore.com/infuse). 
- For typing on-the-go, Apple’s official [Smart Keyboard Folio](https://www.apple.com/shop/product/MU8G2LL/A/smart-keyboard-folio-for-11-inch-ipad-pro-us-english?referrer=https://www.google.nl/) is probably your best bet. It’s certainly an improvement over its previous incarnation. It serves as a case as well.
- When doing serious work at a fixed location – your office desk – you will be better off with a separate Bluetooth Apple Keyboard. 
- I’d also suggest an elevated stand (or some mounted solution like [this one](https://www.goos-e.com/en/)
- Additionally, you could use a separate external monitor that mirrors your iPad screen, using a [USB-C Digital AV adapter](https://www.apple.com/shop/product/MJ1K2AM/A/usb-c-digital-av-multiport-adapter?referrer=https://www.google.nl/). 
- You could also consider purchasing an Apple Pencil. If you’re doing any kind of illustration work, it is a no-brainer. It’s also great for just rough sketching – and even audio editing apps like Ferrite offer support for the stylus.

All combined, you will be confronted with a hefty price tag. But our aim is to replace a MacBook Pro (or iMac), which arguably makes it worth the investment.

## Recommended software
Alright, you will need a couple of well-crafted apps. Generally speaking, though, switching to iOS often requires you to take a step back and think about your workflows. Because programs and files tend to be more often out of your field of vision (and because the Files app isn’t that great yet), it will be necessary to create some structures and shortcuts. Here’s a couple of tips.

- Use Shortcuts. You can easily configure Shortcuts as Alfred-style task / app / website launchers, for example.
- Install apps that offer great Shortcuts support or at least use URL schemes, such as Fantastical (calendars), Omnifocus or Things (task lists), Trello (project management), Working Copy (GIT client) and Spark. 
- If you’re doing web development work (or your agency does), Working Copy especially is an absolute must-have. I use Coda for editing CSS, HTML and JS files (or the Working Copy app itself, actually), and Textable or iA Writer for markdown (Textable has more features, such as Textexpander support, whereas iA Writer offers a more polished editing experience and lets you export nicely styled PDF files).
- If you are really into automation, you can connect Shortcuts to Zapier. For example, it’s easy to automatically create Harvest projects and Trello boards using details from your Contacts app or an Airbase table - and also update that Airbase table.
- Use Siri. You can [type commands to Siri](https://www.imore.com/ios-11-will-let-you-type-queries-siri) (talking out loud to your computer in an agency setting is awkward and annoying).

## Remaining gripes
All in all, I am really happy with the iPad Pro. Its shortcomings are more than compensated by its advantages. 

Shortcuts-fueled wizardry aside, perhaps its most important feat is the user experience. It is blazingly fast, it has really nice animations and a host of advanced apps.

But it’s not all great. My main gripes:

- OS-wise, the iPad isn’t really there yet. Software support on the second-most-popular hardware type on iOS, far behind the juggernaut that is the iPhone, is probably not high on Apple’s list of priorities. But I have high hopes for iOS 13. If Apple can give the Files and Shortcuts apps some love and improve multitasking, I am going to be a happy camper.
- Ergonomics is kind of an issue. Typing for extended periods of time on a connected Smart Keyboard Folio thing or, God forbid, on the iPad’s virtual keyboard will hurt your neck, arms, upper back and probably your mental health to boot. An iPad stand and a separate Bluetooth keyboard will alleviate this issue to a great extent, but this setup introduces a new problem: you will repeatedly have to lift your arm in an awkard position to use the touchscreen. A keyboard will not suffice, and support for a Bluetooth trackpad is sorely lacking (I’m not sure how that would work, but it should be doable).
- External keyboard support is not great. The FN key is absent on the Smart Keyboard Folio, there is no keyboard shortcut to invoke Siri (a voice command or reaching over to hold the power button is required), and there is no way to use a keyboard mode for two languages simultaneously, a mode that is seemingly only possible with the virtual SwiftKey keyboard. 

All in all: it is still very early days, but it is good enough. I did not want to wait for Shortcuts and FaceID to come to MacOS, and probably until the next ARM-cpu-powered generation of MacBooks arrives, I won’t be looking back. 
