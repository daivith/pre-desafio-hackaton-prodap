# Pré desafio do Hackaton do Prodap
   ## Desafio
   O desafio consiste em criar um crud de pessoas com as informações abaixo, utilizando uma das seguintes linguagens/frameworks: Javascript, PHP, Python, Adonis.js, Express.js, Laravel, Lumen, Flask ou Django.
   ### GET - Listar pessoas:    
   ``http://localhost:3000/pessoas``
   - O resultado deve ser algo como:
   ```
   {
      id: 1,
      nome: Vitor hugo,
      cidade: Macapá,
      data_nascimento: 22/04/1990
   }
   ```
   ### POST - Cadastrar pessoas
   ``http://localhost:3000/pessoas``
   - A entrada deve ser algo como:
   ```
   {
      nome: Vitor hugo,
      cidade: Macapá,
      data_nascimento: 22/04/1990
   }
   ```
   ### PATCH - Atualizar pessoa
   ``http://localhost:3000/pessoas/{pessoa_id}``
   - A entrada deve ser algo como:
   ```
   {
      nome: Vitor Santos,
      cidade: Santana,
      data_nascimento: 22/04/1990
   }
   ```
   ### DELETE - Deletar pessoa
   ``http://localhost:3000/pessoas/{pessoa_id}``
   - A saida deve ser algo como:
   ```
   {
      "msg": "sucesso"
   }
   ```
  #### OBS: A utilização de docker será um diferencial
   ## Entrega do desafio
   Para submeter o desafio para comissão, você deve:
   * Se cadastrar no evento da expotec: https://expotecamapa.com.br/cadastro/
   * Criar um Readme.md com as informaçoes basicas para executar seu desafio 
   * Subir o codigo finalizado no próprio repositório do github **(Deve estar público)**
   * Submeter o link do desafio finalizado para o email: jose.barbosa@prodap.ap.gov.br
   ## Avisos dos selecionados
   O selecionados receberão um email informando que poderão comparecer a hackathon promovida pelo PRODAP. 
