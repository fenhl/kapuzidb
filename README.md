This is a database of information about [KapUzi's mixtapes](https://soundcloud.com/kapuzenauf). Information will be machine-readable and will include the music tracks as well as quotes.

Format
======

There is a file `mixtapes.json`, which contains a JSON array of strings, each representing one of the mixtapes. The mixtape strings are sorted chronologically by release date.

For each mixtape string `"<mixtape>"`, there is a file `mix/<mixtape>.json`, which contains a JSON object with the following pairs, all optional:

*   `"date"`: date of publication, in `YYYY-MM-DD` format.
*   `"name"`: the mixtape's name, as listed on the blog.
*   `"time"`: UTC time of publication, in `HH:MM` or `HH:MM:SS` format.
*   `"url:`: HTTP URL to the track on SoundCloud.

When a pair is missing from the object, it means the information is currently unknown. Pull requests welcome.
