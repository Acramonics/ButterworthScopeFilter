ScopeFilter
===========

Andrew Martin, Acramonics, January 2026
---------------------------------------

This is a simple Active Butterworth dual 2nd order filter with a
cutoff of 50kHz. This is designed for putting in front of an
oscilloscope when doing audio work where there is HF interference from
computers, etc.

It is powered by a standard 9v wallwart with the power supply section
is taken from the Elektor ESR meter.

Flter component values are from
https://www.changpuak.ch/electronics/Butterworth_Lowpass_active_24dB.php
and tweaked to standard values.

The LTSpice directory contains an LTSpice simulation showing the
frequency response. The Kicad Spice simulator seems to have difficulty
with dual rail power supplies.
