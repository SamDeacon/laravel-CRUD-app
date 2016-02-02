# this project uses bourbon,neat and refills7
### https://github.com/thoughtbot/bitters
http://bourbon.io/ || http://neat.bourbon.io/ || etc

## Removing bourbon completely:
- cd resources/assets/sass/vendor
- rm -rf base bourbon neat
- delete lines relating to '@inlude base, bourbon and neat' from resources/assets/sass/vendor/_vendor.scss

## Updating to latest versions
1. 
- gem install bourbon # or gem update bourbon
- gem install neat # or gem update neat
- gem install bitters # or gem update bitters
2. 
- cd resources/assets/sass/vendor
- rm -rf base bourbon neat
- bourbpn install
- neat install
- bitters install

### recommended tutorial from Devtips: https://www.youtube.com/watch?v=8ItNE_DX6Cc
