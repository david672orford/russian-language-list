## Software for Creating Lessons

The programs listed on this page may proved useful for preparing course
materials. It is all available for free as opensource software. We have
favored software which works on Linux, Microsoft Windows, and Mac OS X.

Most of these programs we actually use regularly. In a few cases we
note why we do not use them or that you are considering them for use.

### Document Preparation
* [Libreoffice](https://www.libreoffice.org/)
	--A free office suite. A continuation of the Openoffice project. Includes
	an excellent word processor called Write. Native format is ODF
	which can be read and written by most word processors.
* [ODF Format Specification](http://docs.oasis-open.org/office/v1.2/cs01/OpenDocument-v1.2-cs01.html)
	--Technical description of the file format used by Libreoffice. ODF files
	are ZIP archives which contain XML files in a format which is relatively
	easy (for a programmer) to parse and convert into other formats such
	as HTML.
* [Odt2html](https://github.com/david672orford/odt2html)
	--There are a number of ways to convert ODT (ODF wordprocessing) documents to
	HTML. For example, Libreoffice can save in HTML format, but the files it
	produces are intended to produce an exact representation of the printed
	document, not to produce good web pages which look good on screens
	of various sizes. In contrast Odt2html puts the production of good clean
	reflowable HTML first while preserving most formatting. To run this
	program you must have Python 2 installed on your computer.

### Audio Processing
* [Audacity](https://www.audacityteam.org/)
	--An excellent audio editor. You can load audio from files in formats
	including MP3 and WAV. If you have a microphone, you can record right
	in Audacity. You can then trim the audio, remove noise, adjust its tone,
	and combine multiple audio clips on a timeline. You can save the project
	to continue working on it later. When you are ready, you can export
	the finished audio in WAV, FLAC, MP3, and OGG formats.
* [Aeneas Forced Aligner](https://github.com/readbeyond/aeneas)
	--Given a recording of speech and a transcript, find the start and end
	time of each utterance. See also detailed instructions at
	[Sil.org](http://software.sil.org/downloads/r/readingappbuilder/Reading-App-Builder-07-Using-aeneas-for-Audio-Text-Synchronization.pdf).
	(Not yet evaluated.)

### Vector Drawing
* [Inkscape](https://inkscape.org/)
	--An excellent vector drawing program which uses SVG as its native format.
* [Inkscape Manual](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/)
	--Book describing the features of Inkscape. Written by one of the
	program's authors.
* [Mastering Inkscape in 2018](http://libregraphicsworld.org/blog/entry/mastering-inkscape-in-2018)
	--Blog posting with recommendations of books and video lessons on how
	to use Inkscape
* [Isometric Projection in Inkscape](http://ahninniah.blogspot.com/2013/04/isometric-projection-in-inkscape.html)
	--Tutorial in drawing pseudo 3D pictures as done in technical drawings

### Raster Image Editing
* [Pinta](https://pinta-project.com)
	--An easy-to-use image editor. Can be used to draw like MS Paint. Can crop photos
	and adjust their color. Can load and save in BMP, PNG, JPEG, TIFF, and other
	formats, but seeminly not GIF.
* [GIMP](https://www.gimp.org/)
	--The Classic opensource image editor. An answer to Adobe Photoshop. Can be
	bewildering for the casual user.
* [Imagemagick](https://www.imagemagick.org)
	--If you need to convert one or two images, you can use one of the raster
	graphics editors described above. But if you are processing hundreds
	of images, you are better off using Imagemagick. It can be used as a
	command-line program or you can use it as a library from your favorite
	programming language.
* [Krita](https://krita.org)
	--Another answer to Photoshop. Has Linux and MS Windows versions, but may
	not have a MacOS X version.
	(Not yet evaluated.)

## Video 
* [VLC](https://www.videolan.org)
	--A good solid all-around video player which will play most any file.
	Has classic media player controls.
* [Openshot Video Editor](https://www.openshot.org)
	--We used to recommend this editor because it is reasonably easy to use.
	The 1.x version became a bit unstable once projects reached a certain
	level of complexity, but there was a version 2.x in progress which was
	supposed to fix that. But years have gone by and while there are
	regular releases in the 2.x series, version 2.4.4 is still unusable,
	mainly because it cannot play the video without serious stuttering.
* [Shotcut](https://www.shotcut.org)
	--Based on our initial evaluation, this program is much better than
	Openshot. It is much easier to trim your clips and they play smoothly.
* [FFmpeg](https://www.ffmpeg.org)
	--Very capable command-line program for converting audio and video files
	from one format to another.
* [Vidcutter](https://github.com/ozmartian/vidcutter)
	--(Not yet evaluated.)

### 2D Animation
* [Synfig Studio](https://www.synfig.org)
	--2D animation studio. Animation is done by defining keyframes which
	show where the parts of a drawing should be at particular times. The
	program interpolates between these positions to determine where the part
	should be at intermediate times. Exports to video. Attempts to create
	exporters for web animations (SVG) have made little progress.
* [Synfig Tutorial](https://opensource.com/article/16/12/synfig-studio-animation-software-tutorial)
	--An article which introduces Synfig Studio and shows to to start using it
* [Pencil](https://www.pencil2d.org)
	--(Not yet evaluated.)
* [TupiTube](http://www.tupitube.com/)
	--(Not yet evaluated.)

### Stop Motion Animation
* [qStopMotion](http://www.qstopmotion.org)
	--Program to take a series of photos using a camera connected to your
	computer and later assemble them into a video.

### 3D Modeling and Animation
* [Blender](https://www.blender.org)
	--This is the definitive opensource 3D modeling program. It is very capable
	and serious users can get good work done quickly. However it requires a serious
	time commitment to learn it, so it is not suitable for occasional use to create
	a few simple models.
* [Art of Illusion](http://www.artofillusion.org)
	--Easy-to-use 3D modeler. Written in Java, so it will run on most computers.
	Saves in its own inscrutible format, but can export in OBJ and VRML formats.
* [Sweet Home 3D](http://www.sweethome3d.com)
	--Easy-to-use program for creating 3D models of rooms with doors, windows, and furniture
* [X3dom](https://www.x3dom.org/)
	--Javascript library for displaying a 3D model on a webpage so it can be
	zoomed and rotated by the viewer.
* [Panda 3D](https://www.panda3d.org)
	--A free game engine programmable in Python.
	(Not yet evaluated.)

### Other Software Lists
* [34 open source tools for creatives](https://opensource.com/article/16/12/yearbook-top-open-source-creative-tools-2016)
* [Sil Language Technology's Products](http://software.sil.org/products/)

