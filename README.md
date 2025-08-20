---------------------Hello Angular-------------------------


how to run angular 14 in company laptop: 
 cmd: 

npm uninstall -g @angular/cli
npm install -g @angular/cli@14

---but angular 14 need, lower ver of node

in package.json, then dev dependenices
"@types/node": "18.15.11"

then, npm install --save-dev @types/node@18.15.11
