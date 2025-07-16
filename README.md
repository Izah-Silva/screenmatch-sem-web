# 🎬 Screenmatch (versão sem web)

Projeto desenvolvido em Java que consome a API do OMDb (The Open Movie Database) para buscar informações sobre séries, como número de temporadas, episódios e avaliações do IMDb. Aplicação em modo console, com foco em prática de requisições HTTP, consumo de APIs e manipulação de dados com Java moderno.

---

## 💡 Funcionalidades

- Solicita ao usuário o nome de uma série via terminal;
- Busca informações gerais da série (título, total de temporadas, avaliação);
- Busca os dados de todas as temporadas da série, incluindo episódios;
- Exibe os dados estruturados em objetos Java.

---

## 🛠 Tecnologias e conceitos utilizados

- Java 17+ (usando `record`, `var`, etc.)
- Requisições HTTP via `HttpClient` (Java padrão);
- Conversão de JSON usando Gson;
- Programação orientada a objetos (POO);
- Boas práticas de estruturação de pacotes;
- API externa: [OMDb API](https://www.omdbapi.com/)

---

## 📁 Estrutura do Projeto

```bash
screenmatch-sem-web/
│
├── br.com.alura.screenmatch/
│   ├── principal/        # Classe Principal (menu e lógica de execução)
│   ├── model/            # Records para representar os dados da API
│   └── service/          # Lógica de requisição HTTP e conversão de JSON
