# PLEASE READ!

This is a bot for buying a sneakers from the Israeli Snkrs website ON RELEASE DAY.
This is a CLONED version from the original developer to make this bot work on the Israli website.

All the credits belongs to the original developer: https://github.com/alexschimpf/Snkrs-Bot
Visit his Repo for better understanding about the bot.

Quick notes:
I haven't tested the bot, but my friend did.
For newbies, this bot WONT steal your credit card info. You can verify that by checking the full code (main.py).
If you found a bug, report it with full console Log.


# Getting started

There are a few requirements to run the bot. First, you'll need to install `Python 3.7` or greater. The instructions below show you how to do this in several operating systems

Next, we have provided the web drivers for MacOS, Linux, and Windows, but if they're not there, or you want something more up-to-date than the included drivers, you'll need to download them yourself with the instructions below

Finally, the program is run from the terminal (command line), so you should familiarize yourself with running python programs from the terminal [here](https://realpython.com/run-python-scripts/)

## Downloading python

This needs to be Python version `3.7` or up

MacOS
   * From Python's official website [here](https://www.python.org/downloads/mac-osx/)

Windows
   * From Python's official website [here](https://www.python.org/downloads/windows/)

1. The selenium webdrivers for your chosen browser


## Installing the web drivers

* Visit the original repo (https://github.com/alexschimpf/Snkrs-Bot) to learn how. 


# Configuration options

Here is a list and description of the different arguments to use for the script:
מתורגם גם לעברית.
<b>--username</b>
* Username for login
* האמייל של המשתמש

<b>--password</b>
* Password for login
* הסיסמא של המשתמש
<b>--url</b>
* URL for desired shoe
* הקישור להשקה
* Size parameter can also be passed in (for example: https://www.nike.com/launch/t/kobe-5-protro-bruce-lee?size=11). In this case, `--shoe-size` and `--shoe-type` will be ignored

<b>--shoe-size</b>
* Self-explanatory
* גודל הנעל (לפי האתר הישראלי!)

<b>--shoe-type</b>
* Men's (M), Women's (W), Youth (Y) or Child (C)
* סוג נעל, גברים, נשים.
* For special releases (i.e. Air Presto), can pass in XXS, XS, S, M, L or XL. You do not need to pass in shoe size

<b>--cvv</b>
* Card Verification Value for your stored credit card
* May not be needed in some cases (for example, if you have previously purchased a release with a stored credit card)
* שלושת ספרות מחורי הכרטיס המקושר למשתמש,

<b>--shipping-option</b>
* STANDARD, TWO_DAY or NEXT_DAY
* לא רלוונטי לישראל

<b>--shipping-address</b>
* If given, the bot will attempt to add a new shipping address in some scenarios
* כתובת, מומלץ להוסיף למקרה והבוט ייתקע לפי הדוגמא למטה.
* In some cases, checkout will not proceed without adding a new shipping address. If you are unsure, include it
* Must be in this format: '{"first_name":"John", "last_name":"Doe", "address":"1313 Mockingbird Lane", "apt":"", "city":"Long Beach", "state":"CA", "zip_code":"90712", "phone_number":"9999999999"}'

<b>--login-time</b>
* If given, the bot will pause until a specific time before it logs in (can be any datetime format)
* מתי הבוט ייתחבר למשתמש, לא חובה אבל מומלץ.
* דוגמת זמן "2021-03-04 12:59:50"

<b>--release-time</b>
* If given, the bot will pause until a specific time before it purchase the sneaker (can be any datetime format)
* מתי הבוט ייפעל, דוגמת זמן כמו הסעיף שלמעלה

<b>--screenshot-path</b>
* If given, the bot will take a screenshot of the page after purchasing and save it at the given file path (may be useful for debugging)
* הבוט יצלם צילום מסך אם הצליח לקנות.

#<b>רשמית הפקודות המלאה:</b>
https://github.com/alexschimpf/Snkrs-Bot