# Short Answers (Lecture-2)

## Q1
Time domain shows how the signal amplitude changes over time.
Frequency domain shows which frequencies exist in the signal and how strong each one is.
For example, in A1 our signal had 4 frequency components at 500, 600, 700 and 800 Hz,
which were clearly visible as peaks in the FFT plot but not obvious in the time domain plot.

## Q2
In RF receivers, many signals from different sources arrive at the antenna at the same time.
Filtering removes the unwanted frequencies and keeps only the one we want.

## Q3
Modulation shifts a low-frequency message signal up to a higher carrier frequency.
Low frequencies cannot travel efficiently through air as radio waves.

## Q4
The LPF (low-pass filter) in Case 1 was the easiest to design.
It only needed one cutoff frequency value. I chose 550 Hz, which is between
the 500 Hz component I wanted to keep and the 600 Hz component I wanted to remove.
It was straightforward because I only needed to decide one boundary frequency.

## Q5
Before modulation, the baseband signal m(t) had energy only near 100 Hz.
After multiplying with the carrier at 2000 Hz, the energy moved to two new frequencies:
fc - fm = 1900 Hz and fc + fm = 2100 Hz.
The original 100 Hz component disappeared and two sidebands appeared around the carrier.
This is the basic principle of AM modulation.