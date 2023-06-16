you can install package by npm install censorifyapplication  
$ mkdir readwords && cd readwords  
$ npm install censorifyapplication  
$ vi readwords.js  

    var censor = require("censorify");  
    console.log(censor.getCensoredWords());  
    console.log(censor.censor("Some very sad, bad and mad text."));  
    censor.addCensoredWord("gloomy");  
    console.log(censor.getCensoredWords());  
    console.log(censor.censor("A very gloomy day."));  
      
    :wq // save and exit from vi  
$ node readwords.js  
