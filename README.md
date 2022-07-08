Can run by:
'npm run server' in /newportfoliopro
and
'npm start' in /client

fixes from origial::
fix the package.json by:
https://github.com/ehizeex/udemy-portfolio/blob/master/package.json

Fixed by:
Then delete
node_modules in /newportfoliopro & /client

Then delete
package-lock.json in /newportfoliopro & /client

Then:
'npm i' in /newportfoliopro & /client

heroku:

git push heroku HEAD:master

npm i --save @fortawesome/fontawesome-svg-core
npm install --save @fortawesome/free-solid-svg-icons
npm install --save @fortawesome/react-fontawesome
