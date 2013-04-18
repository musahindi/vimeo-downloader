vimeo-downloader
================

Bash script to download a video from Vimeo to your computer.  This is originally based on "Vimeo Downloader 0.3" from http://ossguy.com/?p=841

Script has been updated to download a set of videos by defining the Vimeo channel ID and (optionally) the range of videos to download by defining the first and last pages in the page range that contains your desired videos.

If a channel is defined, but the start and end pages are not, the channel's entire video library will be downloaded. 

Usage
-----

Run the following from the command line:

    ./vimeo_downloader.sh -i <video_id>

or

    ./vimeo_downloader.sh -c <channel_name>

or

    ./vimeo_downloader.sh -c <channel_name> -s <start_page>

or

    ./vimeo_downloader.sh -c <channel_name> -e <end_page>

or

    ./vimeo_downloader.sh -c <channel_name> -s <start_page> -e <end_page>