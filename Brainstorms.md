# Brainstorms 🧠

I have both [Calibre](https://github.com/kovidgoyal/calibre) and the [Kobo Extended Driver](https://github.com/jgoguen/calibre-kobo-driver) open right now. I need to work off the Extended Driver because I currently use the Kepub conversion (AKA "Send books as kepubs" checkbox) on the Extended tab. And because when using the Extended driver, it's best to disable the KoboTouch plug-in.

 From what I can see in the code, as a Python amateur and infrequent user, the Extended driver inherits the KoboTouch driver, a built-in plug-in in Calibre (so many "in"s). This is my first time dealing with Python development and as a result, inheritance. I believe I will have to inherit the `Collections, covers & uploads` tab from KoboTouch and then add the GUI and all the logic.

# Tracing Code: In progress :)

## Calibre: KoboTouch Plug-in

### kobotouch_config.py file

### driver.py file (the main part of the logic)


## KObo Touch Extended Driver Plug-in

### koboextended_config.py file

### driver.py file (the main part of the logic)

