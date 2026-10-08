# Channel Alignment Analyzer

A browser tool for checking the stop-disk alignment of Hamilton STAR and STARlet pipetting channels from a photo.

**[Open the analyzer](https://jeremyaday.github.io/hamilton-alignment-analyzer/)**

## How it works

1. Take a photo looking straight at the row of channel stop disks, or drop in an existing one (JPG, PNG or HEIC).
2. The page finds each stop disk with OpenCV.js and measures how far each channel sits from the line of the others.
3. You get a table of channels with their deviation, a status and a detection score, plus an annotated image you can download.

The detection threshold can be adjusted and the analysis re-run if a disk is missed.

All processing runs locally in your browser. No images are uploaded anywhere.

## Example photos

The three JPG files in this repository are sample photos you can use to try it out.

## Running it locally

It is a single `index.html` file. Open it in a browser, or serve the folder with any static web server.
