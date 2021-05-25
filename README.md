[VueStoreFront Frontend](https://github.com/patrickjaja/vsf-theme) + latest spryker suite (more details in [deploy.yml](https://github.com/patrickjaja/suite/deploy.yml))

# install (Tested on ArchLinux)
 - `git clone --recurse-submodules https://github.com/patrickjaja/spryker_glue_vue_storefront`
 - `cd spryker_glue_vue_storefront/suite`
 - `docker/sdk boot -v`
 - `cd ../vsf-theme`
 - `yarn install`

# Start Spryker + VSF
 - `docker/sdk up -v`
 - `yarn dev`

Open - VSF: http://localhost:3000

# Prerequisite
 - `nvm install 12` ( + `source /usr/share/nvm/nvm.sh`, `nvm use 12` )
 - docker
 - yarn

# Troubleshooting
 - Spryker
    - https://documentation.spryker.com/docs/installing-in-development-mode-on-macos-and-linux
 - VSF
    - https://github.com/spryker/vsf-theme
    - https://spryker.com/en/press-release-spryker-vue-storefront/
    - https://spryker-vsf-docs.web.app/
 
# User Journeys
## buy product as guest
 - Open http://192.168.87.162:3000/
 - Click on category 'Computer'
 - Select first product 'DELL OptiPlex 3020'
 - Choose Option '3.3 GHz'
 - Click 'Add to Cart'
 - Click on your cart, go to checkout, fill forms

## register
 - tbd

## buy product logged in
 - tbd
