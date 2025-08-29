# Weatherly Data API🌦️
API REST em Flask para consulta de dados meteorológicos históricos.

## 📌 Descrição
O Weatherly é uma aplicação em Python + Flask que disponibiliza uma API REST, desenvolvida para consultar dados de temperatura histórica de diferentes estações meteorológicas.

Os dados são extraídos de arquivos de texto fornecidos e processados com Pandas para facilitar a leitura e filtragem.

A aplicação também possui uma página inicial simples em HTML para exibir a lista de estações disponíveis.

## Funcionalidades
- Listar estações meteorológicas disponíveis
- Consultar temperatura por estação e data
- Consultar todos os dados de uma estação
- Consultar dados anuais de uma estação
- Exibir tabela de estações em página HTML



## 🛠️ Tecnologias Utilizadas
- **Python** – linguagem principal
- **Flask** – framework para criação da API REST
- **Pandas** – manipulação e filtragem dos dados meteorológicos
- **HTML** – renderização da página inicial
- **CSV** – formato dos arquivos de dados fornecidos



## 📚 Aprendizados
Desenvolver o Weatherly foi essencial pra praticar e reforçar ainda mais:
- Desenvolvimento de APIs REST com Flask
- Leitura e manipulação de dados com Pandas
- Criação de rotas dinâmicas em Flask
- Renderização de tabelas HTML usando Jinja
- Organização e processamento de datasets meteorológicos



## ▶️ Como Rodar Localmente
Clone este repositório:
``` bash
git clone https://github.com/gabriel-oligom/weatherly-data-api
cd weatherly-data-api
```
Crie e ative um ambiente virtual:
``` bash
python -m venv venv
source venv/bin/activate   # Linux e/ou Mac
venv\Scripts\activate      # Windows
```

Instale as dependências:
``` bash
pip install flask pandas
```

Execute a aplicação:
``` bash
# Windows
py app.py
# ou 
python app.py

# Linux / Mac
python app.py

```

Acesse no navegador:
``` bash
http://127.0.0.1:5001/home
```

## 📸 Preview

### Página Inicial
![Página Inicial](images\weatherly_full_print.png)