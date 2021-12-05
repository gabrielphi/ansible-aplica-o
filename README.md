# ansible-primeiro

Aplicação Ansible estruturada.

Sumario da hierarquia de pastas:

ansible = Diretorio com todas as configurações do Ansible
-- Roles = Diretorio com as configurações separadas por tipo, mysql, webserver e wordpress
-- group_vars = Todas as variaveis configuradas

ssh-key - Diretorio onde o vagrant armazena as chaves privadas para o acesso do ansible

Em roles na pasta ansible existe as tasks, handlers e afins, são basicamente as tarefas que o ansible vai executar.
