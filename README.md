# twitter-unlike-unfollow-cleanup
Clean up your twitter: unfollow, unlike posts, delete your tweets

This is a collection of scripts and solutions I found, mainly so I can keep them in one place and reference when needed.

# How-To
1. Open Chrome browser and go to your Twitter's relevant tab (see below)
2. From Development Tools, open Console
3. Paste the javascript and let it run (might take a while!)
4. If it gets stuck, refresh the browser and repeat as many times as you need

## Delete likes (unlike) 
Open your profile's "Likes" tab and paste [this script](twitter-unlike-script) script in the Console 

- [original gist and discussion](https://gist.github.com/aymericbeaumet/d1d6799a1b765c3c8bc0b675b1a1547d) 

NB: This script will unlike (remove "hearts") from your liked tweets but it will not remove the actual tweets themselves, as far as I can tell. 

### Alternative unlike script 
- [see here](https://github.com/lukejones/delete-twitter-likes/blob/master/script.js) 

## Unfollow and/or remove followers 
Open the list of people you follow and paste [this script](https://github.com/bpawel-bclub/twitter-unlike-unfollow-cleanup/blob/main/twitter-mass-unfollow) in the Console 

- [original script](https://github.com/canpurcek34/twitter-mass-actions/blob/main/twitter-mass-unfollow.js) 

NB: Make sure to change the language to the one you use on Twitter, otherwise it won't work 

## Delete your tweets (and more) 
- use [this app](https://tweetdelete.net/) 

## URL shorteners 
If Tweeter blocks a link to your mastodon instance you can use a URL shortener, e.g. [bit.ly](https://bitly.com/), [tinyurl](https://tinyurl.com/app), or other ones. 



---

[<img src="https://user-images.githubusercontent.com/117116137/208254846-30408428-d511-4983-841f-8e46ea40afd6.png" target="_blank" width="24px" height="24px" alt="@baroquepawel@artsculture.media"> Follow me on mastodon](https://talk.artsculture.media/@baroquepawel?utm_source=github&utm_medium=twitter-unlike-unfollow-cleanup&utm_campaign=ongoing) 
