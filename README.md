## initializing project

```bash
npm init -y
```

## installaion

> Note: installing tailwindcss, postcss, postcss-cli, autoprefixer, vite as Dev dependicies.

```bash
npm install -D tailwindcss postcss postcss-cli autoprefixer vite
```

## configurations 

> Note: generating a configuration file for Tailwindcss and postcss 

```bash 
npx tailwindcss init -p 
```

## Tailwindcss compiler

> Note: in oreder to get the tailwindcss classes, you have to create a css compile file, and another css file where you store the complie result

```bash
toch src/css/app.css
toch src/css/main.css
```
 - Add the following lines to `app.css` 
 ```bash
    @import 'tailwindcss/base';
    @import 'tailwindcss/components';
    @import 'tailwindcss/utilities';
 ```

 - Compling the `app.css` file to `main.css` file by runing the following commande
 ```bash
 npm run build:css
 ```

## serve

```bash
npm run dev
```
> Note: all commandes are definde in `package.json` file.