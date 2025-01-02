# Projeto de IA - Integração de Ferramentas

Bem-vindo ao repositório do nosso projeto de Inteligência Artificial! Este documento descreve a estrutura e o objetivo do projeto, bem como as ferramentas utilizadas durante o desenvolvimento.

---

## Visão Geral
Este projeto combina diversas ferramentas de Inteligência Artificial para criar uma solução integrada e inovadora. Utilizamos as seguintes tecnologias para atingir nossos objetivos:

- **[MidJourney](https://www.midjourney.com/):** Para geração de imagens a partir de prompts textuais.
- **[Eleven Labs](https://elevenlabs.io/):** Para síntese de voz realista e narrações baseadas em texto.
- **[Spotify Creators]((https://creators.spotify.com/):** Para integração e recomendação de conteúdo de Podcast.
- **ChatGPT (OpenAI):** Para interações baseadas em linguagem natural e automação de tarefas complexas.

---

## Funcionalidades Principais

### 1. **Geração de Conteúdo Visual**
Utilizamos o MidJourney para criar imagens únicas e personalizadas com base nas entradas fornecidas pelo usuário.

### 2. **Síntese de Voz**
A integração com o Eleven Labs permite converter textos em narrações de alta qualidade, ideais para aplicações multimídia.

### 3. **Integração Musical**
Com a API do Spotify, oferecemos recomendações musicais e criação de playlists dinâmicas baseadas no contexto do usuário.

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


