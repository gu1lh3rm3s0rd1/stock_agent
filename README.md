# Estoque Agent

Agente de estoque com streamlit e langchain, podendo selecionar diferentes modelos de IA para responder as perguntas.

## Recursos Utilizados

- **Streamlit**: Biblioteca para criar interfaces web interativas.
- **LangChain**: Framework para construir aplicações de linguagem natural.
- **ChromaDB**: Banco de dados vetorial para armazenar e recuperar embeddings.
- **OpenAI**: Modelo de linguagem para geração de texto.

## Funcionalidades

- Carregamento e indexação de documentos em ChromaDB.
- Recuperação de informações relevantes com base em consultas do usuário.
- Geração de respostas contextuais utilizando modelos de linguagem avançados.
- Interface de usuário interativa para conversação com o agente.

## Requisitos

- Python 3.8 ou superior
- Conta na OpenAI para acesso à API de modelos de linguagem.

## Instalação

1. Clone este repositório
2. Navegue até o diretório do projeto
3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure suas variáveis de ambiente, incluindo a chave da API da OpenAI.
5. Execute o aplicativo Streamlit:
   ```bash
   streamlit run app.py
   ```
