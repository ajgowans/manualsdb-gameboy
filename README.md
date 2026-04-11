# The MiSTer Manuals DB - Nintendo Game Boy

This is a database for the MiSTer project that downloads the English manuals in .pdf form for the Nintendo Game Boy to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manualsdb-gameboy]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-gameboy/db/db.json.zip
```

Or download this .ini file and put it in /media/fat https://github.com/ajgowans/manualsdb-gameboy/blob/db/downloader_ajgowans_manualsdb-gameboy.ini
