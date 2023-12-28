# Formulário de Requisição POST

Este é um simples formulário HTML que realiza uma requisição POST assíncrona para um servidor. O código inclui um script JavaScript que utiliza a função fetch para enviar dados do formulário para um servidor remoto.
Como Funciona

    HTML Formulário:
        Um formulário é criado com campos para o nome, e-mail e CPF.
        O formulário possui uma função JavaScript associada ao botão "Enviar".

    JavaScript Função fazerRequisicao():
        A função é chamada quando o botão "Enviar" é clicado.
        Obtém os valores dos campos do formulário (nome, e-mail, CPF).
        Constrói uma URL com os parâmetros do formulário.
        Realiza uma requisição POST assíncrona para a URL usando fetch.
        Processa a resposta:
            Se a resposta é bem-sucedida (resposta.ok), exibe os dados recebidos em um alerta.
            Solicita uma resposta do usuário através de um prompt.
            Exibe informações no console.
            Se houver erro na requisição, exibe um alerta de erro.

Como Utilizar

    Clone ou faça o download deste repositório.
    Abra o arquivo index.html em um navegador web.
    Preencha o formulário com informações válidas.
    Clique no botão "Enviar" para enviar a requisição POST.
    Observe os alertas e as mensagens no console.

Requisitos

    Navegador web moderno com suporte a JavaScript.
