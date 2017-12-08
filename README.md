# HIRAX Site Bot

Scripts to perform regular reports from the site as well as to monitor for these reports in case something has gone wrong.

The wrapper scripts are machine/user specific. hourly_report runs as the acq-user user on the site machine while bot_checkin runs as devin on the acru webserver.

These are currently very ad-hoc WIP scripts. More advanced monitoring should be done with a more structured approach.

Requires the hirax_tokens.py file for API tokens. Contact devin.crichton@gmail.com if you need this.
