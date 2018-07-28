# ionic-crud-capacitor
A simple CRUD native progressive web app developed using Ionic v4, Capacitor and Angular 5

To create a project, use command

```bash
$ ionic start or
$ ionic start myApp sidemenu --type=angular
```

Use this command to globally set ionic to use `yarn` instead of `npm`

```bash
$ ionic config set -g npmClient yarn
```
For a local project go in the project directory and run
```bash
$ ionic config set npmClient yarn
```

The majority of Ionic app development can be spent right in the browser using the ionic serve command

```bash
$ cd myApp or cd .\myApp\
$ ionic serve
```

Need to run this command if you require ionic-lab

```bash
$ yarn add @ionic/lab or
$ npm install @ionic/lab --save
```

For using the ionic lab use command

```bash
$ ionic serve -lcs
```

To generate `pages`, `components`, `directives` etc. use command

```bash
$ ionic generate or
$ ionic g or
$ ionic generate page "pages/User Detail"
```

## To run on android

Generate the native project, if it does not already exist.

```bash
$ yarn run build
$ ionic capacitor add android
$ ionic capacitor copy android
$ ionic capacitor open android
```
* Requires Android Studio 3+
Set the Package ID, open `capacitor.config.json` file and modify the `appId` property.

