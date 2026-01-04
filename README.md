# GreenRC
A touchOSC doc for the BOSS RC-600 6-channel looper.

This version trades the ASSIGN for selecting tracks 5&6, for a tempo slider.
A TAP TEMPO on the interface didn't work for me, but I like this.  Comment in the Forums.
Things were tightened up and beautified.

![GrnRC1](https://github.com/user-attachments/assets/ee041af0-d523-4dca-8dcb-5d77d4018e2f)


1. Instructions are also in the Document notes:
2. Designed for use with the Boss RC600.  
3. __MIDI Channel 1__
4. __PEDAL MODE may need to be set to INC__   will ck and update.
5. __ASSIGNS__ are required on the Boss RC600 for functionality.  Place the MEMORY99A.RCO and MEMORY98A.RC0 on your looper and copy their Assigns to other locations...
4. MEMORY90X.RCO is for sampling, testing, ans setting effects chains. Little else will work when that PHRASE is loaded.
     Once you are happy with the chain and settings save 90 and copy the effects to the phrase(es) you want.

 If you must set your own ASSIGNS, get https://www.rc600editor.com/, and scroll your life away.  ROLAND has nearly 3 pdf pages of possible assigns not including the A-D for banks, and 1-6 for tracks.  There 4 ways to START  At least with Moose's tool you can do it standing up.
    
          __-- Subject To change --__  and the README may not keep up. RC0 files should.

| ASSIGN | CC Source | Target           |
|--------|-----------|------------------|
|  1     |  01       | RHYTHM ST/STOP   |
|  2     |  02       | RHYTHM KIT       |
|  3     |  03       | RHYTHM LVL       |
|  4     |  04       | MASTER LVL       |
|  5     |  15       | IN FX A          |
|  6     |  06       | PEDAL MODE       |
|  7     |  17       | IN FX C          |
|  8     |  18       | IN FX D          |
|  9     |  09       | IN FX A PRM4     |
|  10    |  16       | IN FX B          |
|  11    |  20       | MIC1 IN MUTE     |
|  12    |  12       | RHYTHM VAR       |
|  13    |  13       | CUR TRK LVL      |
|  14    |  14       | CUR TRK NUM 1+2  |
|  15    |  20       | CUR TRK NUM 3+4  |
|  16    |  21       | TEMPO            |

 # For MEMORY90A.RC0


| ASSIGN | CC Source | Target           |
|--------|-----------|------------------|
|  1     |  64       | T FX CR TYP INC  |
|  2     |  65       | RHYTHM LVL       |
|  3     |  66       | MASTER LVL       |
|  4     |  67       | IN FX CR TYP INC |
|  5     |  68       | PEDAL MODE       |
|  6     |  69       | IN FX A          |
|  7     |  70       | IN FX B          |
|  8     |  71       | IN FX C          |
|  9     |  72       | IN FX D          |
|  10    |  73       | IN FX A PRM4     |
|  11    |  74       | IN FX BNK INC    |
|  12    |  75       | TRK FX A         |
|  13    |  76       | TRK FX B         |
|  14    |  77       | TRK FX C         |
|  15    |  78       | TRK FX D         |
|  16    |  79       | TRK FX BNK INC   |


# FEATURES

     This touchOSC Document incoporates nearly every example of working "cool" touchOSC/lua stuff I could find and make to work over Christmas 2025.  If you want to learn those things like I did, it might be a place to start.

* Shiny Radial Faders can be a bit jittery on a low powered device so I have a dialed down version. Most of which is there but hidden and only 1 version will be available.  There could be a button to swith to the "dialed" down version, but I don't think it's that important to try and support crappy hardware. 
* Battery, Clock, and Gig Timer.
* KEY Select is for Manual Vocal effects +3, +5, octave and unison on IN FX 1-4 that are applied only to MIC1 and not recorded on TRK 1-3 on MEM 98,99.  (Most all my PHRASES are set this way) 
* Only IN effects buttons are active on all but 90. (See below) 
* Slider, up/down, preset mem selector
* TRK SEL
* Pads, KIT, Ryhthm var  Genre and Pattern have to be picked up from the PHRASE.  These can be switched per mem/loop/track but they don't let you access them with assigns. 
* #MEM 90 is to audition and set effects chains. On the other set of ASSIGNS, the inc and TRK FX buttons will not be active. Scroll to the appropriate screen on the RC-600 to show them and you can cycle through bank and type and turn them on and off easily.  Get what you like. Save 90. Thenn copy it's effects (THANK YOU! JMT) to other places.  Don't mess up IN Bank A! or the other parts of your PHRASES.

# I'm looking for your best MEMORYXXA.RCO examples.  Maybe with a great pedal mode setup you like and why.  Great rhythm setups or effects chains....  I'm struggling to get a decent Waltz setup I like.

__Will listen to any ideas to make this better.__

Next Up: 3D, touch sensitive PADs.  Right now I don't see a path but I'm on the outlook.  Let me know if you can help!

It's Green so as not to be too bright onstage.

