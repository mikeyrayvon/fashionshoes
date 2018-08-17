Globie Shopify Starter Pack
---

Starting point for our Shopify themes.

Tech this uses [thnx]:

- http://gulpjs.com/

---

#### Setup
- `brew tap shopify/shopify`
- `brew install themekit`
- make `config.yml` file from example
  - Theme ID:
    - compress theme to zip
    - upload zip to shop themes
    - get theme ID from uploaded theme
  - Password:
    - password found at Apps > Manage private apps > Theme dev
    - If Theme dev app doesn't exist, create it
- `yarn install`
- `gulp build` or `gulp`
- `theme upload`
