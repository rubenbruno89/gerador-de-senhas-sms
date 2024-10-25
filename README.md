# Gerador de Senhas com SMS
Este projeto é uma aplicação web que permite gerar senhas seguras com diversas configurações (como letras maiúsculas, minúsculas, números e símbolos) e enviar essas senhas por SMS para um número de telefone específico.

# Visão Geral do Projeto
A aplicação permite ao usuário configurar:

IP do servidor SMS
Porta de comunicação
Número de telefone para envio do SMS
Comprimento da senha gerada
Presença de letras maiúsculas, minúsculas, números e símbolos na senha
Após configurar, a senha gerada é exibida na tela e enviada via SMS para o número especificado.

# Recursos
Geração de Senha: Cria senhas com base nas configurações especificadas.
Envio de SMS: Usa o IP e a porta fornecidos para enviar a senha via SMS.
Validação de Entrada: Verifica se os campos estão corretamente preenchidos antes do envio.
Feedback Visual: Exibe mensagens de sucesso ou erro após o envio da senha.
# Pré-requisitos
Para rodar a aplicação, é necessário:

Um servidor SMS configurado no IP e porta especificados.
Navegador moderno com suporte a JavaScript.
# Como Usar
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/gerador-de-senhas-sms.git
Abra o arquivo Gerador de Senhas SMS.html em seu navegador.

Preencha os campos com os detalhes do servidor SMS, número de telefone e preferências de senha.

Clique em "Gerar e Enviar Senha" para gerar a senha e enviá-la por SMS.

# Estrutura do Código
HTML e CSS: Define o layout e estilo da interface.
JavaScript: Lida com a geração de senhas e envio de requisições ao servidor SMS.

# Contribuição
Se você deseja contribuir, por favor:

Faça um fork do projeto.
Crie uma nova branch (git checkout -b feature/nova-feature).
Commit suas mudanças (git commit -am 'Adiciona nova feature').
Envie para o branch (git push origin feature/nova-feature).
Abra um Pull Request.
