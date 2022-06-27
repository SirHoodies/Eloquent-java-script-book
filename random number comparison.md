    
_______________________________SIMPLE VERSION_______________________________________________________________________
   
    function greaterThan(n){
            return function(m){ return n > m}
    }

    var greaterThan10 = greaterThan(10);   // is 10 > 11
    console.log(greaterThan10(11));          // the second parenthisis is funciton(m) with the 'm' value assigned
    
 ______________________________MY VERSION___________________________________________________________________________

    var random1 = (Math.floor(Math.random()*10))     // makes it so that the random numbers are between 0 and 9 (you can change the *10 to *100 to make it from 0-100)
    var random2 = (Math.floor(Math.random()*10))

    function greaterThan(n){
        console.log(random1)                 // prints the random numbers generated
        console.log(random2)
        return function(m){
            if (m == n){         
                return "Equal"
            }
            else
                return (n > m);
        }
    }

    var random_number = greaterThan(random1);      // just to simplify things
    console.log(random_number(random2));          // the second parenthisis is funciton(m) with the 'm' value assigned
    
 _____________________________________________________________________________________________________________________
 
 I added an equal too comparison and made the numbers you compare randomly generate.
