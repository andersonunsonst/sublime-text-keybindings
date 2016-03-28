# sublime-text-keybindings
Um paliativo para bug no kde que não permite a digitação de letras acentuadas {à è ì ò ù ç ã ô ..etc}
A Solução é: 

vai em Preferences - Keibiding -> User

// missing accented characters fix for ubuntu 14.10

    // a, [á, à, ã, â, å, ä]
    { "keys": ["´","a"], "command": "insert", "args": {"characters": "á"}},
    { "keys": ["`","a"], "command": "insert", "args": {"characters": "à"}},
    { "keys": ["~","a"], "command": "insert", "args": {"characters": "ã"}},
    { "keys": ["^","a"], "command": "insert", "args": {"characters": "â"}},
    { "keys": ["°","a"], "command": "insert", "args": {"characters": "å"}},
    { "keys": ["¨","a"], "command": "insert", "args": {"characters": "ä"}},

    // A, [Á, À, Ã, Â, Å, Ä]
    { "keys": ["´","A"], "command": "insert", "args": {"characters": "Á"}},
    { "keys": ["`","A"], "command": "insert", "args": {"characters": "À"}},
    { "keys": ["~","A"], "command": "insert", "args": {"characters": "Ã"}},
    { "keys": ["^","A"], "command": "insert", "args": {"characters": "Â"}},
    { "keys": ["°","A"], "command": "insert", "args": {"characters": "Å"}},
    { "keys": ["¨","A"], "command": "insert", "args": {"characters": "Ä"}},

    // e, [é, è, ê, ẽ, ë]
    { "keys": ["´","e"], "command": "insert", "args": {"characters": "é"}},
    { "keys": ["`","e"], "command": "insert", "args": {"characters": "è"}},
    { "keys": ["^","e"], "command": "insert", "args": {"characters": "ê"}},
    { "keys": ["~","e"], "command": "insert", "args": {"characters": "ẽ"}},
    { "keys": ["¨","e"], "command": "insert", "args": {"characters": "ë"}},

    // E, [É, È, Ê, Ẽ, Ë]
    { "keys": ["´","E"], "command": "insert", "args": {"characters": "É"}},
    { "keys": ["`","E"], "command": "insert", "args": {"characters": "È"}},
    { "keys": ["^","E"], "command": "insert", "args": {"characters": "Ê"}},
    { "keys": ["~","E"], "command": "insert", "args": {"characters": "Ẽ"}},
    { "keys": ["¨","E"], "command": "insert", "args": {"characters": "Ë"}},

    // i, [ì, í, ï]
    { "keys": ["`","i"], "command": "insert", "args": {"characters": "ì"}},
    { "keys": ["´","i"], "command": "insert", "args": {"characters": "í"}},
    { "keys": ["¨","i"], "command": "insert", "args": {"characters": "ï"}},

    // I, [Ì, Í, Ï]
    { "keys": ["`","I"], "command": "insert", "args": {"characters": "Ì"}},
    { "keys": ["´","I"], "command": "insert", "args": {"characters": "Í"}},
    { "keys": ["¨","I"], "command": "insert", "args": {"characters": "Ï"}},

    // o, [ó, õ, ô, ö]
    { "keys": ["´","o"], "command": "insert", "args": {"characters": "ó"}},
    { "keys": ["~","o"], "command": "insert", "args": {"characters": "õ"}},
    { "keys": ["^","o"], "command": "insert", "args": {"characters": "ô"}},
    { "keys": ["¨","o"], "command": "insert", "args": {"characters": "ö"}},

    // O, [Ó, Õ, Ô, Ö]
    { "keys": ["´","O"], "command": "insert", "args": {"characters": "Ó"}},
    { "keys": ["~","O"], "command": "insert", "args": {"characters": "Õ"}},
    { "keys": ["^","O"], "command": "insert", "args": {"characters": "Ô"}},
    { "keys": ["¨","O"], "command": "insert", "args": {"characters": "Ö"}},

    // u, [ú, ů, ü]
    { "keys": ["´","u"], "command": "insert", "args": {"characters": "ú"}},
    { "keys": ["°","u"], "command": "insert", "args": {"characters": "ů"}},
    { "keys": ["¨","u"], "command": "insert", "args": {"characters": "ü"}},

    // U, [Ú, Ů, Ü]
    { "keys": ["´","U"], "command": "insert", "args": {"characters": "Ú"}},
    { "keys": ["°","U"], "command": "insert", "args": {"characters": "Ů"}},
    { "keys": ["¨","U"], "command": "insert", "args": {"characters": "Ü"}},

    // y, [ý, ÿ]
    { "keys": ["´","y"], "command": "insert", "args": {"characters": "ý"}},
    { "keys": ["¨","y"], "command": "insert", "args": {"characters": "ÿ"}},

    // Y, [Ý, Ÿ]
    { "keys": ["´","Y"], "command": "insert", "args": {"characters": "Ý"}},
    { "keys": ["¨","Y"], "command": "insert", "args": {"characters": "Ÿ"}} 
