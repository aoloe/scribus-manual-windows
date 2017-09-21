# Scribus and Windows

## Fonts

### Adding fonts to Windows

If you have have downloaded a new Font, you will first have to install it, to make it avalaible to Scribus.

If the fonts came packed in a zip file, you'll first have to unzip the archive.

In all versions of Windows you can install fonts through the Fonts tool in the Control Panel: Launch it and drag and drop the unzipped font files to it.

### Adding custom fonts directories

If you don't want the fonts to be available to all your programs but only in Scribus, you can create a directory where you will place your fonts and add that directory to the ones used by Scribus:

- In Scribus close all your documents.
- In the preferences activate the Fonts section and click on the "Additional Paths" tab.
- Use the "Add" button to add a new directory to the list of the custom fonts paths.
- Close the preferences by clicking on "OK" and restart Scribus.
- Now the fonts that are placed in that directory will be available in Scribus (but you will have to restart Scribus each time you add a new font).

### Using a different Python interpreter

in the wiki there is an howto

https://wiki.scribus.net/canvas/Windows_Full_Python_Integration

but it does not seem to be working.

what seems to be working:

- rename the scribus' python directory so that scribus cannot find it
- then scribus will detect your system python
- warning: the system and the "scribus" pythons must be "binary" compatible. at the moment of writing you can use python 2.7.x with 10 <= x <= 13
