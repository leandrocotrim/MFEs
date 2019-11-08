# MFEs

## Micro Frontends with Angular

`Enviroment`

- **npm install -g @angular/cli/**
- **npm -g live-server**

`Starts`

- cd ds4 && npm i && npm run build:externals
- cd ds3 && npm i && npm run build:externals
- cd ds2 && npm i && ng serve --port=4201 --single-bundle
- cd ds1 && npm i && ng serve

`Access`

### http://localhost:4200

!["Result"](assets/4200.PNG)

### WebComponent Container isolated code NG, not single bundle

!["Result"](assets/2_polyfills_zonejs_webcomponents_project_ng.PNG)

### WebComponent External, single bundle

!["Result"](assets/3_webcomponents_weight.PNG)

### WebComponent, Exposed Modules NG

!["Result"](assets/4_web_components_models_global_weight_but_good.PNG)

### WebComponent Read Exposed Modules NG

!["Result"](assets/5_only_module_noop_ng_modules.PNG)

### Código gerado

!["Result"](assets/1_html.PNG)

## reference
### https://www.softwarearchitekt.at/aktuelles/