# promptn8n

Passo 1 - Definir Automação
Quero criar uma automação no N8N para registar e organizar automaticamente novos leads recebidos através de um formulário de contacto.

Público ou responsável:
Equipa comercial.

Resultado esperado:
Receber os dados do novo lead, validar as informações, guardar o contacto e notificar a equipa comercial para que possa fazer o acompanhamento.

---

Passo 2 - Adicionar contexto e regras
Ferramentas envolvidas:
N8N, formulário de contacto, Google Sheets e Gmail.

Fluxo desejado:
1. Receber os dados de um novo lead através de um formulário.
2. Verificar se o nome e o endereço de e-mail foram preenchidos.
3. Validar se o endereço de e-mail apresenta um formato válido.
4. Registar os dados do lead no Google Sheets.
5. Enviar uma notificação por e-mail para a equipa comercial.
6. Enviar uma mensagem de confirmação para o lead.

Regras importantes:
Não registar leads sem nome ou endereço de e-mail válido.
Se os dados forem inválidos, o lead não deve avançar no fluxo.
Os dados devem ser registados de forma organizada na folha de cálculo.

---
Passo 3 - Prompt final
Atue como um especialista em N8N.

Crie uma automação para registar e organizar automaticamente novos leads recebidos através de um formulário de contacto.

Público:
Equipa comercial.

Ferramentas envolvidas:
N8N, formulário de contacto, Google Sheets e Gmail.

Fluxo:

1. Receber os dados de um novo lead através de um formulário.
2. Verificar se o nome e o endereço de e-mail foram preenchidos.
3. Validar se o endereço de e-mail apresenta um formato válido.
4. Se os dados forem válidos, registar o lead no Google Sheets.
5. Enviar uma notificação por e-mail para a equipa comercial com os dados do novo lead.
6. Enviar uma mensagem de confirmação para o lead.
7. Se os dados forem inválidos, interromper o fluxo e não registar o lead.

Regras:
Não permitir que leads sem nome ou com endereço de e-mail inválido sejam registados.
Os dados devem ser guardados de forma organizada no Google Sheets.
A equipa comercial deve ser notificada apenas quando o lead tiver passado pelas validações.
O fluxo deve possuir uma lógica clara para tratar dados inválidos.

Explique quais os nós do N8N que devem ser utilizados, a função de cada nó e a lógica de funcionamento do workflow.
