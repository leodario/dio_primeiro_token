# Dio Criando ToKen do Zero
## Treinamento criando token com faucet ethereum goerli

Neste treinamento o instrutor Ricardo Zago ensina a criar um Token do Zero, ensinando um passo a passo para a configuração da Wallet Metamask e do RPC info.

O primeiro passo foi criar a carteira:

<div align-"center">
![carteira metamask](https://github.com/leodario/dio_primeiro_token/assets/6862531/959ed22e-4c55-45e6-a622-88f90baac24e)
</div>

Logo após escolhi a rede de teste Goerli:

<div align-"center">
        ![rede de teste goerli](https://github.com/leodario/dio_primeiro_token/assets/6862531/a17652ff-c7ab-4a40-92ca-e59a73b2b4a0)
</div>

Para ter criptomedas de teste você terá que pesquisar no google moedas faucetes, que são utilizadas somente para teste "faucet ethereum goerli"

Que após meneirar um valor mínimo para fazer o teste iremos para a próxima etapa:

<div align-"center">
![carteira metamask](https://github.com/leodario/dio_primeiro_token/assets/6862531/959ed22e-4c55-45e6-a622-88f90baac24e)
</div>

Utilizamos a IDE REMIX https://remix.ethereum.org/

O código está no repositório chamando token.sol.

Utilizei a versão // SPDX-License-Identifier: GPL-3.0 - pragma solidity ^0.8.7.

Tem poucas diferenças no código basicamente a diferença está onde você insere seu código token, 
Exemplo:
```
constructor() {
        _totalSupply = 1000000;
        balances[0xAf25A94D2983EF88BDbb86788F1C211D8c85A788] = _totalSupply;
    }
```
Após isso é só compilar e realizar o deploy ;)
