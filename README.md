# notes-view

1. Install Angular CLI
```sh
ng n notes-view --verbose=true --commit=true --minimal=true --routing=true --skipInstall=true --style=sass --force=true
cd notes-view
git commit -m "create angular"
ng add @angular/pwa
git add -A
git commit -m "add pwa"
ng g appShell --client-project=notes-view --universal-project=notes-view
git add -A
git commit -m "add appShell"
```
