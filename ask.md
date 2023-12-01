# Dúvidas por esclarecer

## A1

- [X] Perguntar diferença entre role / processo 
  - generalizar se já estiver no bpmn
- [X] Ver se os roles que temos são ok -> demasiados detalhes
  - Não representar os que já estão no BPMN
  - Generalizar
- [X] Roles direção e das unidades (dirT e vendas/armazem)
- [X] Funcionários operacionais na loja (subunidade) 
  - TODO: Justificar no relatório o porquê de não termos funcionários
- [X] fornecedores & **operadores de transporte** (forum)
  - Não representar


## A2
> **Não repetir com o BPMN**
- [ ] Ligação do PICKTRU ao serviço do RUN-SCM
- [X] fornecedores --> divisões (produtores e distribuidores)
  - Não é necessário especializar
- [ ] Data Object vs Business Object --> linha 38 da descrição da empresa
- [ ] Serviços / Processo Business Application
- [ ] Coordenador UFC liga a alguma cena?
- [ ] Ter mais atenção aos processes e eliminar roles para teremos mais processes
- [ ] Services da application component


## P1

- [ ] Linha 57 é funcionário operacional ou pode ser o coordenador também?
- [X] Task service vs message (send)
  - Tem de ser task porque há o processo de **criar a mensagem**
- [X] Fornecedor ser notificado
  - TODO: Adicionar no relatório uma frase que destaque que sempre que há alterações no SCM, ele próprio notifica os fornecedores
  - alterar o estado de rejeito


## P2 

- [X] Como representar o SCM
    - Não representar
- [ ] Como começar o coordenador
- [ ] Eventos paralelos para notificar o coordenador de loja e o operador de transporte (linha 140)
- [ ] Condicional no recebimento da encomenda --> passei para catch
- [ ] Confirmar recessão da encomenda (linha 145)
- [X] Como representar quando não recebemos a encomenda
  - Podemos ser nós de escolher como preferimos
- [X] Como representar que a encomenda foi aceite
  - Mensagem 😃
- [X] Como representar que todas as encomendas foram arrumadas -> não há o multiple
  - Gateway multipla que pergunta se já todas as lojas enviaram mensagem

### TODO:
- Não usar 'enviar', 'submeter', etc nas tasks de envio
- Trocar event receive task por task receive task

#### P2
- Pôr no relatótio as cenas do SCM do P2 estão ocultadas -> sempre que se altera o estado do fornecedor, por exemplo, ele é suspenso, é efetuado um registo do SCM
- Pôr no relatótio que quando a encomenda não é entregue, automaticamente não há nada para arrumar na loja
- Loop no alterar as rotas -> segue em frente

#### P1
- Pôr no relatório que "Sempre que for executada uma ação relativa a um fornecedor 92 ainda não conhecido na aplicação SCM, é nesse momento 93 criado um registo novo para esse fornecedor"
- Condicional no pedido de novo documento de candidatura