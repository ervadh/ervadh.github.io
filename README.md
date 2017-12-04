# Front End Boilerplate
Pastikan sudah install [Nodejs](https://nodejs.org/en/), [Git](https://git-scm.com/), dan [Gulpjs](http://gulpjs.com/).

## Initial Setup
```sh
$ git clone git@gitlab.com:salt-frontend/dev-html.v.2.git
$ cd dev-html.v.2/Core
$ npm install
```

## Running Development
```sh
$ cd dev-html.v.2/Core
$ gulp
```

## Integration with Backend Development
```sh
$ cd dev-html.v.2/Core
$ gulp development
```

## Directory Structure
```
- Core
    - sass
    - script
    - views
    - bower_components
    - plugins
    
- Public (semua hasil generate-an gulp akan di-render di folder ini)
    - assets
        - css
        - js
        - images (tambahin disini)
```