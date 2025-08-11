# pagina-web-wordpress-mysql-docker
Exemplo de criação de uma página web utilizando wordpress, mysql e docker compose

Visão Geral do Projeto
Este projeto demonstra a criação e orquestração de um blog WordPress completo em um ambiente containerizado. Todo o processo foi realizado exclusivamente via terminal Linux, desde a configuração inicial do servidor até a implantação final.

A arquitetura foi implementada em um servidor VPS da Hostinger e é definida no arquivo docker-compose.yml, que estabelece dois serviços essenciais:

WordPress: O sistema de gerenciamento de conteúdo (CMS) do blog.

MySQL: O banco de dados para armazenar todas as informações do WordPress.

A comunicação entre os containers é gerenciada por uma rede interna do Docker. Para acessar o blog, mapeamos a porta 8080 do servidor para a porta 80 do container do WordPress, resolvendo um conflito de porta existente.

Tecnologias e Ferramentas Utilizadas
Terminal Linux: Todo o projeto foi construído e gerenciado via linha de comando.

Hostinger: Plataforma de hospedagem do servidor VPS.

Docker: Ferramenta de containerização.

Docker Compose: Orquestrador de aplicações multi-container.

WordPress: CMS robusto para criação de blogs e sites.

MySQL: Sistema de gerenciamento de banco de dados relacional.

Autor: João Paulo Pereira Zanela
