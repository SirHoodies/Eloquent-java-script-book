    var num1 = 2
    var num2 = 31
    var counter = num2

    var res = num1*num1

    while(counter > 2 ) {     //im using > 2 because res = num1 * num1(2*2) so when we go to where we redefine res, its really res = (num1 *num1 *num1) (2*2*2) so it 
        res = (res*num1)        already does the first 2 steps
        counter -= 1
        //(optional) console.log('progress ' +counter+ ": " +res)
    }

    console.log('The square root of '+num1+ " to the "+num2+ " power is "+res)

