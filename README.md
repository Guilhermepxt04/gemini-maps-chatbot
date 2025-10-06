
# Rota Acessível - Chatbot com Gemini e Google Maps 🗺️

O **Rota Acessível** é um projeto de uma plataforma desenvolvida para facilitar o planejamento de viagens com foco em acessibilidade no Brasil. Utilizando o poder da **Inteligência Artificial do Google Gemini** e a **API do Google Maps**, a aplicação oferece um assistente de viagens inteligente que compreende as necessidades do usuário, sugere locais acessíveis e os exibe em um mapa dinâmico.


## Funcionalidades 🚀

- **Inteligência Artificial Conversacional**: Integração com a API do Gemini para entender e responder às solicitações do usuário de forma natural.

- **Foco em Acessibilidade**: O chatbot é treinado para ser um especialista em turismo acessível, fornecendo sugestões de hotéis, pontos turísticos e praias adaptadas.

- **Mapa Interativo**: Utiliza a API do Google Maps para exibir os locais mencionados na conversa, adicionando marcadores dinamicamente.

- **Comandos de Voz**: Suporte à Web Speech API para interação por voz, permitindo que o usuário fale com o chatbot e ouça as respostas.

- **Interface Limpa e Responsiva**: Layout que se adapta a diferentes tamanhos de tela, de desktops a dispositivos móveis.

## Tecnologias utilizada 🛠️

- HTML

- CSS

- JavaScript

- [Google Gemini API](https://ai.google.dev/gemini-api/docs?hl=pt-br)

- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript?authuser=1&hl=pt-br)

- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) (para reconhecimento e síntese de voz)

- [Marked.js](https://marked.js.org) (para renderizar a resposta do Gemini em HTML)


## Configurações do projeto ⚙️

Para rodar este projeto em sua máquina local, siga os passos abaixo. Por ser um projeto front-end, você só precisa de um navegador web.

- **1 - Clone o repositório**:

```bash
git clone https://github.com/seu-usuario/gemini-maps-chatbot.git
```

- **2- Configure as Chaves de API**:

Para que a aplicação funcione, você precisará obter suas próprias chaves de API para o Google Gemini e o Google Maps.

**Google Maps API Key**

No arquivo **index.html**, substitua o placeholder SUA CHAVE DO MAPS AQUI pela sua chave da API do Google Maps.

**Arquivo: index.html**

**Linha: 51**

```HTML
<script src="https://maps.googleapis.com/maps/api/js?key=SUA CHAVE DO MAPS AQUI&callback=initMap" async defer></script>
```

**Google Gemini API Key**

No arquivo **js/script.js**, substitua o placeholder **SUA KEY DA API DO GEMINI AQUI** pela sua chave da API do Gemini.

**Arquivo: js/script.js**

**Linha: 1**

```JavaScript
const API_KEY = "SUA KEY DA API DO GEMINI AQUI";
```

- **3- Abra o arquivo index.html**

Após configurar as chaves, basta abrir o arquivo index.html no seu navegador de preferência.
## Como Usar 🕹️
- Abra o arquivo index.html no navegador.

- Digite sua pergunta no campo de texto (ex: "Quais praias acessíveis existem no Rio de Janeiro?").

- Pressione Enter ou clique no botão de enviar.

- A resposta do chatbot aparecerá na tela de chat, e os locais mencionados serão marcados no mapa.

- Você também pode clicar no ícone de microfone para fazer sua pergunta por voz. (Se seu navegador suportar)
## Demonstração 🌐

Veja um video de demonstração no [Linkedin](https://neo-vision-proanos.vercel.app)

