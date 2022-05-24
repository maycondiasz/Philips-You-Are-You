# Entendendo como o GIT funciona por baixo dos panos
## Tópicos fundamentais para entender o funcionamento do GIT
- SHA1
- Objetos fundamentais
- Sistema distribuído
- Segurança

### SHA1
Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptográficas projetdas pela NSA (Agência de Segurança Nacional dos EUA).\
A encriptação gera um conjunto de caracteres de 40 dígitos.

É uma forma curta de representar um arquivo.
```bash
echo "ola mundo" | openssl sha1
SHA1(stdin)= d9802fa01c4c1dfc4ddaf61f766d8d56ad8a8699
```
---
## Objetos internos de GIT
- Blobs
- trees
- Commits

**Blobs** são semelhantes ao arquivos dentro de um computador, as blobs guardam metadados do que definem o arquivos com o seu código hash de 40 dígitos.

**Trees** são semelhantes as pastas dentro de um computados, armazemando blobs e outras trees.

**Commit** É o que organiza as hash pela sua hierarquia, ele aponta para a tree e seu antercessor (parente), ele define o altor do commit, ele define uma mensagem para identificar o hash, ele define o exato momento que o commit foi criado.

---
## Chave SSH e Token
Alteração no processo de autentificação no CLI, faz-se necessário o uso de uma chave SSH.

[Back :back:](../README.md)
