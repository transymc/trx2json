A small Nodejs library to convert VS test result file to json format

## Installation

  `npm install @buu_tran/trxtojson`

## Usage

  var {processor} = require('trx2json');
  var path = {filename:"*.trx", options:""};
  var htmltemplate = {filename:"*.trx", options:""};
  processor(path, htmltemplate).then ((response)=>{console.log(response)});
  
  Output should be json string of trx format that is ready to be rendered in html

## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.
