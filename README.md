## Desafio - Newsletter System
Sistema de newsletter desenvolvido com Laravel 11.

# Descrição
O sistema permitirá que um usuário admin crie tópicos (temas de interesse) e gerencie listas de e-mails associadas a esses tópicos. Os usuários podem se inscrever nessas listas para receber e-mails relacionados ao tópico de seu interesse.

# Requisitos

- O projeto deve ser desenvolvido utilizando Laravel 11.
- É necessário garantir uma cobertura ampla de testes para todas as funcionalidades do sistema.
- O uso de Docker é obrigatório para facilitar a configuração e a execução do ambiente de desenvolvimento.
- O sistema deve fazer uso dos eventos do Laravel para implementar funcionalidades como o envio de e-mails.
- Frontend: Não é necessário desenvolver um frontend para este projeto. O foco será nas funcionalidades de backend.
- Deve ser criado um arquivo README.md com instruções detalhadas sobre como configurar e executar o projeto.
- Uma seed deve adicionar o usuário admin ao banco de dados.

# Funcionalidades

- O usuário admin deve poder adicionar outros usuários não-admins.
- O usuário admin poderá criar topicos (listas de interesse).
- Os usuários não-admins não podem criar topicos.
- Qualquer pessoa apenas com um email, deverá poder se inscrever em um topico.
- Quando o admin ou um outro usuário enviar uma mensagem para um topico, deverá ser encaminhada via email para os usuarios inscritos no topico.
- Endpoint para visualizar as mensagems já enviadas.
