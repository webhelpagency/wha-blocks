# wha-blocks Theme
1. Run the command in the terminal.

```
docker compose up 
```

### 2. Install Node Modules

```
cd dev/wha-block-theme
npm install
```

### 3. Compile:

``composer lint:wpcs :`` checks all PHP files against PHP Coding Standards.

``composer lint:wpcs :`` checks all PHP files against PHP Coding Standards.

``composer lint:php :`` checks all PHP files for syntax errors.

``composer make-pot :`` generates a .pot file in the languages/ directory.

``npm run compile:css :`` compiles SASS files to css.

``npm run compile:rtl :`` generates an RTL stylesheet.

``npm run watch :`` watches all SASS files and recompiles them to css when they change.

``npm run lint:scss :`` checks all SASS files against CSS Coding Standards.

``npm run lint:js :`` checks all JavaScript files against JavaScript Coding Standards.

``npm run bundle :`` generates a .zip archive for distribution, excluding development and system files.

### Push to the FTP

``.github/workflows/main.yml`` https://github.com/marketplace/actions/ftp-deploy

Use http://localhost:8080/ to see WordPress instance.

Use http://localhost:8081/ to see phpmyadmin instance.