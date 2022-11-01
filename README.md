# firefox-configs

A list of settings I use on firefox

## Disclaimer

I am not involved in the development of any of the software I mention here. This is simply a collection of settings I use for my browser. 

## Who is this for?

This is primarily for my own reference, but can be used as a guide to making firefox slightly more convenient to use than it is out of the box. Not all of these settings work for everybody, and I am happy to hear about modifications to this setup you believe will help me. 

## Basic Settings

- Make sure automatic updates are enabled for firefox.
- From the 'Home' category, disable snippets, recommended by pocket, recent activity and shortcuts.
- From the 'Search' category, uncheck 'Provide search suggestions'.
- Choose a privacy respecting search engine. I personally use Brave Search. 
- From the 'Privacy & Security' section, set Enhanced Tracking Protection to 'strict'. 
- Check 'Delete cookies and site data when Firefox is closed'.
- Uncheck 'Ask to save logins and passwords for websites'. Use Bitwarden or KeepassXC instead. 
- Check 'Always use private browsing mode'. 
- Uncheck everything in 'Firefox Data Collection and Use'. If you want to keep telemetry enabled, you can alter these settings accordingly.
- Uncheck 'Block dangerous and deceptive content'. This sends data to Google, but leave it enabled if it works for your threat model. 
- Enable HTTPS-Only Mode in all windows.

## Settings in the about:config menu

1. Type `about:config` in the search bar.
1. Click 'Accept the Risk and Continue'. 
1. Start changing the settings accordingly:
- Set `extensions.pocket.enabled` to `false`. 
- Set `privacy.firstparty.isolate` to `true`.
- Set `geo.enabled` to `false`.
- If you do not use web notifications, set `dom.webnotifications.enabled` to `false`. 

## One Click Addons

This list might not work for everyone, but try not to have too many addons. 

- uBlock Origin
- Skip Redirect

## Password Managers

These are generally better than the built in login manager. Use either KeepassXC or Bitwarden.

- Keep a strong master password, at least 15 characters randomly generated, or 30 characters as a passphrase.
- Do not reuse this master password anywhere.
- Generate a new password for each site. Make sure this is random.
- Save any new passwords to your password manager. 
- Remember to save any changes to your login credentials. 

## Privacy Redirect

- This is something I use to redirect YouTube, Reddit, and Twitter links.
- I do not have accounts for any of these platforms, so private frontends work just fine for me.
- I use FreeTube, and configure the addon so that all YouTube links are opened with Freetube. 
- I use one instance each of libreddit, piped, and nitter.

