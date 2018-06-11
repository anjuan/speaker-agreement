# Speaker Agreement Template

I'm often asked how I structure the speaker agreements that formalize the contract between event organizers and myself. This repository contains the LaTeX version of my standard speaker engagement agreement.

## Attribution

This template is based on an agreement orginally created by [Brandon Fryslie](https://github.com/brandon-fryslie) and extensively modified by [Vel](http://www.vel.nz). I've kept a lot of the structure from Vel's LaTeX file, but I heavily modified the contents and added additonal variables.

## Dynamic Variables

This template is designed to be used for creating speaker agreements using LaTeX. It has dynamic variables that you can change based on the event informaton (e.g., event name, venue, session start time, etc.) and static content that will always be the same (e.g., your name, mailing address, etc.).

## Ready to Modify

The terms and conditions in the contract have been cobbled together from a variety of speaker agreements that I have seen in the past. They are meant to provide sample content that you can modify to fit your needs. 

## Structure.tex

You'll need to make sure that you bring the structure.tex file down to your local machine since it contains formatting that the template uses to improve its look.

## Mac Users

If you're using MacOS, edit the structure.tex file and uncomment the font settings for MacOS. Then, comment out the default font settings in the next block. This will improve the look of the rendered document, but you will have to change your LaTeX client to compile with XeLaTeX.

## LaTex Client

You'll need a LaTeX client to modify and use this template. There are several open source multi-platform client options available as either desktop or online applications. I currently use [MacTeX](http://www.tug.org/mactex/).

If you use MacTeX, keep in mind that a number of other files will be created in your directory along with the rendered PDF file. You'll see files with the following extensions: .aux, .log, and .gz.
