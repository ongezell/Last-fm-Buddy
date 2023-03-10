# Last.FM Buddy

Customize your Last.fm page with a personalized buddy and CSS styles using this userscript. Make your profile stand out and show off your personality with this script.

## Installation

To install this userscript, you'll need a browser extension that allows you to run userscripts. Some popular options include:

- Tampermonkey (Chrome, Firefox, Safari, Microsoft Edge)
- Greasemonkey (Firefox)

Once you have one of these extensions installed, Visit the script page at https://ongezell.com/userscripts/lastfm-buddy.user.js
- Click the "Install" button on the userscript manager extension.
- Accept the prompts to install the script.

## Configuration

You need to add a "config" string to your "about-me" section that points to a JSON file containing your configuration.

To do this, create a JSON file with the following structure:

```json
{
  "default": "https://i.imgur.com/dVS2SdF.png",
  "scrobbling": "https://i.imgur.com/oyE70Kv.png",
  "css": ".some-class { color: blue; }"
}
 ``` 
Then, host the file somewhere (e.g. on a GitHub Gist, or your own web server) and add a line to your "about-me" section that starts with "config:" followed by the URL of the JSON file. For example:

`config: https://website.com/config.json`

this allows you to add custom CSS to your profile page.

as seen on my profile : https://www.last.fm/user/Ongezell



## Tips

- If you want to modify the CSS styles in your Last.FM profile, you can edit the "css" property in your JSON file, it will be visible for those who visit your profile page and also have the script installed.
