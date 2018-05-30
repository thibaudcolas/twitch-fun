# Twitch fun

> A place to keep all of my hard-earned Twitch streaming knowledge

## Tools

*   [Twitch](https://www.twitch.tv/thibaudcolas)
*   [OBS](https://obsproject.com/)
*   [KeyCastr](https://github.com/keycastr/keycastr)
*   TODO: a better window position manager

## Hard-earned knowledge

*   Do not use scaled video output – stream with the canvas size.
*   Turn on recordings in Twitch as well as in OBS.

### Twitch

*   Timestamps for Twitch videos: [`?t=01h01m01s`](https://www.reddit.com/r/Kappa/comments/29a47v/psa_when_you_link_to_a_twitch_stream_heres_how_to/)

### ffmpeg

*   Truncate video: `ffmpeg -i input.mp4 -ss hhfrom:mm:ss -to hhto:mm:ss -c copy output.mp4`
*   Concatenate videos: [https://stackoverflow.com/a/11175851/1798491](https://stackoverflow.com/a/11175851/1798491)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Thibaud Colas](https://twitter.com/thibaud_colas) has waived all copyright and related or neighboring rights to this work.
