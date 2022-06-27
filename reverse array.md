    function reverseArray(userArray){
        let output = [];                //empty array
        for (let i = userArray.length - 1; i >= 0; i--) { //how to get to the last index of an array
            output.push(userArray[i])         //pushes the last index into the empty array first
        }
        return output;      //when done, returns the reversed array
    }
    console.log(reverseArray(['A', 'B', 'C','D']));
