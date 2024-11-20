# SteamPriceScrapper
Ruby Script to fetch game prices from Steam Store

# Tested On Ubuntu 22.04
* ruby 3.0.2p107
* selenium-web driver 4.26.0

# Usage
* install ruby
* install selenium web-driver `gem install selenium-webdriver`
  
After downloading script, create log file

```
sudo touch /var/log/steam_price_scrapper.log
sudo chown <username>:<username> /var/log/steam_price_scrapper.log
```

Edit this line if geckodriver location if it's not in /snap/bin
```
service.executable_path = '/snap/bin/firefox.geckodriver'
```

Run Script Like this:

```
ruby steam_price_scrapper.rb 'https://store.steampowered.com/app/1091500/Cyberpunk_2077/'
```
