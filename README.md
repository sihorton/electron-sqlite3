# electron-sqlite3
Example electron app with sqlite3 integration

Based on the approach in https://github.com/atom/electron/issues/1182 and http://verysimple.com/2015/05/30/using-node_sqlite3-with-electron/

For windows the line in package.json:
````
"postinstall": "npm run rebuild-sqlite3",
````
can be changed to:
````
"postinstall": "npm run rebuild-sqlite3-win",
````
or alternatively just run
````
npm run rebuild-sqlite3-win
````
