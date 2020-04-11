                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:1348492
Geeetech Prusa I3 Pro C Dual Extruder Inductive Sensor Bracket by ritzy is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

Installing the inductive sensor for auto bed levelling is the best mod i have done to the printer. Took a little to figure out how it works but print quality has gone way up.

Benefit of this over mount other inductive holders is its mounted at the rear and centre of the dual extruder's.
This gives full corner mapping and means the Z offset is easy to work out.

I first used aluminium tape in the corners but that was a pain and not very accurate. 
So I bought a MK3 aluminium heat bed from ebay ($29au) so inductive sensor detects the aluminium heat bed itself.

I got an 8mm inductive sensor but a 10mm would be better as I am literally 1mm or less from the printed objects.With 10mm you could put 2mm higher.

If you need any help getting the inductive sensor working I'm happy to help.

NPN or PNP doesn't matter as its an easy change in firmware. :)

Mines a 18mm sensor but smaller would mean lighter I guess.

Using SCAD just change the ?? to your sensor dimensions.  cylinder(d = ??, h = 7, centre = true);

# Print Settings

Printer: Geeetech i3 pro C dual extruder
Rafts: No
Supports: No
Resolution: .2
Infill: 100%

Notes: 
ABS would be preferred but I didn't have black so just used PLA.