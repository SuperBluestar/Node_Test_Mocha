# React Typescript Signup Page
<a href="https://www.airfleet.co/">The AirFleet Team</a>

# How to run this project?
### To start, install node modules
```
npm i
or
yarn install
```
### To see the result, run the project
```
npm start
or
yarn start
```

Please check the result by clicking <a href="localhost:8080">localhost:8080</a>.

# How to build this app?
### If you check the project is working well, run the command
```
npm run build
or 
yarn build
```
### Copy the generated files in dist/*.* directory to apache server or other server's public folder.

### Then you can see the result by clicking <a href="localhost">localhost</a>

# How to use eslint?
### Just run the below command
```
npm run lint
or
yarn lint
```
Using eslint, you can rearrange the codes in src folder.
<br>
You can add some settings in eslintrc.js
# Project structure
### Source File structures
```
configs: project configuration folder
dist: public folder
src
  |-- assets: optimized resources and additional styles
      |-- img: optimized image resources
      |-- scss: customized variables from bootstrap scss
  |-- components: medium components using in this project
  |-- elements: small unit using in this project
  |-- layouts: main layout using in this project
  |-- pages: web project's pages
  |-- App.tsx: Here you can add the routes
  |-- entry point of this react project
test: test codes. this is working as demo server when this project is connected to server.
express.js: this is express server. from here you can develop server code.
...
```

