# dreamcast-media-center
Multi-Media Player for the Sega Dreamcast

Dreamcast Media Center v.2.0 (C) 2011-2013 Josh PH3NOM Pearson

This software uses works derived from the independant JPEG group.

All libraries that are used under GPL license include original documentation.

All work created by me is free for public use and or modification.

First you need to build the libraries:

OpenGL (Beta Build)      
libopengl: GL/makefile

Dolby Digital Audio Codec:
liba52: liba52/liba52/makefile

FLAC Audio Codec:
libflac: libflac/src/libFLAC/makefile

MP4/AAC Audio Codec:
libfaad_2.27: libfaad/libfaad/makefile
libmp4ff: libfaad/common/mp4ff/makefile

MP3 Audio Codec:
libmpg123_1.13.1: libmpg123/libmpg123/makefile

Mpeg2 Video Codec:
libmpeg2: libmpeg2/libmpeg2/makefile

XviD Video Codec:
libxvidcore_1.3.0: libxvid/src/makefile

Then you can build DCMC main binary

Supported Formats:

MP4/AAC Audio Codec:
-M4A Audio (.m4a)
-AAC Audio (.aac)
-MP4 Audio (.mp4)
-iTunes Audio Supported
        
MP3 Audio Codec:
-MP3 Audio (.mp3)

FLAC Audio Codec:
-FLAC Audio (.flac)( Audio Player is hardcoded to 16bit )

Dolby-Digital Audio Codec:
-AC3 Audio (.ac3)( Audio Player is hardcoded to 44.1kHz Stereo )

ADX Audio Codec:
-ADX Audio (.adx)
-SFA Audio ( used in SOFDEC video )

Mpeg2 Video Codec:
-MPEG2 Video (.mpg)( mp2 or mp3 audio )
-MPEG1 Video (.mpg)( mp2 or mp3 audio )
-SOFDEC Video (.sfd)( adx audio, experimental )
      
XviD Video Codec:
-AVI Video (.avi)( mp3 or ac3 audio up to 6ch )
-DivX Video (.avi)( mp3 or ac3 audio up to 6ch )

Image Codecs: ( maximum 1024x1024 resolution )
-JPG Image
-PNG Image
-PVR Texture

Applications:
-Unsrcrambled binary loader

LIMITATIONS:
-On an SD Card, maximum bitrate for any media file is ~656kbps.
-On a CD, maximum bitrate for video files is ~1.4mbps