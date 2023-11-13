# 3dprinterconfigs
These are the PrusaSlicer and Klipper configs for my Artillery Genius Pro. My printer has stock hardware except for a magnetic PEI bed. 

The Klipper config should be plug and play for any Artillery Genius Pro except for a couple of things:
  1.  I use ResHelper to automate some of the input shaping resonance measurements. If you don't want to use those scripts, comment out [include reshelper.cfg].
  2.  The filament runout sensor does not work with klipper using the stock connector. My config assumes you use the otherwise unused z-stop connector instead. If you don't want to do that, comment out the [filament_switch_sensor my_sensor] section.
