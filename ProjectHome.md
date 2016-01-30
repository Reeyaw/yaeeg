**yaEEG** is an acronym for Yet Anothe ElectroEncephaloGram, but for sure, it can be extende to:
  * yaEMG: for muscles
  * yaEOG: for ocular muscles
  * yaECG: for heart (cardio)

this project involves development of hardware and specific software.

## Project Organisation ##
This project is in initial phase, before doing any research on software, a hardware (prototype of) is required.

The hardware is Arduino compatible, so the most of the signal processing is supposed to be done there.

The software is the more complex. We are going to have 2 fronts:
  * Firmware: that goes to Arduino/PIColino
  * Utility: this piece will go to the computer for more powerful processing

## Hardware Consideration ##

The hardware is somewhat critical. Dealing with lower and weak signals, requires a sort of  estability provided by specific components. But in another hand, we must be careful.

Attaching electronic devices around your body is not a good idea - EVER! But when dealing with lower voltages, it can be safely tied if you observe some rules:

  1. make sure the device is isolated from the mains
  1. make sure the device tied to your body delivers only lower voltages (less than 10V)
  1. do not use it in rainy days or under situation that might pose you to a electric discharge.

## Disclaimer ##

The device here and all the results from this research is not suitable for health care and that should never be built and used for that! THIS IS A RESEARCH ONLY DEVICE.

The author and associated developers are not responsible for any injury caused by misuse of the knowledge shared here. IT'S YOUR OWN RESPONSIBILITY.

## About the logo ##
This project have a logo of the curve PQRST from a electro cardiogram. Well, what's EEG have to do with that? Almost everything. To assess the circuitry, during prototype phase (veroboard) I used against my chest... Wow! What a surprise see such curve in my "Processing" interface (not like that, but similar to the logo)

## Further documentation ##
This site is not intended to document, detail or simply blog each conquer... so take a look in http://mmc-zaap.blogspot.com.br/ and watch out for the information there