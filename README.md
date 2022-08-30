# NOVY-STARY-Plane-Crash-Custom-Location-Snippets-PC-And-Console
XML and Json files for my Plane Crash Custom Location between Novy and Stary in a field.

Files that can be put into your Mappos.xml files and the json that goes into your custom folder

PlaneCrashNovy.json file - This file is fine as it is, you can just upload it straight into the CUSTOM folder in dayzOffline.chernarusplus Folder above the DB folder.

PlaneCrashNovyPos.XML - All you do with this file is Highlight ALL of the code, copy it and paste it into your mapgrouppos.xml file, making sure ther is an empty line above and below it. Highly recommend you do this adding in Notepad++ instead of directly on your server, when done just upload it in the dayzOffline.chernarusplus folder over the top of your old mapgrouppos.xml file and thats it your done.

Last thing you need to do is go into your cfggameplay.json file in the dayzOffline.chernarusplus folder, go to line 31 and put in the JSON file name in the brackets and iverted commas MAKING SURE its starts with custom/  EXAMPLE: "objectSpawnersArr": ["custom/PlaneCrashNovy.json"],
If you want to usemore that one custom location at any given time put a comma after the closing inverted commas and add in the other locations JSON file. EXAMPLE: "objectSpawnersArr": ["custom/PlaneCrashNovy.json","custom/TISYnpp.json"],

if you need extra help with this i HIGHLY recommend ScaleSpeeders Youtube Video on this - https://www.youtube.com/watch?v=mFPzPId38Qc this shows you in detail how to upload these files to your nitrado server for PC and Console! Skip to timestamp 23:50 and watch from there as it shows you where to put the files and how to get them there.

Thanks for using my Custom Location and i hope you enjoy it
