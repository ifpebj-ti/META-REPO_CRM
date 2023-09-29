# Tutorial para Executar o Projeto Localmente

Este tutorial fornecerá instruções passo a passo para executar o CRM localmente usando o Docker Compose. O projeto utiliza o Docker para criar contêineres isolados que contêm todas as dependências necessárias.

## Pré-requisitos

Antes de começarmos, certifique-se de ter instalado os seguintes componentes em seu sistema:

* [Docker](https://docs.docker.com/get-docker/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## Portas

O sistema possui 4 modulos e 4 banco de dados diferentes, para que cada modulo funcione corretamente as portas defindas no docker-compose devem estar livres no sistema, são elas:

* Modulo Frontend: porta 80
* Modulo Vendas: porta 8081
* Modulo Marketing: porta 8082
* Modulo Análise: porta 8083


* Banco de vendas:
* Banco de Marketing:
* Banco de Análise:
* Banco integrado:

## Passos

Siga estas etapas para executar o projeto localmente:

1. **Clone o repositório:** Comece clonando o repositório do projeto em seu computador:
   `git clone https://github.com/ifpebj-ti/META-REPO_Dockerfile.git`
2. **Navegue até o diretório do projeto:**
   `cd [diretorio do projeto]`
3. **Inicie o projeto com o Docker Compose:
   `docker-compose up -d`**

   Isso criará e executará os contêineres definidos no arquivo `docker-compose.yml` em segundo plano.
4. **Acesse a aplicação:** Após a inicialização bem-sucedida, você pode acessar a aplicação em seu navegador ou usando o endereço IP do contêiner, dependendo da configuração do projeto. Verifique a documentação do projeto para obter detalhes específicos sobre como acessar a aplicação.

## Problemas e Suporte

Se você encontrar problemas ou precisar de suporte, sinta-se à vontade para abrir um issue no repositório do projeto ou entrar em contato com a equipe de desenvolvimento.
