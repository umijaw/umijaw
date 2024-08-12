**Si vous exécutez le programme avec la commande**

./huffman_compression.py

s’affiche dans la console le texte suivant qui vous explique comment utiliser le programme
You should give:

- -c or -d as first argument to specifiy if you want to compress or decompress,
- the second argument is the name of the file to (de)compress,
- the third argument is the name of the output file.
If you do not give a third argument, output file name will be set up to:
-- <first_argument>.huf if you compress,
-- <first_argument>.dec if you decompress.
Vous pouvez taper, après vous être assuré que le fichier test_file_to_compress.txt est
bien dans le répertoire où vous exécutez le programme :
./huffman_compression.py -c test_file_to_compress.txt
puis
./huffman_compression.py -d test_file_to_compress.txt.huf
puis
diff test_file_to_compress.txt test_file_to_compress.txt.huf.dec
