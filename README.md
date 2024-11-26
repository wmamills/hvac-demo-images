# hvac-demo-images

This repo uses git-lfs to store prebuilt images for the hvac-demo repo.
It should normally not be cloned but instead should be left to the
scripts/maybe-fetch script to manage.
That script will fetch images as they are needed.
In this way you will only fetch the images you need and not the whole catalog.

Most images are compressed and some are archives of whole directories.
For this reason the files reday to be used are in the images/ directory and
the sparse catalog is in saved-images/ directory.

A built image will never be overwritten by a saved image but a built image
may be saved.
