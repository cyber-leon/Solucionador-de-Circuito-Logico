# MANUAL
Para baixar o arquivo clique em "Clone or donwload"
![](https://cloud.addictivetips.com/wp-content/uploads/2016/08/github-plus.jpg)

Ao baixar o arquivo, extraia o arquivo.zip em qualquer pasta, caso seu computador não tenha como extrir arquivos desse tipo você pode baixar o Winrar.

Crie um arquivo de texto.txt, coloque o circuito logico que deseja solucionar nele, é importante que nada além das entradas, saídas e portas logicas estejam nesse arquivo.Além de que as letras devem estar em maiúsculo. Segue um exemplo:

CIRCUIT Expressao logica //nome do arquivo após o CIRCUIT

NOT 1 4

AND 2 3 8 //uma porta lógica "e" entradas 2 e 3 saída 8

NOR 4 8 7

AND 1 7 5

AND 2 5 6

INPUT 1 A //uma entrada A na porta 1

INPUT 2 B

INPUT 3 C

OUTPUT 6 S //uma saída S na porta 6

Os "//" são comentários ao arquivo acima, não os inclua no arquivo de leitura.

Ao abrir o arquivo terá uma arquivo.txt com o nome "solucionado" nele estará o código que deverá ser copiado para qualquer decompilador em c, sugiro o Qt Creator, o donwload dele pode ser realizado no site: https://www.qt.io/download-open-source?hsCtaTracking=9f6a2170-a938-42df-a8e2-a9f0b1d6cdce%7C6cb0de4f-9bb5-4778-ab02-bfb62735f3e5


Ao copia os dados, compile e execute o arquivo, no Qt você pode fazer isso apertando um botão com o simbolo de play.

Apos isso o CMD abrirá, informe o local do arquivo que será solicitado pelo programa e ele gerará a tabala verdade de acordo com o resultado.

Caso queira um exemplo de circuito logico, você pode utilizar o que estar nessa imagem:
![](https://i.ytimg.com/vi/B7uSZmXu94I/maxresdefault.jpg)
