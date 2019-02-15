# Rigden-websafe-color-blind-interpolator
high-quality color-blind filter function

Interpolates any RGB color (16,777,216 of them) from up to 8 data-points of the Rigden websafe colorblind table.  Christine Rigden compiled the data by hand through testing of actual color-blind people.  The results seem better than the Daltanize algorithmic process.

input a full-color RGB value
it returns a color-blind simulation for protan, deutan, and/or tritan color-blind people.

It is a plugin for my RGB_Calc class, and requires that:

https://github.com/SoftMoonWebWare/RGB_Calc-color-space-converter

see a demo of the conversion quality at

http://softmoon-webware.com/MasterColorPicker_instructions.php


Note the webafe-interpolator function can support any dataset.
The Rigden colorblind data is inplicitly included.
