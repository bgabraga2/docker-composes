# Aplicações NodeJS

Para aplicações Codeigniter, eu costumo utilizar apenas dois containers, um para rodar a aplicação, e outro para o banco de dados **MongoDB**

Neste caso utilizo também um Dockerfile para definir o que exatamente meu container vai executar e como ele vai se comportar

***Importante:*** No meu caso, sempre trabalho com o **npm dev** mas você deve trocar este comando, tanto no ***Dockerfile*** quanto no ***docker-compose.yml*** para o script que você usa para subir suas aplicações.