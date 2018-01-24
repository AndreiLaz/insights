# The Coming Age Of The Disappearing Infrastructure

## But Not To Worry Fellow Shell-Geeks, The Future Is Bright

I’m a shell-geek. I’ve always been. My first real job back in 2001 was managing a high-availability network made up of quite a few Unix and Linux machines. And that meant living in the shell. Korn shell, Bash shell, whatever shell, I would always go back to my shell and let my inner geek go crazy at the prompt. Some 15 years later, I’m still a shell-geek.

-> Once a shell-geek [image]

The shell is not going anywhere, but the way we use it is about to change radically.

To understand why, a bit of history.

## Beyond The PC Era And Into The Era Of Calm Technology

Around that same time, 2001, I started working on my first real company. It was called Calm Technologies. I had created my first real product, a client-server mobile file browser. You would install the server on your home computer and then you could browser your files from your mobile phone. Needless to say, I had no idea what product management, marketing and so forth meant and so the product went nowhere. Ditto for the company.

As most entrepreneurs say at the end of a failure, it was a learning experience. But honestly, it truly was. Perhaps, the greatest learning experience for me, wasn’t so much the fact that I tried to grow a product company, but it was that I had learned about a new way of thinking about products. I had recently discovered the work of a brilliant man named Mark Weiser. His research while at Xerox PARC has changed the way I understood technology. I recommend two of his papers in particular, [The Coming Age Of Calm Technology](http://www.ubiq.com/hypertext/weiser/acmfuture2endnote.htm) and [The Computer For The 21st Century](https://www.ics.uci.edu/~corps/phaseii/Weiser-Computer21stCentury-SciAm.pdf).

Guess where I got the name of my first company from?

It’s no mystery that most of the PC era was influenced heavily by innovations pioneered by Apple and Microsoft. But perhaps what’s somewhat less known is that most of the innovations championed by Apple, Microsoft and the like, originated at Xerox PARC. The researchers there made history and will remain heroes in the eyes of many tech entrepreneurs. One such hero is Mark Weiser.

He proposed the idea that technology has three major eras. The Mainframe era, The Personal Computing Era and The Ubiquitous Computing Era. We’re way into the Ubiquitous (or Pervasive) Computing era today. But we still have so much to learn from the work of giants like the researchers at Xerox PARC did decades ago. There’s so much to learn, but I just want to pick out a powerful idea and use it to better understand the current forces that are shaping our present. And our future. The first sentence of the [The Computer For The 21st Century](https://www.ics.uci.edu/~corps/phaseii/Weiser-Computer21stCentury-SciAm.pdf) reads as follows:

*The Most Profound Technologies Are Those That Dissappear.*

It’s been 15 years since I’ve first read this sentence but I’m still profoundly inspired every time I re-read it. I hope you are too. How does it apply today though?

## The Rise Of Real Profound Technologies.

In the past few years we’ve seen a transition from the shell on our local machine, to the shell on a remote machine, to the shell on a virtual machine and now to the shell in a container. Virtualization has changed the way we build technology and now Docker & co are taking the Virtualization revolution a step further with the concept of lightweight containers. We can see a trend in the simplification of infrastructure, from machines, to images and now to containers. But that’s not all.

We’re starting to innovate down to zero. To nothing. To a serverless architecture. Amazon is leading the pack with [AWS Lambda](https://aws.amazon.com/lambda/) which they released into full production less than a year ago. Google is a couple of years behind but they’re moving in that direction too with the introduction of [Google Cloud Functions](https://cloud.google.com/functions/). Still in Alpha but I expect to see rapid developments here. Microsoft Azure doesn’t have anything of the sort yet, but I’ll bet they’re working on it.

I’ve been working with AWS Lambda and I have to say that I didn’t expect much but so far, I’m impressed. The technology feels new and it is. As all new technologies, it requires patience. It’s still early in terms of tooling and community support. You still have to zig zag your way into getting things to work with limited help. But once you get it working, it’s amazing. I have to admint that as a shell-geek, I was nervously reluctant to dump my shell for a serverless architecture where I have absolutely no control over the infrastructure. But at the end of the day, I bet that’s how binary geeks felt when they were faced with embracing assembly. And I bet assembly geeks were also nervous when faced with embracing high-level languages. And so forth.

## Technology Will Evolve Whether We Want It Or Not.

The question is, are we ready to adapt or not? We’ve seen early attempts to transition to a serverless, headache-free architecture. We’ve seen the rise and fall of Parse and the MBaaS economy. Still, none of those technologies truly got out the way, if you know what I mean. With the growth of services like AWS Lambda, Google Cloud Functions, any more more to come, we’re starting to really get a real sense of what a serverless architecture could possibly feel like. It’s almost as if the infrastructure has completely disappeared. It’s there, but it’s not. At least we don’t care about it. But fear not, fellow shell-geeks. We can still give our shells lots of love. The local shell that is. If you’re onboard with AWS and you love your shell, then make sure you make the [AWS CLI](https://aws.amazon.com/cli/) your new best friend. I know I did and it’s crazy now many cool things you can do right from your own local machine with a little (maybe not so little) tool like that and a serverless infrastructure. And if you really want to beef up your local environment, install [Ansible](https://www.ansible.com/) and automate like a boss. I personally believe Ansible is perfectly positioned to reign as the main automation tool for the coming age of the disappearing infrastructure, mainly because it’s agentless. But so much more.
Whatever your local shell looks like, just start getting used to a new world where the infrastructure that powers our products is “invisible” and where remote shells are irrelevant. That’s good news though, my fellow shell-geeks. Because no remote shells also means super-geeked-out local shells.

Oh yeah.
