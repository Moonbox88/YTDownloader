# YT_vid_DL (YouTube Video Downloader)

Package for aquiring binary data for YT videos with age restrictions.

# Usage

To use in your project include 'import YT_vid_DL'

Create a class object passing a url (for a YouTube video) string like:
	yt = YT_vid_DL.AgeRestrictedYTVideo(<url-here>)
	
Query if video is age restricted like:
	age_restricted = yt.is_age_restricted()
	
Either way, a binary object for the video is returned by:
	bytes_obj = yt.get_video()

