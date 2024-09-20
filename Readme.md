# Projeto Tradutor com Flask e Azure

Bem-vindo ao projeto Tradutor! Este projeto utiliza várias ferramentas e tecnologias para criar uma aplicação web simples que traduz textos usando a API de Tradução da Azure. 🚀

## Funcionalidades

- **Tradução de Texto**: Digite um texto em um campo e veja a tradução em outra página.
- **Interface Simples**: Interface amigável criada com Bootstrap.
- **Ambiente Seguro**: Uso de variáveis de ambiente para proteger suas chaves de API.

<img src="img/Captura de tela 2024-09-20 160037.png" alt="Minha Imagem">

<br>

<img src="img/Captura de tela 2024-09-20 160730.png" alt="Minha Imagem">


## Tecnologias Utilizadas

- **Flask**: Framework web para Python.
- **Azure Translator API**: Serviço de tradução de texto.
- **Bootstrap**: Framework CSS para criar interfaces responsivas.
- **.env**: Arquivo para armazenar variáveis de ambiente.
- **Ambiente Virtual**: Para gerenciar dependências do Python.
- **Git**: Controle de versão.
- **.gitignore**: Para ignorar arquivos desnecessários no repositório.
- **Python**: Linguagem de programação principal.


## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/projeto-tradutor.git
   cd projeto-tradutor
2. **Crie e ative um ambiente virtual**:
   ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
3. **Instale as dependência**:
   ```bash
    pip install -r requirements.txt
4. **Configure as variáveis de ambiente**:
    * Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API da Azure:
   ```bash
    AZURE_API_KEY=sua_chave_aqui
5. **Execute a aplicação**:
   ```bash
    flask run
6. **Acesse a aplicação**:
   * Abra seu navegador e vá para `http://127.0.0.1:5000`

<br>
<br>

# Estrutura do Projeto
    ```bash
    projeto-tradutor/
      │
      ├── templates/
      │   ├── index.html  # Página principal com o campo de texto
      │   └── result.html  # Página de resultado da tradução
      │
      ├── app.py  # Arquivo principal da aplicação Flask
      ├── .env  # Arquivo de variáveis de ambiente (não incluído no repositório)
      ├── .gitignore  # Arquivo para ignorar arquivos desnecessários
      ├── requirements.txt  # Lista de dependências do Python
      └── README.md  # Este arquivo!
      
<br>

<h1> Contribuição</h1>
Sinta-se à vontade para contribuir com este projeto! Faça um fork, crie uma branch e envie um pull request. Qualquer ajuda é bem-vinda! 😊


