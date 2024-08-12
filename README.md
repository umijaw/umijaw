### **Vous pouvez exécuter le programme avec la commande :**

### `./huffman_compression`

Vous devez mettre :

1. `-c` ou `-d` comme premier argument pour spécifier si vous souhaitez compresser ou décompresser.
2. Le nom du fichier à compresser ou décompresser.
3. Le troisième argument (facultatif) est le nom du fichier de sortie.

Si vous ne donnez pas de troisième argument, le nom du fichier de sortie sera défini sur :
- `<nom_du_fichier_en_argument>.huf` si vous compressez,
- `<nom_du_fichier_en_argument>.dec` si vous décompressez.

Vous devez vous assurer que le fichier à compresser et celui à exécuter (`huffman_compression`) soient dans le même répertoire. Si ce n'est pas le cas, vous devrez ajouter le chemin du fichier.

**Exemple :**
Si tous les fichiers sont dans le même répertoire :

./huffman_compression -c test_file_to_compress.txt

Puis :

./huffman_compression -d test_file_to_compress.txt.huf

*Enfin, pour vérifier l'intégrité du fichier après décompression :*

*diff test_file_to_compress.txt test_file_to_compress.txt.huf.dec*


