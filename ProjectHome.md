# Overview #
Phoshare allows you to export and synchronize your iPhoto or Aperture library to a folder tree. It preserves both the original and modified image, your event and album organization, and applies your iPhoto titles, descriptions, keywords, face tags, face rectangles, places, and ratings to the IPTC/EXIF metadata of your images. You can export a full copy of your library, or just build a tree of linked images that require very little additional disk space. You can re-run phoshare at any time to synchronize any changes made in iPhoto to your export tree quickly. phoshare works well with file-system based photo management tools like Picasa, Adobe Bridge, or Windows Live Photo Gallery.

[Dan Warne](http://danwarne.com/) has written a blog post on [how to back up your iPhoto library to Dropbox](http://danwarne.com/backup-iphoto-library-dropbox-resize-images-save-space-2/) with Phoshare.

Phoshare is written in Python, and is easily customizable by just editing the Python scripts.

# Documentation #
Use the [Documentation](http://www.google.com/url?q=https://sites.google.com/site/phosharedoc&usg=AFQjCNHQRNA6miLUmwpUh3z1yHnxbucp7w) link for the latest updates and "How To" information, and the [user group](http://groups.google.com/group/phoshare-users) for feedback and discussions.

# iPhoto 9.4 and Aperture Users - Please read! #
If you have upgraded to iPhoto 9.4, or are using Aperture, functionality of Phoshare will be limited:
  * No export of keywords (iPhoto 9.4 no longer shares keyword information).  In Aperture, you can work around this with Metadata -> Write ITPC Metadata to Original.., and re-generating your previews after you changed keywords.
  * Face tag regions will be based on the original image. So if you have cropped, rotated, or straightened an image, the exported face tag regions will not match the faces.
  * Downloaded images (e.g. from MobileMe, Facebook, etc.) are not visible to Phoshare, and will not be exported.
  * If you have edited an image, Phoshare can now only export the modified image, but not the original.

# Updates #
The most recent version of Phoshare is 1.5.1, posted on 9/31/2012. This version fixes some issues with iPhoto 9.4. Phoshare has been tested with iPhoto 6 and newer and with Aperture 3.1.2 or newer, running on OS X Leopard through Moutain Lion.

If you are using an older version of iPhoto (e.g. iPhoto '09 and earlier), I recommend you download Phoshare 1.4.7.

# Future of Phoshare #
In October 2012, I made the difficult decision to no longer actively develop Phoshare. The limitations introduced by iPhoto 9.4 no longer make it a very attractive tool. See [this post](https://groups.google.com/forum/?fromgroups=#!topic/phoshare-users/moWsMcD5SdQ) for more details.



