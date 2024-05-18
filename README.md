{
  "name": "ghosts-n-toasts-website",
  "version": "1.3.2",
  "homepage": "https://GhostsNToasts.github.io/Website/",
  "dependencies": {
    "classnames": "2.3.2",
    "moment": "2.29.4",
    "nouislider": "15.4.0",
    "react": "18.2.0",
    "react-datetime": "3.2.0",
    "react-dom": "18.2.0",
    "react-router-dom": "6.11.1",
    "react-scripts": "5.0.1",
    "reactstrap": "8.10.0",
    "sass": "1.62.1"
  },
  "devDependencies": {
    "gh-pages": "^6.1.1"
  },
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build -r git@github.com:GhostsNToasts/Website.git",
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "install:clean": "rm -rf node_modules/ && rm -rf package-lock.json && npm install && npm start",
    "compile-sass": "sass src/assets/scss/paper-kit.scss src/assets/css/paper-kit.css",
    "minify-sass": "sass src/assets/scss/paper-kit.scss src/assets/css/paper-kit.min.css --style compressed"
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "optionalDependencies": {
    "typescript": "5.0.4"
  },
  "peerDependencies": {
    "react": ">=16.0.0",
    "react-dom": ">=16.0.0"
  },
  "overrides": {
    "svgo": "3.0.2"
  },
  "description": "",
  "main": "src/assets/scss/paper-kit.scss",
  "keywords": [
    "react",
    "reactstrap",
    "reactjs",
    "paper-kit",
    "paper-kit-react",
    "paper-kit-2",
    "paper-kit2",
    "paper-design",
    "hook",
    "hooks",
    "react-hook",
    "react-hooks",
    "template",
    "theme",
    "react-template",
    "react-theme"
  ],
  "author": "GhostsNToasts"
}
