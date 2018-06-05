# primo compitino di studio

## fare una app angular con login e un paio di pagine con get e put

* in material

### link e risorse


https://github.com/angular/material2
https://material.angular.io/

https://github.com/angular/flex-layout
https://github.com/angular/flex-layout/blob/master/CODING_STANDARDS.md


http://jasonwatmore.com/post/2016/09/29/angular-2-user-registration-and-login-example-tutorial

http://jasonwatmore.com/post/2018/05/16/angular-6-user-registration-and-login-example-tutorial


https://github.com/angular/angular-cli#usage

https://medium.com/codingthesmartway-com-blog/angular-material-and-angular-6-material-design-for-angular-6b1a3ee476f0

https://embed.plnkr.co/HonqIW/

http://patternry.com/p=angular-material-sign-in-form/

https://medium.com/codingthesmartway-com-blog/angular-material-b1973e5a2ee6

https://www.sitepoint.com/angular-forms/

https://material.angular.io/components/form-field/examples

2018-06-04 12:53:08

https://github.com/daniel-nagy/md-data-table

https://github.com/michaelkrone/generator-material-app
### step

* app
* routing
* viste
  - login
  - splash
*

-----

0. npm install -g @angular/cli
npm install @angular/cli
ng update @angular/cli



1. step 1 uno scaffolding material funzionante 2018-06-01 14:50:59



git init AAMaterialLogin
ng new AAMaterialLogin --inline-template --inline-style --routing
ng add @angular/material
ng generate @angular/material:materialTable -- name dataResult
npm i -g npm-check-updates
ncu -u
npm install
npm install typescript@">=2.7.0 <2.8.0"

```
λ ncu -u
Using C:\Users\utente1\Documents\studio\AAMaterialLogin\package.json
[..................] / :
 @angular/animations                 ^5.2.0  →         ^6.0.3
 @angular/common                     ^5.2.0  →         ^6.0.3
 @angular/compiler                   ^5.2.0  →         ^6.0.3
 @angular/core                       ^5.2.0  →         ^6.0.3
 @angular/forms                      ^5.2.0  →         ^6.0.3
 @angular/http                       ^5.2.0  →         ^6.0.3
 @angular/platform-browser           ^5.2.0  →         ^6.0.3
 @angular/platform-browser-dynamic   ^5.2.0  →         ^6.0.3
 @angular/router                     ^5.2.0  →         ^6.0.3
 rxjs                                ^5.5.6  →         ^6.2.0
 @angular/compiler-cli               ^5.2.0  →         ^6.0.3
 @angular/language-service           ^5.2.0  →         ^6.0.3
 @types/node                        ~6.0.60  →        ~10.3.0
 jasmine-core                        ~2.8.0  →         ~3.1.0
 karma-coverage-istanbul-reporter    ^1.2.1  →         ^2.0.1
 karma-jasmine-html-reporter         ^0.2.2  →         ^1.1.0
 protractor                          ~5.1.2  →         ~5.3.2
 ts-node                             ~4.1.0  →         ~6.0.5
 tslint                              ~5.9.1  →        ~5.10.0
 typescript                          ~2.5.3  →         ~2.9.1
 @angular-devkit/build-angular       ~0.6.6  →  ~0.7.0-beta.1
Upgraded C:\Users\utente1\Documents\studio\AAMaterialLogin\package.json
```


~~ng generate @angular/material -s -t --name loginPage~~
ng generate -t -s @angular/material:material-nav --name nav


git remote add origin https://github.com/netalex/AAMaterialLogin
git push -u origin master