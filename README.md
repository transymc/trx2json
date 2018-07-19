# trx2json
Nodejs utility to convert from VS test result file to json format


npm install trxtojson

node trx2json.js

sample code
var {processor} = require('trx2json');
var path = {filename:"*.trx", options:""};
var htmltemplate = {filename:"*.trx", options:""};
processor(path, htmltemplate).then ((response)=>{console.log(response)});
