# note-laser-co


untuk penggunaan mosfet maka output signal dari pwm harus di invert

ini bisa dilakukan dengan membuka file Defaults.h

ubah ini :

#ifndef DEFAULT_INVERT_SPINDLE_OUTPUT_PIN

#    define DEFAULT_INVERT_SPINDLE_OUTPUT_PIN 0

#endif

menjadi 


#ifndef DEFAULT_INVERT_SPINDLE_OUTPUT_PIN
#    define DEFAULT_INVERT_SPINDLE_OUTPUT_PIN 1
#endif
