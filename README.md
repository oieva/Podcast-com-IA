# Projeto de IA - Integração de Ferramentas

Bem-vindo ao repositório do nosso projeto de Inteligência Artificial! Este documento descreve a estrutura e o objetivo do projeto, bem como as ferramentas utilizadas durante o desenvolvimento.

---

## Visão Geral
Este projeto combina diversas ferramentas de Inteligência Artificial para criar uma solução integrada e inovadora. Utilizamos as seguintes tecnologias para atingir nossos objetivos:

- **[MidJourney](https://www.midjourney.com/):** Para geração de imagens a partir de prompts textuais.
- **[Eleven Labs](https://elevenlabs.io/):** Para síntese de voz realista e narrações baseadas em texto.
- **[Spotify Creators](https://creators.spotify.com/):** Para integração e recomendação de conteúdo de Podcast. 
- **ChatGPT (OpenAI):** Para interações baseadas em linguagem natural e automação de tarefas complexas.

---

## Funcionalidades Principais

### 1. **Geração de Conteúdo Visual**
Utilizamos o Chat GPT para criar imagens únicas e personalizadas com base nas entradas fornecidas pelo usuário.
 
Você é um artista criativo em capas de vídeos e podcasts, crie uma imagem de capa de podcast voltado ao mundo de erp, a capa precisa conter uma boneca fofa de uma mulher caucasiana cabelos ruivos e headset azul, olhos castanhos escuros sentada em uma mesa de podcast com cores que remetam ao erp business central e precisa ser bem criativa a imagem. Regras negativas: Nada de simulação de rostos reais



Aqui está a capa criativa do podcast voltada ao mundo de ERP. A personagem é uma boneca estilizada com cabelos ruivos, headset azul, e está em um ambiente que reflete elementos do Business Central. Espero que você goste! Caso precise de ajustes, é só me avisar. 😊

De <https://chatgpt.com/c/6776f7df-f034-8004-84ef-d1d222f7d57f> ![image](https://github.com/user-attachments/assets/0b198e3e-6c08-49d7-9ca8-088bef878ace)



### 2. **Síntese de Voz**
A integração com o Eleven Labs permite converter textos em narrações de alta qualidade, ideais para aplicações multimídia.
Usei o gpt para montar o roteiro do podcast usando regras e regras negativas.
Abaixo inseri o prompt

Dito pelo ChatGPT:
ChatGPT
Entendido! Vou criar um roteiro seguindo suas instruções. Vamos começar:

[Roteiro do Podcast - Level Up ERP]
[INTRODUÇÃO]
"Fala, galera! Hoje vamos embarcar em uma viagem fascinante no universo do Business Central, um sistema que está revolucionando a gestão de empresas. Se você gosta de tecnologia e eficiência no mundo corporativo, esse é o seu lugar! Eu sou a Eva e vou guiar você nessa jornada cheia de descobertas incríveis!"
[CURIOSIDADE1]
"Você sabia que o Business Central tem uma funcionalidade de navegação que deixa muitos concorrentes no chinelo? Com a sua interface super intuitiva, é possível encontrar qualquer informação em segundos, graças à barra de pesquisa universal. Digite o que precisa, e o sistema apresenta relatórios, registros e até configurações relacionadas. Isso economiza tempo e reduz erros de busca. Fantástico, né?"
[CURIOSIDADE2]
"E não para por aí! Uma das maiores vantagens do ERP Business Central é sua compatibilidade impressionante. Ele se integra perfeitamente a outros produtos da Microsoft, como o Teams e o Outlook. Imagine estar numa reunião no Teams e acessar dados financeiros em tempo real ou criar faturas diretamente pelo Outlook. A sinergia entre as ferramentas faz toda a diferença!"
[FINALIZAÇÃO]
"Bom, pessoal, chegamos ao final do nosso papo de hoje. Espero que tenha curtido essas curiosidades sobre o Business Central. Eu sou a Eva, e esse foi o Level Up ERP desta semana. Até a próxima!"

De <https://chatgpt.com/c/6776f7df-f034-8004-84ef-d1d222f7d57f> ![image](https://github.com/user-attachments/assets/cfdf0399-8876-4f99-9a04-5c1c0bf1b1b4)



### 3. **Integração Musical**
Com o Creators do Spotify, oferecemos o podcast para o Nicho de tecnologia. [Episódio consta aqui](https://open.spotify.com/episode/0YRbgv59wt6gO6b6wQrygL?si=FUbgJfhITieE2lBT4lVJMQ)


### 4. **Interações Baseadas em Linguagem Natural**
O ChatGPT é utilizado para fornecer uma interface interativa, respondendo a perguntas, oferecendo sugestões e automatizando processos criativos.

---

## Requisitos de Instalação
Para executar o projeto localmente, você precisará de:

1. Python 3.8 ou superior.
2. Dependências listadas no arquivo `requirements.txt`.
3. Chaves de API para:
   - MidJourney (conta ativa)
   - Eleven Labs
   - Spotify Developer
   - OpenAI (para acesso ao ChatGPT).

### Passos:
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_projeto.git
   ```
2. Navegue para o diretório do projeto:
   ```bash
   cd seu_projeto
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure as variáveis de ambiente com suas chaves de API no arquivo `.env`.

---

## Estrutura do Repositório

```
.
├── data/                  # Dados de entrada/saída
├── docs/                  # Documentação adicional
├── src/                   # Códigos fonte
│   ├── midjourney/        # Integração com MidJourney
│   ├── elevenlabs/        # Módulo de síntese de voz
│   ├── spotify/           # Integração com Spotify
│   └── chatgpt/           # Interação com ChatGPT
├── .env                   # Configuração de variáveis de ambiente
├── requirements.txt       # Dependências do projeto
└── README.md              # Este documento
```

---

## Como Contribuir
Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para sua funcionalidade:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça as alterações e commite:
   ```bash
   git commit -m "Adiciona minha nova feature"
   ```
4. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

## Contato
Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:
- **Email:** evelynsousacontabilidade@gmail.com
- **GitHub:** [soieva](https://github.com/oieva)

Agradecemos por explorar nosso projeto!


