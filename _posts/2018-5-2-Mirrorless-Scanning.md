---
layout: post
title: Mirrorless scanning
---
When starting to shoot film one of the first problems for developing at home was the need to scan at home as well.

Looking at the different approaches to this problem I decided on trying a camera with a macro lens. For this I use my good old Sony A6000. I picked up a Sony 30mm macro lens for a little over 100 euros and started trying to get good scans.

The first setup I had was a tablet computer screen displayed nothing but white. I needed to lift the film above the tablet quite a bit in order to not show RGB structure of the screen.
![_config.yml]({{ site.baseurl }}/images/DSC_1071.JPG)
Tablet raised position

One of the problems that showed up near right away was the fact I had no good way to keep the camera stable. I added in a cheap copy stand in order to keep the camera stable and mostly level with the film.

At this point I judged the main problem in my scans to be image flatness. Flatbed scanners use film holders which are supposed to keep the film mostly flat. I bought a holder for a Plustek film scanner. The holders are really simple and don't actually do much to keep the film flat. They still curl quite a bit. Flatness also isn't uniform over the piece of film.
![_config.yml]({{ site.baseurl }}/images/DSC_1072.JPG)
Tablet with filmholder

In processing scanned color negatives I had a very hard time getting accurate colour. When I compared different computer screens I had it became quite obvious that what is white according to one screen isn't the same colour temperature as white on another screen. Film also isn't calibrated for the target colour temperature of most computer monitors (D65, 6500K). Film is instead calibrated for somewhere around 5200K assuming normal daylight film. I bought a small cheap 4x5" light pad which is supposed to have a near 5000K temperature.
![_config.yml]({{ site.baseurl }}/images/DSC_1068.JPG)
Lightpad without filmholder

A light pad has a number of advantages over a computer display as a light source:

    A light pad does not have an RGB backlight to show up in the scans. Mounting height is therefore no longer a concern.
    A light pad has more uniform lighting than a computer display, most computer displays are edge let where as a light pad has lighting all over the surface area.
    A light pad is MUCH brighter than any computer display. This allowed me to cut my shutter speed by a lot of stops.
    A light pad has a non reflective surface which is not made out of glass and does not suffer newton rings.

At this point I no longer felt I needed to change my scanning hardware, yet I still didn't like the end result I got from scanning. In Photoshop when importing the raw files I noticed I very often clipped the blue channel. This turned out to be quite a problem when I went to invert the image since the blue channel simply lacked information. To remedy this I set the camera white balance to the lowest possible point, in my case 2500K. This is part negates the mask of the negatives but more importantly, it makes it so none of the RGB channels are blown out for a normal exposure. Files in Photoshop were easier to edit with a low colour temperature than they were with a high one.
![_config.yml]({{ site.baseurl }}/images/sloot.jpg)
Manual grading

Editing files was still very much a long term process with a lot of manual labour. Some files I never managed to get to a state with good colour.
![_config.yml]({{ site.baseurl }}/images/missende_ruit.jpg)
Abandoned house - Manual processing
Desperately trying to find a remedy I wound up trying some exotic software. When I saw ColorPerfect which is a plugin for photoshop to manage film color grading I gasped at the price but was glad to see a free trial available. I opted for the trial and was amazed by how good the colour looked without even turning any settings.
![_config.yml]({{ site.baseurl }}/images/colorperfect.jpg)
Abandoned house - ColorPerfect

This tool alone has made the biggest improvement in my entire scanning process. It was a magical experience, no matter what image I gave it the program would find a sane presentation. A lot of hours, about the price of a dedicated film scanner and a lot of pain later I got what I assume are decent camera scans. Sadly I am very much not yet satisfied by these results. Both tonality and resolution seem to leave something to desired. To remedy this I am strongly considering getting either a drum scanner setup or moving to a format larger than 35mm film. Either way I will be retiring the camera scanning setup.
