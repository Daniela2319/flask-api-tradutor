# Projeto Tradutor com Flask e Azure

Projeto Tradutor! Este projeto utiliza várias ferramentas e tecnologias para criar uma aplicação web simples que traduz textos usando a API de Tradução da Azure. 🚀

## Funcionalidades

- **Tradução de Texto**: Digite um texto em um campo e veja a tradução em outra página.
- **Interface Simples**: Interface amigável criada com Bootstrap.
- **Ambiente Seguro**: Uso de variáveis de ambiente para proteger suas chaves de API.

<img src="img/Captura de tela 2024-09-20 160037.png" alt="Minha Imagem" width="800" >

<br>

<img src="img/Captura de tela 2024-09-20 160730.png" alt="Minha Imagem" width="800"  >


## Tecnologias Utilizadas

- **Flask**: Framework web para Python.
- **Azure Translator API**: Serviço de tradução de texto.
- **Bootstrap**: Framework CSS para criar interfaces responsivas.
- **.env**: Arquivo para armazenar variáveis do sistema.
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
5. **Ativar o modo de desenvolvimento**
   * Antes de rodar o servidor, é importante ativar o modo de desenvolvimento para facilitar a visualização de erros e mudanças automáticas.
   * Esse comando ativa o ambiente de desenvolvimento.
   ```sh
     set FLASK_ENV=development

6. **Execute a aplicação**:
   * Depois de ativar o ambiente de desenvolvimento, execute o servidor com o comando:
   ```bash
    flask run
7. **Acesse a aplicação**:
   * Abra seu navegador e vá para `http://127.0.0.1:5000`

<br>
<br>

# Estrutura do Projeto
```sh
projeto-tradutor/
  │
  ├── templates/
  │   ├── index.html  # Página principal com o campo de texto
  │   └── result.html  # Página de resultado da tradução
  │
  ├── app.py  # Arquivo principal da aplicação Flask
  ├── .env  # Arquivo de variáveis do sistema (não incluído no repositório)
  ├── .gitignore  # Arquivo para ignorar arquivos desnecessários
  ├── requirements.txt  # Lista de dependências do Python
  └── README.md  # Este arquivo!
```

<br>

<h1> Contribuição</h1>
Sinta-se à vontade para contribuir com este projeto! Faça um fork, crie uma branch e envie um pull request. Qualquer ajuda é bem-vinda! 😊


