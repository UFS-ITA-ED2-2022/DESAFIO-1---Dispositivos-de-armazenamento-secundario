# DESAFIO-1---Dispositivos-de-armazenamento-secundario

Você sabe o seguinte sobre seu HD:
* Número de Bytes por setor: 512
* Número de setores por trilha: 40
* Número de trilhas por cilindro: 11
* Número de cilindros: 1.331

Há um conjunto de dados composto por 20.000 registros, sendo que cada registro tem 256 Bytes.

**Quantos cilindros são necessários para se armazenar esses 20.000 registros?** Apresente todos os cálculos para se chegar no total de cilindros necessários.

## Resposta

### Obtendo quantidade de Bytes para armazenar
20.000 Registros de 256 Bytes
20.000 x 256 = 5.120.000 Bytes no total

### Obtendo a quantidade de trilhas no HD
11 trilhas x 40 setores = 440 trilhas

### Obtendo a quantidade de bytes de um cilindro
440 trilhas * 512 Bytes = 225280 Bytes por cilindro

### Obtendo quantidade de cilindros
5120000 / 225280 ~= 22,72 cilindros
