    var JSON_ancestry_file = 
    [
        {"name": "Emma de Millano" ,"sex": "f" ,"born": "1876","died": "1956","father": "Petrus de Millano","mother": "Sophia van Damme" },
        {"name":"Carlos Haverbeke" ,"sex": "m","born": "1832","died": "1905","father": "Carel Haverbeke","mother": "Maria van Brussel"},
        {"name":"Carlos Cummberbatch","sex":"m","born":"1980","died":"N/A","father":"Emmanuel Cummberbatch"}
    ]

    var string = JSON.stringify({name: "Carlos Cummberbatch", sex: "m", born: "1980", died: "N/A", father: "Gabriela Fitzgerald", father: "Emmanuel Cummberbatch" });
    console.log(string);
    console.log(JSON.parse(string).name);
    console.log(JSON_ancestry_file);
