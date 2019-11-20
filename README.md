# Base58 for 1C


Base58 encoding / encoding function without using an external component.

These algorithms are ported from JS. Based on the ts-lib-crypto library. External components were not used in development. To use algorithms, a platform version of at least 8.3.11 is required.


## Installation and use

Build the configuration extension from the files in the repository. Connect to your configuration.

Interface development does not consist of general modules.

## For developers

```

bytesFromBase58 = Crypt_Base58.base58_decode("3BHaM9Q5HhUobQ5oZAqjdkE9HRpmqMx4XLq3GXTMD5tU"); // Масссив: {  "0": 32,  "1": 89,  "2": 236,  "3": 93,  "4": 158,  "5": 214,  "6": 64,  "7": 183,  "8": 87,  "9": 34,  "10": 236,  "11": 106,  "12": 47,  "13": 247,  "14": 104,  "15": 144,  "16": 229,  "17": 35,  "18": 234,  "19": 70,  "20": 36,  "21": 136,  "22": 117,  "23": 73,  "24": 219,  "25": 118,  "26": 29,  "27": 103,  "28": 139,  "29": 168,  "30": 248,  "31": 153}
	
base58String = Crypt_Base58.base58_encode(bytesFromBase58); // Строка: 3BHaM9Q5HhUobQ5oZAqjdkE9HRpmqMx4XLq3GXTMD5tU

```