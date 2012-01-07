This is a clone of [Icey Robson's CSS compressor](http://iceyboard.no-ip.org/projects/css_compressor/info/)

Change log
==========

* v0.12 > v0.13

  Fixed removing HTML comments. Thank you to Beau for providing the bug report and solution.
  
* v0.11 > v0.12
  
  Thanks to Sam S for these bug fixes:
  
  *	RBGA colour values are no longer broken.
  
  * Many font combining rules have been removed, because they would reset font attributes to their defaults.
  
* v0.10 > v0.11

  * 'white' is converted to '#fff' if the "Convert long colours names to hex" option is checked. Thanks to JTBrinkmann for suggesting that.
  
  * If all four borders are present (border-top, border-left, etc) and have the same properties, they are converted to the shorter 'border' version. Thanks to JTBrinkmann for suggesting that.
  
* v0.9 > v0.10

  Fixed rgba() values being converted. Thanks to Thomas O'Dea for letting me know about that.