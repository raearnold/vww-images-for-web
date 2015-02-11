# Images for the Web and Print
Presentation and supporting assets for the Vermont Works for Women Step Up to IT Image Manipulation &amp; Photoshop workshop.

Below is a summary of the slides and all resource links.

## Image Types

- Raster Images (JPG, PNG, GIF, etc…)
	- **Pixels** (a.k.a. bitmaps)
	- Used for most web graphics
	- Cannot be enlarged
	- Each format has specific advantages 
- Vector Images (EPS, SVG, etc…)
	- **Math, Paths, XML**	 
	- SVG created for web use, others are mainly print
	- Can be scaled up without losing quality

## Image Resolution and Quality
### Aspect Ratio and Orientation
Regardless of print or web, understanding aspect ratios and orientation is vital to resizing and using images. While you can crop images to different aspect ratios or orientations, you may lose vital parts of the graphics. Portrait orientation-images that won't work for banners, backgrounds, etc. on desktop devices might be well suited for mobile, but you'll often need a way to support both. Likewise, a 4:3 image won't work well if your users all use 16:9 screens.

### Web / Screen Resolution
With the rise of high-density displays (e.g. Retina), "standard" screen resolutions are becoming tiered. As Web developers need to support multiple screen densities, vector graphics are playing a larger role so that multiple sizes aren't needed for each image on a website. 

### Print
Standard minimum quality for printing is 300 DPI (newer printers often use 600 DPI). This means that a 640x480px (.3 Megapixel) image will print at ~2.1x1.6".

You need at least 2 MP (1600x1200px) for a reasonable 4x6" photo print, and double that for a full-page graphic.

Note that DPI (or Document Size) in Photoshop has no effect on screen display size. Screens are all about pixels.

## Manipulation Basics: Resizing and Cropping

We're demoing in Photoshop for the sake of the course, but many image editing programs allow you to resize and crop your photos.

[Pixlr Editor](http://apps.pixlr.com/editor/) is a free web-based editor that should look familiar to Photoshop users.

[Gimp](http://www.gimp.org/) is a well-known free Photoshop alternative that runs on Windows, Mac, and Linux.

[Gimpshop](http://www.gimpshop.com/) a Photoshop look-a-like port of Gimp, also free.

[Affinity Photo (Beta)](https://affinity.serif.com/en-gb/photo/) a new photo editing program for OSX. Free in beta.

[Pixelmator](http://www.pixelmator.com/mac/try/) one of the best rated Mac alternatives to Photoshop. Free 30-day trial, $29.99 after.

Remember: keep aspect ratio and intended device in mind when resizing or cropping an image.

## Optimizing Images for the Web and Print

**Lossy:** affects the quality of the image. High-levels of compression can be very obvious, causing "artifacts". 

**Lossless:** does not affect the visual quality of the image. Works by using a variety of compression algorithms and strips unneeded metadata.

### Web

#### Demo: Save for Web and Devices in Photoshop
"File > Save…" isn't enough for the web. Photoshop provides handy tools to reduce your file size.

#### Even Better Image Compression

Photoshop does okay for JPGs, but their PNG compression isn't the best—you should always run these files through a better PNG compression program. Trying additional options for your JPGs can't hurt.

[TinyPNG](http://tinypng.com/) (and [TinyJPG](http://tinyjpg.com/)) is a great free, online application for PNG and JPG compression. It is lossy, and isn't good for batch processing, but for a few images now and then, it's a good option.

[Kraken](https://kraken.io/) isn't completely free, but it allows you to choose lossy or lossless, and resize images with a paid subscription. If you're doing a lot of work with images, it could be worth it.

There are a variety of other options for both Windows and Mac. Do a web search for "image compression <your OS>" and try a few to see what you like.

###Print

Generally, the larger the file resolution, the better, depending on what your printer can handle. But you should consider color profiles, color modes (RGB vs CMYK), and your document size settings before printing.

## Placeholders
Sometimes, you need a few basic images while waiting for actual assets. Don't worry, the Web has many resources, including any number of placeholder image APIs.

[Lorempixel](http://lorempixel.com/) has a variety of categories and options. Most of the images in this presentation came from here. 

[Placehold.it](http://placehold.it/) is a quick and easy way to get a plain graphic of any size, with text overlay.

… and many others with amusing niches—[Fill Murray](http://www.fillmurray.com/), [{place kitten}](http://placekitten.com/), [baconmockup](http://baconmockup.com/), [Place Creature](http://placecreature.com/)





