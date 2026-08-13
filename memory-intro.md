## Computer Memory
- A memória é o espaço de armazenamento eletronico onde um computador armazena as instruções e os dados que o processador precisa acessar rapidamente. A memória é um componente fundamental de um computador, pois sem ela o Sistema Operacional não funcionaria.
### Comunicação entre a memória e a CPU
- CPU = Processador
- A memória do computador se comunica com a CPU por meio de um sistema estruturado de caminhos e controladores eletronicos, pois assim a CPU pode armazenar e buscar dados de forma eficiente. Abaixo esta uma explicação.

- O principal canal de comunicação entre a CPU e a memória é o barramento do sistema, que é uma coleção de tres tipos de barramentos:
	- Barramento de dados: Transfere o conteúdo (valores, números, caracteres, endereços) entre a CPU e a memória. É o transporte que carrega a informação.
		- É bidirecional, pois a CPU pode ler um dado DA memoria, e tambem escrever um dado NA memoria.
	- Barramento de endereços: Carrega a localização (endereço de memória) que aponta de qual lugar a CPU deve manipular os dados, como ler ou gravar.
		- É unidirecional, APENAS a CPU decide aonde quer acessar, a memoria não pode fazer isso.
	- Barramento de controle: Envia sinais que coordenam e controlam as tarefas, como indicar operações de leitura ou gravação.
		- É bidirecional, a CPU envia comandos e a memoria envia respostas.
	
###### Resumo visual dos 3 barramentos:

| Barramento    | O que transporta       | Direcao                        | Analogia                   |
| ------------- | ---------------------- | ------------------------------ | -------------------------- |
| **Dados**     | O conteudo em si       | Bidirecional                   | A carga                    |
| **Enderecos** | Onde esta o dado       | Unidirecional (CPU -> memoria) | O endereco de entrega      |
| **Controle**  | O que fazer com o dado | Bidirecional                   | As instrucoes do motorista |
