# 🤖 Gerador de Conteúdo com IA

Um gerador de conteúdo inteligente desenvolvido em **Python**, utilizando **Streamlit**, **LangChain** e **Groq (Llama 3.3)** para criar textos otimizados para SEO e adaptados para diferentes plataformas e públicos.

## ✨ Funcionalidades

* Geração automática de conteúdo com IA
* Otimização para SEO
* Escolha da plataforma de publicação
* Definição do tom do texto
* Seleção do tamanho do conteúdo
* Definição do público-alvo
* Inclusão opcional de CTA (Call to Action)
* Inclusão opcional de hashtags
* Uso de palavras-chave para melhorar SEO

---

## 🚀 Tecnologias

* Python 3
* Streamlit
* LangChain
* Groq API
* Llama 3.3 70B Versatile
* python-dotenv

---

## 📂 Estrutura do Projeto

```text
.
├── app.py
├── .env
├── requirements.txt
├── README.md
```

---

## ⚙️ Pré-requisitos

* Python 3.10 ou superior
* Conta na Groq
* Chave de API da Groq

---

## 🔑 Configuração

Clone o repositório:

```bash
git clone https://github.com/gabaoo/Gerador-de-conte-do---Markeing-Python
```

Entre na pasta:

```bash
cd Gerador-de-conte-do---Markeing-Python
```

Crie um ambiente virtual:

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

---

## 🔐 Variáveis de Ambiente

Crie um arquivo chamado `.env` na raiz do projeto.

```env
GROQ_API_KEY=sua_chave_da_groq
```

---

## ▶️ Executando o Projeto

```bash
streamlit run app.py
```

O navegador será aberto automaticamente em:

```
http://localhost:8501
```

---

## 🖥️ Interface

O usuário pode informar:

* Tema
* Plataforma
* Tom
* Tamanho
* Público-alvo
* Inclusão de CTA
* Inclusão de Hashtags
* Palavras-chave para SEO

Após clicar em **Gerar conteúdo**, a IA cria um texto personalizado seguindo todas as configurações escolhidas.

---

## 📋 Exemplo

### Entrada

**Tema**

```
Alimentação saudável
```

**Plataforma**

```
Instagram
```

**Tom**

```
Inspirador
```

**Público**

```
Jovens adultos
```

**SEO**

```
alimentação saudável, bem-estar, qualidade de vida
```

### Saída

Um texto otimizado para Instagram contendo as palavras-chave informadas, adaptado ao público selecionado, com tom inspirador e CTA opcional.

---

## 🧠 Como funciona

1. O usuário preenche o formulário.
2. O Streamlit coleta os dados.
3. Um prompt é criado dinamicamente.
4. O LangChain monta a cadeia (`Prompt → LLM → Parser`).
5. O modelo **Llama 3.3 70B** da Groq gera o conteúdo.
6. O resultado é exibido na interface.

---

## 📦 Dependências

```text
streamlit
python-dotenv
langchain
langchain-core
langchain-groq
```

Ou instale diretamente:

```bash
pip install streamlit python-dotenv langchain langchain-core langchain-groq
```

---

## 📚 Aprendizados

Este projeto foi desenvolvido com o objetivo de praticar:

* Desenvolvimento de interfaces com Streamlit
* Integração com APIs de IA
* Engenharia de Prompt
* LangChain
* Manipulação de variáveis de ambiente
* Boas práticas em Python
* Geração de conteúdo com LLMs

---

## 👨‍💻 Autor

Desenvolvido por **Gabriel Oliveira**.
