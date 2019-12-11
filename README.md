# VapourSynthColab

A Google Colab Environment set up for both conventional and machine learning video processing. Run ESRGAN or MXNet models, OpenCL and CUDA filters, and CPU filters on video frames in VapourSynth scripts instead of reading and writing a bunch of 8-bit pngs, or use VapourSynth filters to pre/post process videos for other ML Colab projects.

![Colab1.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab1.PNG)
![Colab2.png](https://raw.githubusercontent.com/AlphaAtlas/VSSH-Wiki-Images/master/images/Colab2.PNG)

Basic usage:
* Log in to Google, open the notebook: https://colab.research.google.com/github/AlphaAtlas/VapourSynthColab/blob/master/VapourSynthColab.ipynb
* Run the "Check GPU" and "Run This at Startup" cells.
* Run the cell with the example VapourSynth script, or load your own video and edit it.
* Run the "Preview Options" cell to test the script.
* Generate the preview in the preview cell. 
* Process the whole video in a scratch cell. 

For basics on VapourSynth and super resolution filters, see the wiki (and links to other guides) here:
* https://github.com/AlphaAtlas/VapourSynth-Super-Resolution-Helper/wiki/VapourSynth-Basics
I highly recommend stabilizing ESRGAN output with a temporal filter, to reduce jitter, or using a dedicated video model from another repo. Also, keep in mind that Colab's CPU is very slow, so use GPU accelerated filters wherever possible in large scripts.

Grab models for specific kinds of content here, or train your own:
* https://upscale.wiki/wiki/Model_Database
* https://colab.research.google.com/drive/1ygwTH7nN66UEUjD87u8kdFAGoVBzL-Bt

For help, just post an issue, or ask in the Game Upscale or Animation Upscale Discords.
* https://discord.gg/cpAUpDK
* https://discord.gg/sGH8kKc
