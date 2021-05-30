# fix-media-import
Batch script for fixing media after importing it from my iPhone

When I import photos/videos off my iPhone onto my Windows 10 PC (via Photo Gallery), on the videos, the "Media created" date is the date I imported the video, rather than the date the video was taken.  This then causes Windows Photo Gallery to show the photos in the wrong order.

This script uses exiftool (https://exiftool.org/) to update the "Media Created Date" to the FileCreateDate
