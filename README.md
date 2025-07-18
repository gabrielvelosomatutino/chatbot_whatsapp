**Chatbot Básico para Atendimento no WhatsApp**

**Introdução**

Este projeto apresenta um chatbot de estrutura básica para WhatsApp, desenvolvido para servir como um ponto de partida para a automação de atendimento ao cliente. O bot foi projetado para responder a perguntas frequentes através de um menu interativo, oferecendo informações pré-definidas de forma rápida e direta, ideal para pequenos negócios ou para desenvolvedores que estão iniciando com a automação de WhatsApp.

**Tecnologias Utilizadas**

A solução foi construída utilizando a linguagem Node.js e as seguintes bibliotecas principais:

whatsapp-web.js: Biblioteca central para a integração e automação de mensagens no WhatsApp, permitindo que o script se conecte e interaja como um cliente normal.

qrcode-terminal: Utilitário responsável por gerar o QR Code de autenticação diretamente no console, facilitando a conexão inicial da conta de WhatsApp ao bot.

**Funcionalidades Principais**

Os objetivos e funcionalidades deste chatbot são diretos e focados na simplicidade:

Ativação por Palavras-Chave: O bot inicia a interação ao receber mensagens com saudações comuns como "Olá", "Oi" ou a palavra "Menu".

Menu de Opções Numérico: Ao ser ativado, ele cumprimenta o usuário e apresenta um menu principal com cinco opções numeradas, guiando o cliente para as informações mais comuns (como funciona, valores, benefícios, etc.).

Respostas Pré-definidas: Para cada opção numérica selecionada pelo usuário (de 1 a 5), o bot envia uma resposta de texto específica que está diretamente programada no código.

Simulação de Interação Humana: O script utiliza delays e exibe o status "digitando" antes de enviar as respostas, criando uma experiência de conversação mais fluida e natural para o usuário.

**Conclusão**

Este chatbot demonstra os fundamentos da automação no WhatsApp de forma clara e objetiva. Ele serve como uma excelente base para desenvolvedores que desejam explorar e construir soluções de atendimento mais complexas, podendo evoluir para incluir funcionalidades como persistência de dados, integração com APIs externas ou processamento de linguagem natural (PLN).

**Como Utilizar Este Repositório**

Este repositório contém o código-fonte em um único arquivo chatbot.js. Para executá-lo, siga os passos:

**Clone o repositório:**

git clone https://github.com/gabrielvelosomatutino/chatbot_whatsapp.git

cd chatbot_whatsapp

**Instale as dependências:**

npm install

**Execute o bot:**

node chatbot.js

**Autenticação:**

Um QR Code aparecerá no seu terminal.

Abra o WhatsApp no seu celular, vá em Configurações > Aparelhos conectados > Conectar um aparelho e escaneie o código para iniciar a sessão. O bot estará online e pronto para responder.

*Contribuições**

Contribuições para a melhoria deste projeto são bem-vindas. Sinta-se à vontade para enviar pull requests com correções de bugs, refatoração de código ou sugestões de novas funcionalidades básicas.

**Contato**

Para mais informações ou dúvidas relacionadas a este projeto, entre em contato com [Gabriel Veloso] via e-mail: [velosogabriel5@gmail.com].
