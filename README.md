# OKI AC125A Switching Power Supply


# Overview

The OKI AC125A includes a linear power supply capable of providing -48VDC at 5A.

Replace the OKI AC125A power supply with a Mean Well RSP-500-48 switching supply capable of supplying 48VDC at 10.5A.  Create a 34-⅝” x 2” mounting plate to mount the power supply and meters for measuring current and voltage.

![alt_text](https://raw.githubusercontent.com/hharte/ac125a_ps/master/photos/ac125a_ps.jpg "image_tooltip")

# Mounting Plate

The mounting plate was designed with Front Panel Designer and ordered from [https://www.frontpanelexpress.com](https://www.frontpanelexpress.com/) and arrived a few days later.


# Components

[Mean Well RSP-500-48](https://www.digikey.com/en/products/detail/mean-well-usa-inc/RSP-500-48/7706343) Power Supply

[Illuminated Power Switch](https://www.digikey.com/en/products/detail/e-switch/RBW2ABLKGILFF1/2639098)

[Two LED DC panel meters](https://www.amazon.com/dp/B01DDQM6Z4)


# Assembly

Attach the Mean Well RSP-500-48 power supply to the rear of the power supply front panel using four M4 tapered head screws, 5 mm in length.

To install the LED voltage and current meters, remove the meter circuit board from the plastic housing by carefully bending the tabs.  Pop the plastic housing into the mounting holes, and then carefully re-install the circuit board assembly, taking care not to crack the LED diffuser panel.

The current meter has a range of 0-100A.  As the OKI draws nowhere near this amount of current, and in fact, the Mean Well RSP-500-48 is only capable of supplying 10.5A, wrap the -48V lead 10 times around the  hall effect sensor.  This improves the accuracy of the current meter with a range of 0-10A.  The only drawback to this is that the decimal point is in the wrong place.

