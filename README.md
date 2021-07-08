# Simple frontend

## To recreate

1. `npm i -g @angular/cli @angular-devkit/{core,schematics} @angular-eslint/schematics`
2. `ng new app`
3. `cd app`
4. `ng add @angular-eslint/schematics`
5. `ng g @angular-eslint/schematics:convert-tslint-to-eslint --remove-tslint-if-no-more-tslint-targets --ignore-existing-tslint-config`
