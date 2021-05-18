# typhm_store

This is the official repository of the published Typhm beatmaps.

## Notices for beatmap users

### How to play a beatmap in the game

Select "Browse store" and type in the filename of the beatmap you find here (without extension).
See the [README of Typhm](https://github.com/UlyssesZh/typhm#playing-through-browsing-the-store).

### Why cannot I play a beatmap

Since most pieces of music used by beatmaps are specified using URL
whose domain is different from ulysseszh.github.io,
and it does not allow ulysseszh.github.io to get access to resources on it,
you may meet problems when trying to play such beatmaps according to the
[same-origin policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy).
To circumvent this problem, you have to install plugins to modify the browser
you use to force it to allow accessing to resources from various origins.
One of the recommendations is
[Moesif Origin & CORS Changer](https://chrome.google.com/webstore/detail/moesif-origin-cors-change/digfbfaphojjndkpccljibejjbppifbc)
(a chrome extension).
Note that forcing Cross-Origin Resources Sharing (CORS) can
make your computer potentially vulnerable to network attacks,
so only enable forcing CORS
when you trust the source of the music for the beatmap you are playing
and disable forcing CORS after you finish playing.

In the [list of music](#list-of-music),
whether a music is public resource (thus available without forcing CORS) is indicated.

## Notices for beatmap creators

### How to create a beatmap

Use any text editor you like to create and edit a file with extension `.typhm`
and refer to [README of Typhm](https://github.com/UlyssesZh/typhm#how-to-compose-a-beatmap).

You can refer to beatmaps here as examples.

### How do I know whether I can use a music

Most music are protected by copyrights.
Before you create a beatmap on a certain piece of music,
you should check whether or not its creator has explicity stated usage terms.
This information can often be found in description sections
of an artist's music release platforms
(e.g. Bandcamp, Soundcloud, YouTube)
or their personal website.
If a song is licensed under a [Creative Commons License](https://creativecommons.org/)
or is available for non-commercial use,
it is safe to create and submit a beatmap for it.

If you want to create a beatmap for a song and its usage rights are not clear,
it is recommended to reach out to its artist for permission.
Most artists have contact methods labeled on their music release platforms,
personal websites, and social media.
You should explain to them clearly how their music will be used.
Refer to [how you should use a music](#how-should-i-use-a-music).

### How should I use a music

The **only** way you use a music is to specify the URL of it
in the [`audioUrl`](https://github.com/UlyssesZh/typhm#audiourl) item
of the header of your beatmap.

The most recommended way to get the URL of an audio file
is to copy the download link of it from its official release platform.

However, in most cases, the music is **not** available for download
through its release platform.
In this case, you should ask the artist for a URL for the audio file.
Tell him/her that this means making the URL public and
allowing all people to download the audio file through the link.

In other cases, the artist do not provide you with a link but just the audio file.
Then, you have to upload the audio file to this repo (typhm_store)
and specify `audioUrl` through [jsDelivr](https://www.jsdelivr.com/).
Tell him/her that this means making the audio file public on GitHub
and allowing all people to download it.

*Attention*:
If an audio file is not available for downloading through its official release platform,
it probably means that **its artist does not want to make it public**.
However, attaching the download link here or
uploading the audio file to this repo (typhm_store)
means making it availble for the public to download.
Whether the audio file is uploaded to this repo is
indicated in the [list of music](#list-of-music).
Therefore, what you need to do in this case is to contact the artist,
tell him/her about this situation, and **ask for his/her permission**.
You may offer to **add a license for the music** so that the uploaded music
will not be abused by people downloading it from here.
You and the artist should reach an agreement upon this.

### How can I state the license of the music I use

You should include the information in the [list of music](#list-of-music).

Again, you should reach an agreement with the artist on
which license to create a beatmap for the music
if the original music is not licensed with a license
that allows you to use it without contacting the artist.

## List of music

Not including [offset_wizard](https://github.com/UlyssesZh/typhm_store/blob/master/offset_wizard.typhm).

The list items:
- Artist(s):
The artist(s) (music author(s)).
Should be the same as specified in beatmaps.
- Title:
The title of the music.
Can be different from as specified in beatmaps when the beatmap
only includes part of the original music.
- Source:
Where the music can be found.
- Public:
Whether the audio file can be accessed without forcing CORS.
See the [notice above](#why-cannot-i-play-a-beatmap).
- Uploaded:
Whether the audio file is uploaded to this repo.
- License:
What the license of the music is.
- Contacted:
Whether the beatmap author has already contacted the artist of the music.
- Beatmap(s):
The list of beatmaps using the music.

| Artist(s) | Title | Source | Public | Uploaded | License | Contacted | Beatmap(s) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| W. A. Mozart (Composer) & S. Ligoratti (Player) | 12 Variations on "Ah, vous dirai-je maman" | [IMSLP](https://imslp.org/wiki/12_Variations_on_%22Ah,_vous_dirai-je_maman%22,_K.265/300e_%28Mozart,_Wolfgang_Amadeus%29) | Yse | No | CC BY 3.0 | No | AhVousDiraiJeMaman |
| EBIMAYO | GOODRAGE | [AB-Sounds](https://ab-sounds.com/bms/) | No | No | CC BY-NC | No | GOODRAGE |
| Scott Holmes Music | Stomps and Claps | [Free Music Archive](https://freemusicarchive.org/music/Scott_Holmes/media-music-mix/stomps-and-claps) | No | No | CC BY-NC 4.0 | No | StompsAndClaps |
