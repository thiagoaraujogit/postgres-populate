# Knex - Database setup

Script usado para fazer setup do banco de dados ao rodar os testes automatizados nos workflows.

O banco de dados é iniciado em um container Docker, usando a imagem **postgresql:stable-alpine** (uma versão menor e compactada do banco postgres).