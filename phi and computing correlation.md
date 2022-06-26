    function phi(table) {
        return (table[3] * table[0] - table[2] *table[1]) / 
        Math.sqrt((table[2] + table[3]) *
            (table[0] + table[1]) *
            (table[1] +table[3]) *
            (table[0]+ table[2]));     
         
    }

    console.log(phi([4, 3, 2, 1]));
    
i honestly have a 99% understanding of whats happening

