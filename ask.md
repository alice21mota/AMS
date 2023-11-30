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
  - Adicionar no relatório uma frase que destaque que sempre que há alterações no SCM, ele próprio notifica os fornecedores
  - TODO: alterar o estado de rejeito


## P2 

- [X] Como representar o SCM
    - Não representar
- [ ] Como começar o coordenador
- [ ] Eventos paralelos para notificar o coordenador de loja e o operador de transporte
- [ ] como representar quando não recebemos a encomenda
- [ ] Como representar que a encomenda foi aceite
- [X] Como representar que todas as encomendas foram arrumadas -> não há o multiple
  - Gateway multipla que pergunta se já todas as lojas enviaram mensagem