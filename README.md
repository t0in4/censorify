you can install package by npm install censorifyapplication  
1. mkdir readwords && cd readwords  
2. npm install censorifyapplication  
3. vi readwords.js  
    var censor = require("censorify");  
    console.log(censor.getCensoredWords());  
    console.log(censor.censor("Some very sad, bad and mad text."));  
    censor.addCensoredWord("gloomy");  
    console.log(censor.getCensoredWords());  
    console.log(censor.censor("A very gloomy day."));  
4. :wq // save and exit from vi  
5. node readwords.js  
