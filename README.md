## CryptoWalletManager

Este é um projeto de uma carteira de criptomoedas simples desenvolvida em TypeScript, utilizando as bibliotecas BIP39, BIP32 e BitcoinJS-lib. A carteira gerada é para a rede Bitcoin Testnet.

### Funcionalidades

- Geração de carteira Bitcoin Testnet com endereço, chave privada e seed (frase mnemônica) aleatórias.
- Exibição dos detalhes da carteira no console.

### Pré-requisitos

- Node.js instalado
- npm (Node Package Manager) instalado

### Instalação

1. Clone este repositório:

   ```
   git clone https://github.com/seu-usuario/cryptowalletmanager.git
   ```

2. Navegue até o diretório do projeto:

   ```
   cd cryptowalletmanager
   ```

3. Instale as dependências:

   ```
   npm install
   ```

### Executando o projeto

1. Compile o código TypeScript:

   ```
   npm run build
   ```

2. Execute o projeto:

   ```
   npm start
   ```

### Detalhes da Carteira Gerada

Ao executar o projeto, será exibido no console os detalhes da carteira gerada, incluindo:

- **Endereço**: O endereço Bitcoin associado à carteira.
- **Chave Privada**: A chave privada que pode ser usada para acessar os fundos da carteira.
- **Seed (Frase Mnemônica)**: Uma frase mnemônica que pode ser usada para regenerar a carteira no futuro.

### Tecnologias Utilizadas

- TypeScript
- Node.js
- BIP39
- BIP32
- BitcoinJS-lib

### Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.