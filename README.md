# Style Guide
Project com Material Design
---
## Instalação
- Baixe projeto em sua máquina
- Acesse o diretório do projeto local
- Rode os comandos:

```
npx create-react-app
    nome do projeto: app
// instalando a biblioteca de design system -> mui (dentro da pasta app)     
yarn add @mui/material @emotion/react @emotion/styled
// instalando icon
yarn add @mui/icon-material
npm install recharts
```
---
## Para quem for olhar o layout, basta ter o node instalado e usar esses codigo dentro do projeto clonado.

```
yarn install
yarn start

```
---

- O projeto irá rodar em [http://localhost:3000](http://localhost:3000) 
- Analise o código e implemente outros componentes do Material UI: [https://mui.com/pt/components/](https://mui.com/pt/components/alert/)

## React libs & document
Documentação oficial: 
- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
- [React documentation](https://reactjs.org/).
- [bold] (https://bold.bridge.ufsc.br/).

---

## Componentização
User interface Design
    Padronização
    Reutilização
    Produtividade

## Agilidade
Process in development
    Trabalho em equipe
    Ciclos Incrementais
    Geração de conhecimento
Framework ágil
    Scrum
    xp
    kambam

---
# Anotação Build in Delivery

## SDE
Software Development Environment
    Desenvolvimento
    Beta
    Produção

## Web Server
Servidores web
    Hospedagem compartilhada
    IaaS - Infrastructure as a Service
    PaaS - Platform as a service

    |  Informações tabelada                      |
    |--------------------------------------------|
    |  Protocolo    | Tipo de Aplicação | Porta  |
    |  ------------ | ----------------- | ------ |
    |  HTTPS        | Website           | 80     |
    |  HTTP         | Website           | 443    |
    |  FTP          | Arquivos          | 20     |
    |  SSH/SFTP     | Arquivos          | 22     |
    |  Whois        | Domínios          | 43     |
    |  POP3(e-mail) | E-mails           | 110    |
    |  IMAP4        | E-mails           | 143    |
    |  MySQL        | Banco de dados    | 3306   |
    |  PostgreSQL   | Banco de dados    | 5432   |

## Tipos de testes
    Funcional
        O próprio desenvolvendor testa as funcionalidades para ver se há uma ruptura para dar manutentação
    Regressivo
        Checar se o que foi desenvolvido recentemente teve um impacto positivo em comparação à aplicação antiga. (Melhoria continua)
    Unitário
        Foco maior, tentar analisar todas funções e métodos desenvolvidos, focado mais no código, existe ferramentas automatizadas para esses testes.
        (metodologia test driven development)
[Link do JestJs](https://jestjs.io/pt-BR/)  
    Segurança
        São teste mais focais, checar vulnerabilidade. Existe ferramentas.
    Performance
        Strees test, teste do sistema, para ver se ele aguenta um grande volume de acesso por exemplo.

# Git no console.
Nesse etapa estou configurando meu workspace para gerar a consepção de trabalho em grupo entre 2  ou mais breanch de desenvolvimento.

## Anotação para criação ambiente de development

$ git checkout -b dev `para criar uma breach novade desenvolvimento`

$ git add e commit criando  o commet `é recomendado com a seguinte sintaxe "feat: aqui vai a expecificação feito."`

$ git push --set-upstram origin dev `nesse caso como não estou desenvolvendo com uma equipe, não será necessario fazer pull request]`.

Após ser passado pela etapa de QA (`Um engenheiro de controle de qualidade é um profissional que encontra e corrige bugs em um produto ou programa antes de seu lançamento`), podemos subir a requisção para o ambiente de Homologação

## Anotação para criação ambiente de homologação

$ git checkout -b "beta"
---
$ git push --set-upstram origin beta
---
$ git fetch --all `Para pegar todas as alterações`
---
$ git merge main `compara se a branch main ta atualizada`
---
$ git checkout main `Para se locomover até a branch main.`
---
$ git merge beta `compara se a branch beta ta atualizada`

---

# FTP
File Transfer Protocolo
https://filezilla-project.org/ `Programa que faz uma interface com ftp`

## SSH
    - Protocolo Padrão de acesso do linux
    - Criptografado por padrão
    - Não consome muito recurso
    - Envia apenas a saída dos comandos
    - Já  vem instalado na maioria das distribuições linux
    - Server já vem instalado
