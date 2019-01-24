---
title: Taking off the mittens – going back to the future with an iPad Pro
date: 2019-01-24
---
As of 2019, dismissing the iPad as ‘unfit for real work’ or even ‘just for consuming content’ can arguably be considered a tired cliché. But is the iPad Pro ready for actual prime time? Can it be used as a sole means of production by someone who does Serious Computing for a living? 

![](https://bureaubolster.s3-eu-west-1.amazonaws.com/Photo-2019-01-24-10-20.jpeg)

These last few months, I increasingly found myself sitting in front of an idle MacBook Pro (with external monitor, peripherals, the whole shebang), whilst frantically programming Shortcuts on my comparatively tiny iPhone screen. I was creating automated workflows for jobs I would otherwise be performing manually on my MacBook. I figured: a bigger iOS screen would be a welcome addition to my setup. 

Moreover, in a less practical, more gut-feel-y sense, I wanted to experience *delightful computing* - the feeling you get when using FaceID, for example. Hell, even the process of installing an app – *any* app – on iOS gives me the kind of “whoa, I am living in the future” feeling that only iOS seems to be able to provide nowadays. 

Well, now that my late-2016-era MacBook Pro with TouchID is in for repairs (and will be getting its *third* keyboard replacement due to Sticky Key Syndrome) I decided to dive into the deep end and switch to iOS. I did favor this MacBook Pro over any previous model if only for the sake of it having TouchID, allowing me to quickly log in to websites using 1Password. But whereas TouchID is still arguably the best premium hardware feature of the current generation of Apple laptops, it has long been replaced by FaceID on iOS. That is just plain *embarrassing*, and it reinforces the image of macOS as a second-tier OS.

To put it bluntly: working on macOS feels like working in the past. I wanted to go back to the future, so I bought an iPad Pro.

## Mittens 
Paraphrasing William Gibson: the future may be here, but it is not evenly distributed. You do get the impression that the hardware was sent ahead, and the software should be coming along shortly.

I was weary of the idea of doing Real Work on an iPad. As John Gruber ([Daring Fireball](https://daringfireball.net)) has said on several podcast episodes: working on an iPad feels like wearing mittens. I think a couple of factors come into play: certain tasks take more time, are impossible, *seem* impossible or have to be done in convoluted or inconsistent ways. 

A scarcity of system-wide conventions for handling files or windows certainly does not help. But I do think many everyday tasks that appear to be cumbersome on iOS can actually be done more easily – if you take some time to set up alternative workflows.

![Mittens](https://bureaubolster.s3-eu-west-1.amazonaws.com/20r1edd2g168bhky6tuwwfq33bn2arkg.jpeg)

Everyday tasks pose a challenge, though. Downloading an image from Unsplash, cropping and resizing it, optimizing it on [Tinypng.com](https://tinypng.com) and uploading it to a webserver is easy on MacOS if you know how to use websites. On iOS, however, the same procedure feels considerably slower – unless you automate it (using the TinyPNG API and [Dropshare](https://dropshare.app) which sends images to your Amazon S3 bucket and places the url on your clipboard). 

Another example: creating a new Markdown file inside its enclosing folder in Working Copy felt like a chore. So I created a shortcut (see [my Twitter thread](https://twitter.com/jaapstronks/status/1088352712138391552?s=21) to automate this).

So, whenever I feel like as if I’m ‘wearing mittens’ on my iPad Pro, I usually take a step back and think how I can automate whatever it is I’m trying to accomplish. 

## Going in: recommended hardware
If you’re running a digital agency or doing Some kind of content creation, marketing or consultancy work, the iPad Pro will probably be well-suited to your needs. You will need a couple of things, though. Here’s a list of my suggestions for necessary hardware:

- Let’s start with the actual iPad Pro. I’d suggest the 11” with 256GB of storage. That’s plenty of room for local files, photos and some media - I keep most of my files in the cloud, including my media library, thanks to Dropbox and [Infuse](https://firecore.com/infuse). 
- For typing on-the-go, Apple’s official [Smart Keyboard Folio](https://www.apple.com/shop/product/MU8G2LL/A/smart-keyboard-folio-for-11-inch-ipad-pro-us-english?referrer=https://www.google.nl/) is probably your best bet. It’s certainly an improvement over its previous incarnation. It serves as a case as well.

![](https://bureaubolster.s3-eu-west-1.amazonaws.com/Photo-2019-01-24-13-33.JPG)

- When doing serious work at a fixed location – your office desk – you will be better off with a separate Bluetooth Apple Keyboard. 
- I’d also suggest an elevated stand (or some mounted solution like [this one](https://www.goos-e.com/en/)
- Additionally, you could use a separate external monitor that mirrors your iPad screen, using a [USB-C Digital AV adapter](https://www.apple.com/shop/product/MJ1K2AM/A/usb-c-digital-av-multiport-adapter?referrer=https://www.google.nl/). 
- You could also consider purchasing an Apple Pencil. If you’re doing any kind of illustration work, it is a no-brainer. It’s also great for just rough sketching – and even audio editing apps like Ferrite offer support for the stylus.

All combined, this requires a considerabel budget. But our aim is to replace a MacBook Pro (or iMac), which arguably makes it worth the investment.

## Recommended 
Switching to iOS requires you to take a step back and think about your workflows. Because programs and files tend to be more often hidden from your field of vision (and because the Files app isn’t that great yet), it will be necessary to create some structures and shortcuts. Here’s a couple of tips.

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
- External keyboard support is not great. The FN key is absent on the Smart Keyboard Folio, there is no keyboard shortcut to invoke Siri (a voice command or reaching over to hold the power button is required), and there is no way to use a keyboard mode for two languages simultaneously, a mode that is seemingly only possible with the virtual SwiftKey keyboard. While I was typing this in iA Writer, the ‘single quote’ symbol would not respond when I pressed its key – it is somehow fixed again.

All in all: it is still very early days, but it is good enough. I did not want to wait for Shortcuts and FaceID to come to MacOS, and probably until the next ARM-cpu-powered generation of MacBooks arrives, I will not be looking back. 

Are you going iOS-only as well? Follow me on Twitter, I’d love to hear your experiences and tips.
