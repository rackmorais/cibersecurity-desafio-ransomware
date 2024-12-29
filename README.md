### Página do projeto:
para criar a página digite:
mkdir (nome da pasta)

para acessar a pasta digite:
cd (nome da pasta)

### Criação dos arquivos:
Serão 3 arquivos:
- descrypter.py
- encrypter.py
- teste.txt
- 
## Comando para criar o arquivo:
nano (nome do arquivo)
Salve e saia do editor:
`Ctrl + O (salvar)`
`Enter (confirmar o nome do arquivo)`
`Ctrl + X (sair do editor).`

## Encriptografar o arquivo

1. Execute o script de encriptação:
```bash
python encrypter.py
```
2. Verifique os arquivos no diretório com o comando `ls`.
3. Um novo arquivo será gerado: `teste.txt.ransomwaretroll`.
**Ao abrir este arquivo, você verá que os dados não estão mais legíveis – eles foram encriptografados.**

![Captura de tela 2024-12-18 173235](https://github.com/user-attachments/assets/02d36987-6649-4a6d-ba65-61c1612f28e7)

## Descriptografar o arquivo

1. Para reverter o processo e tornar o arquivo legível novamente, execute:
```bash
python decrypter.py
```
2. Verifique os arquivos no diretório novamente com `ls`.
O arquivo original, `teste.txt`, estará disponível e legível.

![Captura de tela 2024-12-18 173411](https://github.com/user-attachments/assets/1863fda1-a964-4e41-b1ca-458869b9a3b4)

## 🚀 Conclusão

Este projeto é uma introdução prática à manipulação de arquivos utilizando encriptação e decriptação no Linux.

