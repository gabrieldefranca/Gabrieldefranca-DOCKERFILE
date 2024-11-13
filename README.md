<<<<<<< HEAD
# Gabrieldefranca-Dockerfile
=======
# Projeto de Automação de Ambientes de Desenvolvimento com Docker e GitHub Actions

Este projeto configura e automatiza o ambiente de desenvolvimento de uma aplicação web composta por três componentes principais: um frontend em React, um backend em Node.js/Express, e um banco de dados PostgreSQL. Cada componente possui seu próprio Dockerfile, o que permite que sejam construídos e testados de maneira independente. 

Os workflows do GitHub Actions foram configurados para build, teste e deploy automáticos. Ao fazer um push para a branch `main`, o workflow `build-and-test.yml` executa a construção e os testes de cada imagem Docker. Caso todos os testes passem, o workflow `deploy.yml` realiza o deploy das imagens para o Docker Hub e simula o envio para o ambiente de produção.
>>>>>>> 8ada598 (commit inicial)