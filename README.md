h264-tools
===========

This is a MacOS release of the following tools


ldecod :
	
	Usage: ldecod <lot of options>
	Decodes 3D H.264 video streams, which ffmpeg cannot do directly

yuvsbspipe :
	    
	    Usage: yuvsbspipe -w <width> -h <height> -l left-stream.yuv -r right-stream.yuv -o output-sbs.yuv
	    Reads 2 YUV streams from 2 files/named pipes and output a single YUV Side-By-Side  or Top-Above stream to a file/named pipe

Which I use in my iMacOS workstream to convert 3D blurays to mkv for viewing on VR devices. 

Also included in the repository for completeness is...

mkv2mkv :
	
	Usage: mkv2mkv input-file output-file
	convert audio/video files with optional H.264 video rencoding and aac audio reencoding.
	3D H.264 input video (with MVC) can be reencoded to Side By Side

naluparser :
	
	Usage: naluparser [-stat] [-v] [-nalucount #] [-mkv] [-annexb] < inputFile > outputFile
	Parses Annex-B or mkv style H.264 NALU packets and optionaly convert it  to another bitsream format
	produces statistics on NALU types used in stream

I don't use these and have no idea if they work.

