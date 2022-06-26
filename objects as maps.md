    var map = {};
    function storePhi(event, phi) {
        map[event] = phi;       // just meand that event = phi (in the same property)
    }

    storePhi('pizza', 0.069,);               //event = pizza     phi = 0.069
    storePhi('touched a tree', -0.081);     //event = touched a tree    phi = -0.081

    console.log('pizza'in map)
    console.log(map['pizza']);
    console.log(map);
