<p align="center">
	<a href="https://github.com/lap00zza/Grabber"><img src="https://image.ibb.co/mCLbja/grabber_text_small.png"></a>
</p>
<p align="center">
	<a href="https://standardjs.com"><img alt="JavaScript Style Guide" src="https://img.shields.io/badge/code_style-standard-brightgreen.svg"></a>
	<a href="https://travis-ci.org/lap00zza/Grabber"><img alt="Build Status" src="https://travis-ci.org/lap00zza/Grabber.svg?branch=master"></a>
</p>
<p align="center">
	Grab episodes from 9anime!
</p>

## About
Grabber allows you to fetch episode links from 9anime. It currently support grabbing videos from <strong>9anime Server</strong> (ex: Server F4) and <strong>RapidVideo</strong>. You can then couple these links with a download manager to download episodes in bulk.

![](https://image.ibb.co/kKuF25/grabber.png)

## Download
* [Greasyfork](https://greasyfork.org/en/scripts/31010-grabber)

## Usage
1. Install a user script manager. I recommend [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. Install Grabber
3. Open any 9anime watch page. Example: [Shingeki No Kyojin 2](https://9anime.to/watch/shingeki-no-kyojin-season-2.3v16)
4. The Grab All button will appear near the Server. Click it!
5. Make sure to keep a download manager handy. The grabbed links will be copied to your clipboard.

> :information_source: Read [How To Download Episodes](https://github.com/lap00zza/Grabber/wiki/How-To-Download-Episodes) for more details.

> :warning: **If you get a Tampermonkey page requesting origin permission, remember to click allow.**

## What is metadata.json?
![metadata.json](https://image.ibb.co/iR0Mxk/metadata.png)
> **You can use [Grabber Renamer](https://github.com/yumiris/grabber-renamer) by @yumiris to bulk rename files using metadata.json**

Its a small JSON file which helps you keep track of the files names. When you download videos from servers like RapidVideo the file names are always cryptic. This is where `metadata.json` helps you out. This is how it looks like:
```json
{
	"animeName": "ONE PIECE FILM: GOLD",
	"animeUrl": "https://9anime.to/watch/one-piece-film-gold.71vy",
	"files": [
		{
			"original": "bVTiwZTHZS2Lmme.mp4",
			"real": "one piece film_ gold-ep_001-standard.mp4"
		}
	],
	"timestamp": "2017-06-30T15:01:15.622Z",
	"server": "RapidVideo"
}
```

## License
[MIT](https://github.com/lap00zza/Grabber/blob/master/LICENSE)

Copyright (c) 2017 Jewel Mahanta
