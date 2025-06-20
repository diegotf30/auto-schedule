# Automatic US Visa appointment scheduling

This script uses Python's Selenium library to automatically schedule appointments for a specific site that doesnt like to give proper appointments

## Requerimientos

* Python 3.6+
* Firefox & [geckodriver](https://github.com/mozilla/geckodriver/releases). 
    * **Note:** Make sure that your geckodriver is in your [PATH](https://medium.com/@01luisrene/como-agregar-variables-de-entorno-s-o-windows-10-e7f38851f11f)

## Configuration
1. Install python library dependencies `pip install -r requirements.txt` (might be more than needed here, didn't use a venv)

2. Add credentials to `config.json`:

    * `sender_email` & `sender_email_password`: Used to send a notification email when an appointment is scheduled

    **Note:** if you have 2-factor auth you will need to generate an [app password](https://stackoverflow.com/a/60718806)

    * `notification_email`: Email that is being notified of scheduled appointment (generally the same as `sender_email`)

    * `visa_email` & `visa_email_password`: Credentails from `[redacted]`


