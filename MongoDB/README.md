# MongoDB

### Comandos para inicialização, navegação e interação com Bancos de Dados, Coleções e Documentos

*Antes de utilizar este guia, é importante ter o **MongoDB Community Edition** instalado em sua máquina. Para instalação, siga os passos recomendados para seu sistema operacional através da documentação do MongoDB: https://www.mongodb.com/docs/manual/administration/install-community/*

---

### Iniciar, parar ou reiniciar MongoDB service

- Verificar status do MongoDB service:
  `sudo service mongod status`

- Iniciar o MongoDB service:
  `sudo service mongod start`

- Parar o MongoDB service:
  `sudo service mongod stop`

- Reiniar o MongoDB service:
  `sudo service mongod restart`

- Habilitar ou desabilitar MongoDB service ao inicializar o sistema(Linux):
  `sudo systemclt enable mongod.service`
  `sudo systemclt disable mongod.service`

### Mongo via terminal com MongoDB Shell

MongoDB Shell é uma interface de linha de comando (CLI - command line interface). Em seu terminal, execute o comando: `mongo`. Por padrão, a instância estará rodando na porta `27017`.

Caso queira executá-la em outra porta, basta passar o parâmetro `--port`:
- Exemplo: `mongo --port 3001`.
