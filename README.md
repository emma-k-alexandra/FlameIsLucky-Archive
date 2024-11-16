# FlameIsLucky YouTube Channel Archive

![A screenshot of FlameIsLucky's YouTubeChannel Videos page with many videos displaying a self-destruct date](./readme//2024-11-16.png)

In late 2024, [FlameIsLucky](https://www.youtube.com/@FlameIsLucky) started an [ARG](https://en.wikipedia.org/wiki/Alternate_reality_game) related to their [Where is Mew?](https://www.youtube.com/watch?v=m5gbvKpFEpg) video. As part of this ARG, the channel was changed drastically. Video thumbnails were changed and displayed a self-destruct date.

This project is meant to be an archive of metadata for FlameIsLucky's channel and videos. This includes descriptions, video names, and thumbnails.

## Method

Channel data was downloaded with [yt-dlp](https://github.com/yt-dlp/yt-dlp) using the command

```zsh
yt-dlp --get-comments --write-info-json --write-description --write-all-thumbnails https://www.youtube.com/@FlameIsLucky/videos
```

## Archive Dates

All data in this project was archived on November 16th, 2024.

## Layout

### FlameIsLucky Channel

Metadata about the FlameIsLucky channel including channel description and thumbnails.

### readme

Files used in this README, not from FlameIsLucky channel.

### Videos

Each video gets it's own directory. Each directory is named `{video title} [{video id}]`. Each file in the video has the same name.

- `.description.txt` files contains the description of the video
- `.info.json` contains metadata about the video, including comments on the video
- The `Thumbnails` directory contains all possible thumbnails for the video, including thumbnails that appear when scrubbing the video in the YouTube player.

#### Example

The `Where is Mew?` video is stored in `Where is Mew？ [m5gbvKpFEpg]`

where the video id `m5gbvKpFEpg` can be used to view the view on YouTube at <https://www.youtube.com/watch?v=m5gbvKpFEpg>

## Video Titles

| ARG Video Title | Original Video Title | YouTube Link |
| - | - | - |
| MISSINGNO 1126 | The Race that Changed Everything | [Link](https://www.youtube.com/watch?v=n9SiHr5AZe8) |
| MISSINGNO 1220 | The Fall That Changed Everything | [Link](https://www.youtube.com/watch?v=kpmG1cm_66E) |
| MISSINGNO 1224 | King Ding & The Deep Dark Forest of Chess | [Link](https://www.youtube.com/watch?v=HNlbug7Ms1g) |
| MISSINGNO 1228 | There will never ever be another melee player like Mang0 | [Link](https://www.youtube.com/watch?v=ybcF1_cQcfI) |
| MISSINGNO 1128 | Crowned in Chalk: Climbing's New World Champion. | [Link](https://www.youtube.com/watch?v=6viAiLCcmOU) |
| MISSINGNO 1212 | Magnus's Greatest Comeback (A Chess Documentary) | [Link](https://www.youtube.com/watch?v=ZhmrF10m0jg) |
| MISSINGNO 1208 | Skateboarding's First Ever Gold Medalist (A Yuto Documentary) | [Link](https://www.youtube.com/watch?v=8n7PNB5T97c) |
| MISSINGNO 1216 | 100 Gecs (A Gecumentary) | [Link](https://www.youtube.com/watch?v=MPZfWXiVXAE) |
| MISSINGNO 1204 | There Will Never EVER be Another Melee Player like aMSa | [Link](https://www.youtube.com/watch?v=ZfKH3kOv9hg) |

## Video Files

As the videos are still available on YouTube at the time of writing, I do not feel comfortable including videos files in this project. Please watch the videos on the [FlameIsLucky YouTube Channel](https://www.youtube.com/@FlameIsLucky). They are excellent.
