# Ethereum Blockchain Intro

---

## ETHER: O "Fuel" que move a rede ethereum

---

## Emanuel Mota - @emota7
emanuel@yarilabs.com
### www.yarilabs.com

---
## Sobre a talk

* Definição de Ethereum
* ETHER - a Crypto Moeda
* O que é uma Blockchain ?
* Bitcoin vs. Ethereum
* Descentralização, "Smart Contracts" e Encriptação
* Linguagem de Programação `Solidity`
* Ethereum Virtual Machines
* Aplicações interessantes
* Comprar ETHER (GAS)

---

## O que é uma Blockchain

Blockchain é um tipo de Base de dados Distribuídos que guarda um registro de transações permanente e à prova de violação. A base de dados Blockchain consiste em dois tipos de registros: transações individuais e blocos.

+++

### Blockchain
Um bloco é um componente integrante da blockchain onde são registrados algumas ou todas as transações mais recentes e uma vez concluído é guardado na blockchain como base de dados permanente. Toda vez que um bloco é concluído um novo é gerado. Todos os bloco na blockchain estão ligado em série uns aos outros - como uma cadeia - onde cada bloco contém uma referência para o bloco anterior.

+++

### Blockchain
Todos os nodos que participam na rede podem ler as entradas nesta base de dados.

Se quisermos alterar esta base de dados temos de criar uma transação que tem de ser aceite por todos os outros participantes por consenso.

+++
### Blockchain
A palavra transação significa que a mudança que queremos realizar (ex: dois valores ao mesmo tempo) ou ocorre totalmente ou não ocorre.

+++
### Blockchain
Para além disto enquanto a transação é aplicada à base de dados nenhuma outra transação a pode alterar (não repudiável)

+++
### Blockchain
Todo o registo na blockchain tem um timestamp. Tudo é imutável. Registo histórico completo.

---

## Definição de ETHEREUM

Ethereum e uma plataforma open source que permite que qualquer pessoa possa criar aplicações descentralizadas (DAPPS) que correm em tecnologia baseada na blockchain. Tal como no Bitcoin, ninguém controla ou é dono do Ethereum - é um projecto open-source criado e mantido por muitas pessoas.


+++
### ETHEREUM
Contrariamente ao protocolo Bitcoin, o Ethereum foi desenhado para ser adaptável e flexível. É fácil criar novas aplicações na plataforma Ethereum. É relativamente fácil para qualquer pessoa com conhecimentos básicos de programação criar uma DAPP. 
---

## Expandindo a Definição de ETHEREUM

* Ethereum é essencialmente um grande computador a escala planetária (plataforma)
* Ethereum nunca vai abaixo ou está exposto a interferências
+++
### Expandindo a Definição de ETHEREUM
* Ethereum e criptograficamente seguro mas também é completamente transparente
* Ethereum é uma plataforma para desenvolver DAPPS (com Ether)
+++
### Expandindo a Definição de ETHEREUM
* Ethereum é também um algoritmo para encontro de consensus
* Proof of stake (Serenity) rápida e eficiente
+++
### Expandindo a Definição de ETHEREUM
* 60 milhões de ethers foram pré-minados para o financiamento do projecto
* 12 milhões foram criados para um fundo de desenvolvimento (Ethereum foundation)
+++
### Expandindo a Definição de ETHEREUM
* 5 ethers sao criados em cada bloco (que é minado a cada 15-17 segundos) e são transferidos para a carteira do mineiro.
* 2/3 ethers sao por vezes enviados para outro mineiro (miner) se eles também
* encontraram a solução mas o seu bloco não foi incluído na blockchain (uncle/aunt reward)

---

## O que o Ethereum não é

* Ethereum não é mais rápido do que a maioria das Base de dados (actualmente e múltiplas vezes mais lento)
* Ethereum não é anônimo nem confere anonimidade.
* Ethereum nao esta maduro o suficiente nem preparado para produção

+++
### O que o Ethereum nao e
* Não é somente uma crypto-moeda
* Não é a solução perfeita para todos os problemas de FINTECH
* Não é uma plataforma centralizada (E baseado em algoritmos de consensus descentralizado)

---

## ETHEREUM vs. BITCOIN

* Bitcoin e um sistema baseado em Blockchain criado para ser possível transmitir valor digitalmente, o Bitcoin e a criptomoeda na rede Bitcoin

* Ethereum e uma plataforma baseado em Blockchain para smart contracts com a sua própria crypto moeda chamada ETHER.

+++
### ETHEREUM vs. BITCOIN
A maior diferença é que o Ethereum e a uma plataforma global/mundial para correr scripts/DAPPS.
Para a podermos usar tem de se fornecer "combustível" que é o Ether, o token da rede Ethereum.
O Ethereum pode ser visto como uma plataforma distribuída à escala mundial para executar e criar DAPPS.

+++
### ETHEREUM vs. BITCOIN
O Bitcoin possui uma blockchain para confirmar transações e evitar o problema de gastar o mesmo bitcoin duas vezes. O Bitcoin é um meio para acordar transações, nada a ver com a execução de código. Na realidade são duas coisas muito diferentes.

---

## SMART CONTRACTS - "Contratos inteligentes"

`Smart contracts` também conhecidos como `smart property` sao protocolos computacionais que facilitam, verificam e ou reforçam a negociação ou performance de um contracto ou que tornam uma cláusula contratual desnecessária. Os `Smar Contracts` frequentemente emulam a lógica de cláusulas contratuais.

+++
### SMART CONTRACTS - "Contratos inteligentes"
Um contrato no mundo da linguagem de programação `Solidity` é um pedaço de código (as funções) e dados (o estado) que residem num endereco específico na blockchain do ethereum

+++
### SMART CONTRACTS - "Contratos inteligentes"
Um `smart contract` pode ser escrito em `Solidity`, `LLL`, `Mutant` ou `Serpent`. (Similares a JS, Python, Lisp e GO respectivamente)

---

## Linguagem de programação SOLIDITY

Para testar pode ser utilizado o browser a nao e necessario fazer o download de nada mais a nao ser que seja necessário compilar ou injectar o código na blockchain.

+++
### SOLIDITY

Link para testar:

https://ethereum.github.io/browser-solidity/

+++
### SOLIDITY

* `Solidity` é uma linguagem de programação de alto nível cuja sintaxe é similar ao Javascript e está desenhada para compilar bytecode para a Ethereum Virtual Machine (EVM).

* Protege o programador com limites para registos, strings e valores.

---

## Máquina Virtual de Ethereum - EVM

* Uma máquina virtual completa de 256 bits onde pode ser executado qualquer byte code (opcode) EVM arbitrário. É distribuída, suporta transações, smart contracts e DAPPS.
+++
### Máquina Virtual de Ethereum - EVM
* A EVM tal como qualquer outra VM tem overhead. Nao e totalmente eficiente mas e portável. Executa bytecode.

+++
### Máquina Virtual de Ethereum - EVM
* Built for Ether to process transactions.

* Comparável a outras máquinas virtuais como a JVM. Stack based.

---

## Programas de Interesse
+++
### DAPPS

* Augur - Mercados Descentralizados de Previsão do Futuro
https://augur.net

+++
### DAPPS
* Golam - Worldwide Super Computer
https://golem.network

+++
### DAPPS
* TransActiveGrid - Energy Marketplace peer to peer
http://transactivegrid.net

+++
### DAPPS
* Para ver mais exemplos de DAPPS - http://dapps.ethercasts.com

---

## BUY ETHER (FUEL - GAS)

* Kraken (www.kraken.com)
* Coinbase
* Poloniex
* CEX.IO
* Coinhouse

---

## PREÇO do ETHER em 2017-10-30
 (fonte coinmarketcap.com)
![ethereum valuation graph](https://s3.eu-west-2.amazonaws.com/braga-blockchain/Screenshot+2017-10-31+00.09.27.png)


---

## Perguntas ?

Emanuel Mota 

twitter: @emota7
github: emanuel

