# Solicitação de Serviço

## Objetivo do Projeto

Este projeto tem como objetivo proporcionar uma solução prática e eficiente para a solicitação de serviços, com integração direta a um sistema de gestão visual baseado em Kanban no Notion. A plataforma automatiza também o envio de e-mails por meio da ferramenta Make, garantindo uma comunicação contínua e eficiente.

A combinação dessas tecnologias oferece um gerenciamento de tarefas otimizado, permitindo a visualização do progresso em tempo real e a automação de fluxos de trabalho. Isso elimina a necessidade de intervenções manuais repetitivas, aumentando a produtividade e a eficiência geral dos usuários.

![image](https://github.com/user-attachments/assets/27fc2afc-40f0-4c50-b333-61efdaaae9cd)

## Fluxo do Processo

O fluxo de processo é estruturado da seguinte forma:

1. **Preenchimento do Formulário**  
   O cliente preenche um formulário incorporado na página, que é um **iframe** do Tally. Este formulário coleta as informações necessárias para a solicitação do serviço.

2. **Integração com Notion**  
   Após o envio do formulário, os dados são automaticamente integrados ao Notion, utilizando uma conexão previamente configurada. O Notion, por sua vez, organiza as informações recebidas no formato de **Kanban**, permitindo o acompanhamento visual das solicitações.

3. **Automação de E-mails com Make**  
   Após a criação da tarefa no Notion, uma automação é acionada pelo **Make** para enviar um e-mail de confirmação ao cliente e notificar os responsáveis pela execução do serviço. Essa automação garante que todos os envolvidos no processo sejam informados de maneira eficiente.

Esse fluxo de trabalho totalmente integrado proporciona uma experiência ágil e sem a necessidade de intervenções manuais, otimizando a gestão de tarefas e a comunicação com o cliente.
