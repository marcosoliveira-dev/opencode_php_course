# Aula 1 — OpenCode + Framework PHP

# Objetivo da aula

Nesta aula, você irá conhecer o OpenCode, compreender seu propósito e, na prática, realizar a instalação no Windows 11 utilizando Node.js. 

<br>

Ao final, você terá um primeiro exemplo funcional, criando uma landing page simples diretamente pelo terminal.

<br>

**Apresentar o projeto final** 

[http://barbearia.test/index.php?class=LoginForm](http://barbearia.test/index.php?class=LoginForm)  

<br>

* * *

![](Files/image.png)<br>

## 1\. O que é o OpenCode?

OpenCode é um agente open source que auxilia na escrita e execução de código com qualquer modelo de IA. Ele está disponível como interface baseada em terminal, aplicativo desktop e extensão para IDEs.

<br>

Funciona como um copiloto capaz de gerar, revisar, explicar e refatorar código em projetos reais.

<br>

Ele pode ser utilizado sem criação de conta, pois já inclui um conjunto de modelos gratuitos. Além disso, permite integração com provedores populares como OpenAI, Anthropic e também com modelos locais.

<br>

* * *

## 2\. Por que utilizar o OpenCode?

- Integra IA diretamente ao processo de desenvolvimento.
- Funciona via terminal, aplicativo desktop (BETA)
- Permite trabalhar com arquivos locais e projetos reais.
- Suporta modelos gratuitos e assinaturas existentes (Claude, ChatGPT, Copilot).
- Aceita múltiplos provedores e modelos locais.
- É gratuito, com custos apenas se você conectar serviços externos.
- Garante controle sobre dados, que só são armazenados ao usar modelos gratuitos ou links compartilháveis.

<br>

* * *

## 3\. Instalação no Windows 11

### 3.1 Instalar Node.js

Acessar: [https://nodejs.org](https://nodejs.org)  
Baixar a versão LTS e concluir a instalação.

Verificar:

```
node -v
```

<br>

### 3.2 Instalar OpenCode

Acessar: [https://opencode.ai](https://opencode.ai)

Executar comando no terminal:

```
npm i -g opencode-ai

```

<br>
Executar no terminal:

```
opencode
```

<br>

<br>

* * *

## 4\. Obter o template do Adianti

O template funciona como um gabarito para criação de novos projetos, oferecendo controle de login e permissões por usuários, grupos e programas, suporte a múltiplas unidades e idiomas, gestão de documentos, mensageria e notificações, além de logs de acesso, alterações, SQL, HTTP e REST.

<br>

Nesta aula, o download será realizado apenas para preparar o ambiente. A utilização prática do framework ocorrerá nas próximas aulas.

<br>

Acessar: [https://adiantiframework.com.br/template](https://adiantiframework.com.br/template) Baixar o framework versão 8.4 Extrair para uma pasta de trabalho.

<br>

* * *

## 5\. Exemplo prático

### 5.1 Criar pasta

```
mkdir landing-demo 
cd landing-demo
```

<br>

### 5.2 Iniciar OpenCode

### 5.3 Prompt de exemplo

```
opencode
```

<br>

> Crie uma landing page moderno em HTML e CSS para apresentar um software  de barbearia. Gere os arquivos index.html e style.css.

### 5.4 Abrir arquivos e visualizar no navegador

<br>

* * *

## Encerramento

Nesta aula, você instalou o Node.js, configurou o OpenCode, obteve o template do framework e executou um primeiro uso prático da ferramenta, gerando uma landing page simples por meio de comandos no terminal. Na próxima aula, seguiremos para a utilização do framework no projeto barbearia.

<br>