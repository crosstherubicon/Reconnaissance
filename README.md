# Reconnaissance



### setup
1. npm install
2. `cd config && cp config-sample.js config.js`
3. In MySql create a database named "properties"
4. Update `username` with your MySql username and password with your MySql password in config.js
5. Build bundle.js npm run build (for development use npm run build-dev and keep terminal open)
6. start the project from project root directory node bin/www or nodemon
7. Visit localhost:4000 in browser
8. Use npm run build-sass to transpile sass/scss files to css.