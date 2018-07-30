_aka "What do you use?"_

Basically we just sit on our couch side by side and start chatting. We currently use a [Rode Reporter](/reporter) connected to a [Zoom H5](/zoomh5) with the gain set to around 6.5, and a low-cut filter set to 80Hz. We record to a 44.1kHz 16bit `wav` file.


[Dave](/hosts/dave) will then copy the `wav` file to his [mac](/mac) and run it through the excellent but abandoned [Levelator](http://www.conversationsnetwork.org/levelator) to fix the audio levels. He then will do some basic editing in [Audacity](http://www.audacityteam.org/):

1. [Remove the background noise](https://www.podfeet.com/blog/recording/how-to-remove-noise-with-audacity/)
1. Apply a [noise gate](https://wiki.audacityteam.org/wiki/Nyquist_Effect_Plug-ins#Noise_Gate)
1. Fix any massive issues and chop out garbage
1. [Truncate silence](https://manual.audacityteam.org/man/truncate_silence.html) level -35dB and duration longer than 0.5s to 0.5s
1. Move sections around if needed
1. Reduce breathing and remove pops that may have been increased in loudness by Levelator (select the section and set [amplify](https://manual.audacityteam.org/man/amplify.html) to -10dB)
1. Remove most 'umms' and false starts
1. Cut or [censor any swear words](http://www.instructables.com/id/How-to-create-a-Censor-Beep-Sound-in-Audacity/) that may have crept in (generate a 1000Hz tone at 0.3 amplitude)
1. Add back silences or 'umms' where a topic changes rapidly and the audience may be lost
1. Add the outro guitar strum

Once the file has been exported as an `aiff` file, it is converted to an `mp3` (64 kbps mono) and has chapter art and links added using [Forecast](https://overcast.fm/forecast). The resulting file is then uploaded to [Fireside](http://fireside.fm/), show notes, images, and links are collected and cleaned up, and then it's published to the world.

### Hardware ###

* [Rode Reporter](/reporter) - Our currently mic, shared between us 'interview' style
* [Zoom H5](/zoomh5) - An excellent portable audio recorder. We record to a 4GB SD card
* [4GB Micro SD card](/sdcard) - 4GB Kingston Micro SD HC card and Micro SD adaptor
* [13" MacBook Pro](/mac) the second [best laptop Apple has made](https://marco.org/2017/11/14/best-laptop-ever)
* [MS LifeChat LX-3000 Headphones](https://www.microsoft.com/accessories/en-us/products/headsets/lifechat-lx-3000/jug-00013) - These are the only headphones that haven't been broken (yet)
* [USB-C to USB Adapter](https://www.apple.com/au/shop/product/MJ1M2AM/A/usb-c-to-usb-adapter) gotta have your dongles

#### Previous hardware ####

Hardware that hasn't worked out or we've moved away from.

* [Blue Yeti](/blueyeti) - Turned out to not worth the trouble and the audio wasn't great
* [Hamilton KB220M](https://www.jbhifi.com.au/headphones-dj/accessories/hamilton/hamilton-kb220m-tripod-boom-mic-stand/444220/) - No longer needed as we don't use the Blue Yeti
* Recording a double-ender with a 2nd [Rode smartLav+](/smartlav) and [iPhone SE](/iphonese) - This was too much work to edit as there was a lot of cross-talk
* [Rode smartLav+](/smartlav) - Worked surprisingly well, used on the end of a wooden chopstick
* [3.5mm to Lightning Adapter](https://www.apple.com/au/shop/product/MMX62FE/A/lightning-to-35mm-headphone-jack-adapter) - Lightning to 3.5mm Headphone Jack Adapter, for the Rode SmartLav+
* [iPhone 7](/iphone7) - Used to record audio along with the [VoiceRecordPro7](https://itunes.apple.com/us/app/voice-record-pro-7-full/id820659911?mt=8&at=1001lHTb) app

### Software ###

* [Audacity](http://www.audacityteam.org/) - Edit and clean up the audio
* [Levelator](http://www.conversationsnetwork.org/levelator) - Fix the levels automatically
* [Forecast](https://overcast.fm/forecast) - To add chapter markers and artwork
* [Dropbox](https://db.tt/FGcwblEF56) and [Google Docs](https://www.google.com.au/docs/about/) to share files and notes
* [Inkscape](https://inkscape.org/en/) - To create and edit `svg` image files
* [GIMP](https://www.gimp.org/) - An image editing program
* [convert](https://www.imagemagick.org/script/convert.php) - Converting images for show notes and chapter art
* [exiftool](https://www.sno.phy.queensu.ca/~phil/exiftool/) - Strip metadata from images
* [Marked2](http://marked2app.com/) - Preview markdown files
* [aspell](http://aspell.net/) - Check markdown files for spelling mistakes

#### Previous software ####

Software that hasn't worked out or we've moved away from.

* [Piezo](https://rogueamoeba.com/piezo/) - Record audio on the Mac, no longer needed as we don't use the _Blue Yeti_
* [Podcast Chapters](http://chaptersapp.com) - Add chapters and art, replaced with [Forecast](https://overcast.fm/forecast) as we found _Podcast Chapters_ made larger file sizes
* [ffmeg](https://www.ffmpeg.org) to down-sample mp3s for publishing
* [VoiceRecordPro7](https://itunes.apple.com/us/app/voice-record-pro-7-full/id820659911?mt=8&at=1001lHTb) - To record audio on the [iPhone 7](/iphone7). Seems to produce better audio than the inbuilt voice memo software as we can increase the quality settings

### Other services ###

* [Fireside](http://fireside.fm/) - Our hosting platform
* [Gandi](https://www.gandi.net) - Our domain registrar and webmail provider
* [My Podcast Reviews](https://mypodcastreviews.com) - Collect your international podcast reviews and email them to you
* [IFTTT](https://ifttt.com) - For automating episode posting to [Twitter](/twitter) and [Reddit](/reddit)
* [Sticker Mule](https://www.stickermule.com/au/unlock?ref_id=9044590701) - Creating stickers for [Patreon](/patreon) rewards
* [Artwork Check](https://www.podcastlaunch.co/ArtworkCheck/) - Shows you what your artwork will look like in various podcast apps
* [GitHub](https://github.com) - To version control and share our source files 

### Scripts and other ancillary things ###

* [sferix/t](https://github.com/sferik/t) - A command-line power tool for Twitter
* [podcast-fulllist.py](https://github.com/rdmarsh/sandfm_podcast/blob/master/bin/podcast-fulllist.py) - List all the podcasts from an [Overcast](http://overcast.fm/) OPML file in markdown.
* [podcast-of-the-week.py](https://github.com/rdmarsh/sandfm_podcast/blob/master/bin/podcast-of-the-week.py) - Select a podcast at random from an [Overcast](http://overcast.fm/) OPML file to post to twitter
* [random-question.sh](https://github.com/rdmarsh/sandfm_podcast/blob/master/bin/random-question.sh) - Print a question at random from [250 Conversation Starters](https://conversationstartersworld.com/250-conversation-starters/) website
* [tweet-of-the-week.py](https://github.com/rdmarsh/sandfm_podcast/blob/master/bin/tweet-of-the-week.py) - Select a message at random for tweeting
* [tw-unfollow-and-follow-generate.sh](https://github.com/rdmarsh/sandfm_podcast/blob/master/bin/tw-unfollow-and-follow-generate.sh) - Makes list of twitter accounts that should be (un)followed

Other scripts we wrote and occasionally use are available on our [GitHub](/github) page.

### Common commands ###

Some useful commands we sometimes use for producing audio and image files:

Convert to mono, 64kb/s, 44.1k:

```
ffmpeg -f mp3 -acodec libmp3lame -b:a 64000 -ac 1 -ar 44100 outfile.mp3 -i infile.aiff
```

* `-f mp3` - force format (to mp3)
* `-acodec libmp3lame` - force audio codec (to libmp3lame)
* `-b:a 64000` - audio bitrate (to 64kb/s) 
* `-ac 1` - set number of audio channels (to 1/mono)
* `-ar 44100` - set audio sampling rate (to 44.1 kHz)
* `outfile.mp3` - output file
* `-i infile.aiff` - input file

Strip image metadata:

```
exiftool -all= file.jpg
```

Prepare images for show notes; reduce, convert, remove metadata:

```
convert -resize 800x600 -quality 80% -strip infile.jpg outfile.jpg
```

Prepare images for chapter artwork:

```
convert -resize 1400x1400 -quality 80% -strip infile.jpg outfile.jpg
```

## Podcasting tips ##

Some items that we try to follow to make our episodes better:

1. Shorter is better for us. We aim for 15-20 minutes, no more than 30 minutes unless it's needed to cover the topic
1. We try to stick to one topic per episode
1. Keep our intro short, preferably less than 2 minutes
1. Add silences or 'umms' where a topic changes rapidly and the audience may be lost

## Others advice ##

There are many others who have detailed their workflow much better than I have, check them out:

**Dan Benjamin**

* [Podcast Method podcast](http://5by5.tv/podcastmethod)
* [Podcast Method gear recommendations](http://podcastmethod.co/)
* [Podcast hosting](https://fireside.fm)

**Jason Snell**

* [Want to do a podcast](https://sixcolors.com/post/2014/11/want-to-do-a-podcast-dont-be-intimidated/)
* [How I podcast](https://sixcolors.com/post/2015/01/how-i-podcast-recording/)
* Check out all of [Jason's podcasting articles](https://sixcolors.com/topic/podcasting/), there will be some gems in there that will be useful

**Marco Arment**

* [Easy Listening](https://marco.org/2014/11/29/easy-listening)
* [Podcasting Microphones Mega-Review](https://marco.org/podcasting-microphones)

**Casey Liss**

* [How I make podcasts](https://www.caseyliss.com/2014/11/22/how-i-make-podcasts)
* [Audiophilia](https://www.caseyliss.com/2014/11/29/audiophilia)

**Daniel J. Lewis**

* [The Audacity to Podcast](https://theaudacitytopodcast.com) - A good podcast covering many questions you may have about starting a podcast
* [10 production mistakes podcasters make](https://theaudacitytopodcast.com/10-production-mistakes-podcasters-make-tap194/)

**Bandrew Scott**

* [Podcastage](https://www.youtube.com/channel/UCvOU-zTlankT-JjN3ZzvuKA/featured) - An awesome YouTube channel that provides Gear Reviews and Tests to help you improve your podcast and YouTube audio / video. Seriously check him out.
* [Bandrews YouTube Kit](https://kit.com/podcastage/my-youtube-kit)

**Rachel Corbett**

Rachel is the Director of Podcasts for Mamamia.

* [PodSchool Podcast](https://rachelcorbett.com.au/podschool-podcast/) - Very good advice for beginners to medium experience

**Wil Williams**

* [10 things I wish every podcast would do](https://podcastproblems.wordpress.com/2018/01/19/10-things-i-wish-every-podcast-would-do/) - Things that outside of audio that make your podcast a better experience for listeners, such as accurate descriptions and transcripts 

**Decipher SciFi**

* [How we produce our podcast on Linux at Decipher SciFi](https://chrispeterson.info/how-we-podcast-on-linux-at-decipher-scifi/)

**Tim Ferriss**

* [Podcasting Kit](https://kit.com/timferriss/podcasting-kit)

**Podcast Advocate Network**

* [Podcast Starter Kit](http://podcastadvocate.network/podcast-starter-kit/)

**BufferApp**

* [How to promote a podcast](https://blog.bufferapp.com/promote-a-podcast)

**The Podcast Host**

* [Rode SC6 & SmartLav](https://www.thepodcasthost.com/equipment/microphones/recording-podcast-interviews-with-smartphone-rode-sc6/)

**Matt and Tom**

* [What Matt and Tom Use To Make Videos: The Kit List, 2017 Edition](https://www.youtube.com/watch?v=D1WqlRx2siQ)

**Buzzsprout**

* [Learn How To Create A Podcast Intro Your Listeners Will Love](https://www.buzzsprout.com/blog/podcast-introduction)

**Reddit**

These subreddits are also useful.

* [r/podcasting wiki](https://www.reddit.com/r/podcasting/wiki/index)
* [r/podcasting](https://www.reddit.com/r/podcasting/)
* [r/podcastgear](https://www.reddit.com/r/podcastgear/)
* [r/podcasts](https://www.reddit.com/r/podcasts/)
* [r/podcast](https://www.reddit.com/r/podcast/)

Here are some great threads

* [Growing an Audience From Scratch](https://www.reddit.com/r/podcasting/comments/827m2l/growing_an_audience_from_scratch/)

![sausage making](https://uploads.fireside.fm/images/2/2c1262bc-be8e-476e-92c9-7dabeb91565b/Gh9lcYF3.png)
