/**
*   IMPORTS
*/
fs = require('fs');
request = require('request');
cheerio = require('cheerio');



console.log('Program started');

// Read by file
fs.readFile('./input/input', 'utf8', function (err,data) {
    if (err) {
        return console.log(err);
    }
        console.log(data);
    });



// Web scraping

var url = 'http://stackoverflow.com/questions/12403833/how-to-most-efficiently-parse-a-web-page-using-node-js';
request(url, function(error, response, html){
    if(!error){
        var $ = cheerio.load(html);

        var something = $('#herobox');
        console.log(something);
    }

});





