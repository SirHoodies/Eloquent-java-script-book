    function findSolution(target) {                    //target = the user input in console.log(fondSolution(24));
        function find(start, history){                 // start and history are defined in return find(1,"1") where start = 1 and history = "1"
            if (start == target)                       // if start(1) = target(user input), print "1"
                return history;                       
            else if (start > target)                   // else if start(1) > target(user input), print "null 
                return null;                            
            else                                                  //otherwise (in this case) target = 24 start = 1 and history = "1"
                return find(start + 5, "("+history+" + 5") ||       
                    find(start * 3, "("+history+" * 3)");
        }
        return find(1,"1")
    }

    console.log(findSolution(24)); 

_____________________________________________________________
    
    function isEven(number){
        var res = number % 2;
        if (res == 0||res == -0){
            return true;
        }
    
        if (res == 1||res == -1){
            return false;
        }
        console.log(res)

        return isEven(number - 2)
    }

    console.log(isEven(50)) // true
    console.log(isEven(75)) // false
    console.log(isEven(-1)) // false
