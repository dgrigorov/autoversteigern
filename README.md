# CoreUI Free Vue Bootstrap Admin Template

[![NPM][npm-coreui-vue-badge-latest]][npm-coreui-vue]
[![Vue](https://img.shields.io/badge/Vue-^2.6.11-brightgreen.svg?style=flat-square)][coreui]

[npm-coreui-vue]: https://www.npmjs.com/package/@coreui/vue
[npm-coreui-vue-badge-latest]: https://img.shields.io/npm/v/@coreui/vue/latest?style=flat-square&color=brightgreen  
[coreui]: https://coreui.io/vue

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [UI Documentation](#ui-documentation)

### Installation

#### 1. Add SSH Key
1. Open Git Bash.
2. Paste the text below, substituting in your GitHub email address.

``` bash
$ ssh-keygen -t ed25519 -C "your_email@example.com"
```
3. When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.

``` bash
> Enter a file in which to save the key (/c/Users/<your_username>/.ssh/id_ed25519):[Press enter]
```
4.At the prompt, type a secure passphrase. **For easy work leave empty (click Enter)**

``` bash
> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]
```

5. Go To C:\Users\<your_username>\.ssh
6. Open id_ed25519.pub file
7. Copy the SSH public key to your clipboard.
8. Go To [Github](http://github.io)
9. In the upper-right corner of any page, click your profile photo, then click Settings.
10. In the user settings sidebar, click SSH and GPG keys.
11. Click New SSH key or Add SSH key.
12. In the "Title" field, add a descriptive label for the new key. For example, if you're using a personal Mac, you might call this key "Personal MacBook Air".
13. Paste your key into the "Key" field.
14. Click Add SSH key.
15. If prompted, confirm your GitHub password.


#### 2. Clone repo

``` bash
# clone the repo
$ git clone git@github.com:dgrigorov/autoversteigern.git

# go into app's directory
$ cd autoversteigern

# install app's dependencies
$ npm install
```

#### Usage

``` bash
# serve with hot reload at localhost:8080
npm run serve

# build for production with minification
npm run build

# run linter
npm run lint

# run unit tests
npm run test:unit

# run e2e tests
npm run test:e2e

```

For a detailed explanation on how things work, check out the [Vue CLI Guide](https://cli.vuejs.org/guide/).

### UI Documentation

CoreUI tools documentation:

- Components documentation: [CoreUI Vue library](https://coreui.io/vue/docs)
- Styles documentation: [CoreUI styles](https://coreui.io/docs/3.0-beta/)
- Icons documentation: [CoreUI Icons](http://coreui.io/icons).
