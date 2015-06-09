=====================================
  Krowne - ColorPicker - Preference 
=====================================

* Version modified by Krowne.
* ColorPickerPreference class by Sergey Margaritov.

Features:
=========

* Color Area
* Hue Slider
* Alpha Slider (disabled by default)
* Old & New Color
* Color Preview in Preferences List
* Add hex color.
* Color in new format (circle).
* Color activation checkbox (customized)

Requirements:
=============

* Tested with APIv7, but maybe will work with early versions
* This new version works on Android Studio.


Usage:
======

You can see some tests inside:
  ::

    <net.margaritov.preference.colorpicker.ColorPickerPreference
          android:key="color1"
          android:title="@string/color1_title"
          android:summary="@string/color1_summary"
          android:defaultValue="@color/pumpkin_orange"    <!-- Integer resources are also accepted -->
          showCheckBox="true"		                      		<!-- Enable color via Checkbox -->
          alphaSlider="true"                              <!-- Enable Alpha slider via XML -->
          />

To enable Alpha Slider in your code use function:
  ::

    setAlphaSliderEnabled(boolean enable)

Screens
=======
![Alt text](https://github.com/Krowne/Krowne-ColorPicker-Preferences/blob/master/captures/colorpicker.png?raw=true "Captures")
