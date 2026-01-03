# GreenRC
A touchOSC template for the BOSS RC-600 6-channel looper.



![GrnRC1](https://github.com/user-attachments/assets/6fd6cb3a-b36b-4298-a533-2c618ca9afcc)

Instructions are also in the Document notes:

Designed for use with the Boss RC600.  

    MIDI Channel 1

Assigns are required on the Boss RC600 for functionality.
Place the MEMORY99A.RCO and MEMORY98A.RC0 on your 
looper and copy their Assigns to other locations...
Maybe the SYSTEMXX.RCO to get prefs...  TRK FX selection
doesn't work with these but MODE 2&3 have all you need if 
you use the MEM Pedal settings.

    MEMORY90X.RCO IS FOR 
    SAMPLING TESTING AND SETTING EFFECTS. 
    Little else will wrok.

    Once you are happy with the chain and settings save 90 and 
    copy the effects  to the phrase(es) you want.

or   -- Subject To change

ASSIGN  CC Source      Target
1                01                      RHYTHM ST/STOP
2                02                      RHYTHM KIT
3                03                      RHYTHM LVL
4                04                      MASTER LVL
5                15                     IN FX A
6                06                     PEDAL MODE
7                17                     IN FX C
8                18                      IN FX D
9                09                     IN FX A PRM4
10               16                      IN FX B 
11               20                     MIC1 IN MUTE
12               12                     RHYTHM VAR
13               13                     CUR TRK LVL
14               14                     CUR TRK NUM 1+2
15               20                     CUR TRK NUM 3+4
16               21                     CUR TRK NUM 5+6

-- or for more effects control set the memory patch to
--  memory 90a.rco has these assigns.

ASSIGN  CC Source      Target
1               64                      T FX CR TYP INC
2               65                      RHYTHM LVL
3               66                      MASTER LVL
4               67                      IN FX CR TYP INC
5               68                      PEDAL MODE
6               69                      IN FX A
7               70                      IN FX B
8               71                      IN FX C
9               72                      IN FX D
10              73                      IN FX A PRM4
11              74                      IN FX BANK INC
12              75                      TRK FX A
13              76                      TRK FX B
14              77                      TRK FX C
15              78                      TRK FX D
16              79                      TRK FX BNK INC

Shiny Radial Faders can be a bit jittery on a low powered device so I have a dialed down version. Battery, Clock, and Gig Timer.

KEY Select is for Manual Vocal effects +3, +5, octave and unison on IN FX 1-4 that are applied only to MIC1 and not recorded on TRK 1-3 on MEM 98,99.  (Most all my PHRASES are set this way) Only IN effects buttons are active on all but 90. (See below) Slider, up/down, preset mem selector. TRK SEL.  Pads, KIT, var.  Genre and Pattern have to be picked up from the PHRASE.  These can be switched per mem/loop/track but they don't let you access them with assigns. 

MEM 90 is to audition and set effects chains. On the other set of ASSIGNS, the inc and TRK FX buttons will not be active. Scroll to the appropriate screen on the RC-600 to show them and you can cycle through bank and type and turn them on and off easily.  Get what you like. Save 90. Thenn copy it's effects (THANK YOU! JMT) to other places.  Don't mess up IN Bank A!

I'm looking for your best MEMORYXXA.RCO examples.  Maybe with a great pedal mode setup you like and why.  Great rhythm setups or effects chains....  I'm struggling to get a decent Waltz setup I like.

Will listen to any ideas to make this better.

Next Up: 3D, touch sensitive PADs.  Right now I don't see a path but I'm on the outlook.  Let me know if you can help!
