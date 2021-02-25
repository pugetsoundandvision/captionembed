ABOUT:

This script facilitates embedding captions in the VTT format into video files.
It can be set to either 'burn in' captions or to embed them within the file wrapper.
To function it must have FFmpeg either installed to the computer's path, or in the same repository as the script.


HOW TO USE:

The script has two options, 'burn in' captions or 'embed' captions. These are selected with -b and -e respectively. Default behavior is 'burn in.' The script relies on target VTT files and videos having the same root names. For example: my-cool-movie.mp4 and my-cool-movie.vtt. The script can either be used at individual video/caption targets or directories. If used on a directory, it will attempt to match all detected video and vtt files.

EXAMPLE COMMANDS:

Burn in:
  caption-embed.rb -b my-cool-movie.mp4 my-cool-movie.vtt
Embed:
  caption-embed.rb -e my-cool-movie.mp4 my-cool-movie.vtt
 
