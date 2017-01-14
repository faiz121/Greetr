Greetr is a tiny JS library to give user greetings upon login based on the user's local language.

The Greetr library is using jQuery to for DOM manipulation. The code in Greetr library also looks very similar to how jQuery's new object is created. 

The library at this point is very tiny but can be improved to show more greetings in many different languages and also depending on the time of the day.

Some insights into the code itself. 
Just like jQuery to create a new object 
    // 'new' an object
    var Greetr = function(firstName, lastName, language) {
        return new Greetr.init(firstName, lastName, language);   
    }
    
    Attaching Greetr object to Global object. Also a shorthand way of accessing is G$ (Like jQuery's $)
    global.Greetr = global.G$ = Greetr;
    
    
    
