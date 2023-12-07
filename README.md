# Dio Criando ToKen do Zero
## Treinamento criando token com faucet ethereum goerli

Neste treinamento o instrutor Ricardo Zago ensina a criar um Token do Zero, ensinando um passo a passo para a configuração da Wallet Metamask e do RPC info.
Utilizamos a IDE REMIX https://remix.ethereum.org/
Utilizei a versão // SPDX-License-Identifier: GPL-3.0 - pragma solidity ^0.8.7
Tem poucas diferenças no código basicamente a diferença está onde você insere seu código token, 
Exemplo:
constructor() {
        _totalSupply = 1000000;
        balances[0xAf25A94D2983EF88BDbb86788F1C211D8c85A788] = _totalSupply;
    }
