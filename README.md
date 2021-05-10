# typhm_store

This is the official repository of the published Typhm beatmaps.

## Notices

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
Therefore, what you need to do in this case is to contact the artist,
tell him/her about this situation, and **ask for his/her permission**.
You may offer to **add a license for the music** so that the uploaded music
will not be abused by people downloading it from here.
You and the artist should reach an agreement upon this.

### How can I state the license of the music I use

You should include the information in the [table](#list-of-music-for-published-beatmaps).

Again, you should reach an agreement with the artist on
which license to create a beatmap for the music
if the original music is not licensed with a license
that allows you to use it without contacting the artist.

## List of music for published beatmaps

| Filename | Artist | Title | Uploaded | License | Contacted |
| --- | --- | --- | --- | --- | --- |
| AhVousDiraiJeMaman | W. A. Mozart (Composer) & S. Ligoratti (Player) | [12 Variations on "Ah, vous dirai-je maman", K.265/300e] | No | CC BY 3.0 | No | 
| offset_wizard | Ulysses | offset_wizard | Yes | CC0 1.0 | Yes |

[12 Variations on "Ah, vous dirai-je maman", K.265/300e]: https://imslp.org/wiki/12_Variations_on_%22Ah,_vous_dirai-je_maman%22,_K.265/300e_(Mozart,_Wolfgang_Amadeus)
