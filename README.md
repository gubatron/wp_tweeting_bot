# wp_tweeting_bot

Python Tweeting bot to promote the last N posts of a blog on twitter.

Your tweets won't be read by all your followers if you just tweet them once.
Your tweets will be more attractive if they have image attachments.

This bot, fetches your last posts titles and featured images and it will tweet up to N last posts found every time it runs.

Ideally you should set it up to run on a cronjob every few hours, so you can keep your last posts on rotation.

# Usage
Make sure you have all the required libraries as specified by the [requirements.txt](requirements.txt) file.

`python3 -m pip install -r requirements.txt`

Add as many sections on your config file for as many blogs as you need.
See [config.conf.sample](config.conf.sample) (save it as `config.conf`)

Simply run `./wp_tweeting_bot <config_file_path>`
