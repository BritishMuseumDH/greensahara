# Green Sahara
Part of the African Rock Art website found at https://africanrockart.britishmuseum.org (Repository found [here](https://github.com/BritishMuseum/bm-african-rock-art)).

## Requirements 
- Git
- Apache 2.4.58 or higher

## Installation Instructions
### Install Website
1. Navigate to Apache website dir
```
cd /var/www/prod/
```
2. Clone repository
```
git clone https://github.com/BritishMuseumDH/greensahara.git
```

### Configure Apache with African Rock Art Website
If African Rock art is not already set up, please follow the instructions [here](https://github.com/BritishMuseum/bm-african-rock-art)

1. Navigate to `/etc/apache2/sites-available/`
2. Add the following line to the config, under `<VirtualHost *:80>`
```
Alias /greensahara /var/www/prod/greensahara
```

## Current maintainers 
IS Department - issupport@britishmuseum.org   
 - IS Development team
