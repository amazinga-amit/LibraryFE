
upon downloading follow the strps 

## Terminal Commands

1. Install NodeJs from [NodeJs Official Page](https://nodejs.org/en).
2. Open Terminal
3. Go to your file project
4. Run in terminal: ```npm install -g @angular/cli```
5. Then: ```npm install```
6. And: ```ng serve```
7. Navigate to `http://localhost:4200/`

### What's included

Within the download you'll find the following directories and files:
```
│   .gitattributes
│   angular.json
│   CHANGELOG.md
│   karma.conf.js
│   LICENSE.md
│   package-lock.json
│   package.json
│   protractor.conf.js
│   README.md
│   tslint.json
│   typings.json
│
├───e2e
│       app.e2e-spec.ts
│       app.po.ts
│       tsconfig.json
│
└───src
    │   .DS_Store
    │   favicon.ico
    │   index.html
    │   main.ts
    │   polyfills.ts
    │   styles.css
    │   test.ts
    │   tsconfig.json
    │
    ├───app
    │   │   app.component.css
    │   │   app.component.html
    │   │   app.component.spec.ts
    │   │   app.component.ts
    │   │   app.module.ts
    │   │   app.routing.ts
    │   │
    │   ├───add-book-form
    │   │       add-book-form.component.html
    │   │       add-book-form.component.scss
    │   │       add-book-form.component.spec.ts
    │   │       add-book-form.component.ts
    │   │
    │   ├───add-member-form
    │   │       add-member-form.component.html
    │   │       add-member-form.component.scss
    │   │       add-member-form.component.spec.ts
    │   │       add-member-form.component.ts
    │   │
    │   ├───home
    │   │       home.component.css
    │   │       home.component.html
    │   │       home.component.spec.ts
    │   │       home.component.ts
    │   │
    │   ├───icons
    │   │       icons.component.css
    │   │       icons.component.html
    │   │       icons.component.spec.ts
    │   │       icons.component.ts
    │   │
    │   ├───layouts
    │   │   └───admin-layout
    │   │           admin-layout.component.html
    │   │           admin-layout.component.scss
    │   │           admin-layout.component.spec.ts
    │   │           admin-layout.component.ts
    │   │           admin-layout.module.ts
    │   │           admin-layout.routing.ts
    │   │
    │   ├───lbd
    │   │   │   lbd.module.ts
    │   │   │
    │   │   └───lbd-chart
    │   │           lbd-chart.component.html
    │   │           lbd-chart.component.ts
    │   │
    │   ├───loginform
    │   │       loginform.component.html
    │   │       loginform.component.scss
    │   │       loginform.component.spec.ts
    │   │       loginform.component.ts
    │   │
    │   ├───maps
    │   │       maps.component.css
    │   │       maps.component.html
    │   │       maps.component.spec.ts
    │   │       maps.component.ts
    │   │
    │   ├───models
    │   │       issue.ts
    │   │       return.ts
    │   │
    │   ├───notifications
    │   │       notifications.component.css
    │   │       notifications.component.html
    │   │       notifications.component.spec.ts
    │   │       notifications.component.ts
    │   │
    │   ├───request-book-form
    │   │       request-book-form.component.html
    │   │       request-book-form.component.scss
    │   │       request-book-form.component.spec.ts
    │   │       request-book-form.component.ts
    │   │
    │   ├───services
    │   │       services.service.spec.ts
    │   │       services.service.ts
    │   │
    │   ├───shared
    │   │   ├───footer
    │   │   │       footer.component.html
    │   │   │       footer.component.ts
    │   │   │       footer.module.ts
    │   │   │
    │   │   └───navbar
    │   │           navbar.component.html
    │   │           navbar.component.ts
    │   │           navbar.module.ts
    │   │
    │   ├───sidebar
    │   │       sidebar.component.css
    │   │       sidebar.component.html
    │   │       sidebar.component.ts
    │   │       sidebar.module.ts
    │   │
    │   ├───tables
    │   │       tables.component.css
    │   │       tables.component.html
    │   │       tables.component.spec.ts
    │   │       tables.component.ts
    │   │
    │   ├───typography
    │   │       typography.component.css
    │   │       typography.component.html
    │   │       typography.component.spec.ts
    │   │       typography.component.ts
    │   │
    │   ├───upgrade
    │   │       upgrade.component.css
    │   │       upgrade.component.html
    │   │       upgrade.component.spec.ts
    │   │       upgrade.component.ts
    │   │
    │   └───user
    │           user.component.css
    │           user.component.html
    │           user.component.spec.ts
    │           user.component.ts
    │
    ├───assets
    │   │   .DS_Store
    │   │   .gitkeep
    │   │
    │   ├───css
    │   │       demo.css
    │   │       pe-icon-7-stroke.css
    │   │
    │   ├───fonts
    │   │       Pe-icon-7-stroke.eot
    │   │       Pe-icon-7-stroke.svg
    │   │       Pe-icon-7-stroke.ttf
    │   │       Pe-icon-7-stroke.woff
    │   │
    │   ├───img
    │   │   │   angular-red.png
    │   │   │   angular2-logo-white.png
    │   │   │   angular2-logo.png
    │   │   │   default-avatar.png
    │   │   │   favicon.ico
    │   │   │   full-screen-image-3.jpg
    │   │   │   loader-preview.svg
    │   │   │   loading-bubbles.svg
    │   │   │   mask.png
    │   │   │   new_logo.png
    │   │   │   opt_lbd_angular_thumbnail.jpg
    │   │   │   sidebar-1.jpg
    │   │   │   sidebar-2.jpg
    │   │   │   sidebar-3.jpg
    │   │   │   sidebar-4.jpg
    │   │   │   sidebar-5.jpg
    │   │   │   tim_80x80.png
    │   │   │
    │   │   └───faces
    │   │           face-0.jpg
    │   │           face-1.jpg
    │   │           face-2.jpg
    │   │           face-3.jpg
    │   │           face-4.jpg
    │   │           face-5.jpg
    │   │           face-6.jpg
    │   │           face-7.jpg
    │   │           tim_vector.jpe
    │   │
    │   └───sass
    │       │   .DS_Store
    │       │   light-bootstrap-dashboard.scss
    │       │
    │       └───lbd
    │           │   .DS_Store
    │           │   _alerts.scss
    │           │   _buttons.scss
    │           │   _cards.scss
    │           │   _chartist.scss
    │           │   _checkbox-radio-switch.scss
    │           │   _dropdown.scss
    │           │   _footers.scss
    │           │   _inputs.scss
    │           │   _misc.scss
    │           │   _mixins.scss
    │           │   _navbars.scss
    │           │   _responsive.scss
    │           │   _sidebar-and-main-panel.scss
    │           │   _tables.scss
    │           │   _typography.scss
    │           │   _variables.scss
    │           │
    │           └───mixins
    │                   _buttons.scss
    │                   _cards.scss
    │                   _chartist.scss
    │                   _icons.scss
    │                   _inputs.scss
    │                   _labels.scss
    │                   _morphing-buttons.scss
    │                   _navbars.scss
    │                   _social-buttons.scss
    │                   _tabs.scss
    │                   _transparency.scss
    │                   _vendor-prefixes.scss
    │
    └───environments
            environment.prod.ts
            environment.ts
```


