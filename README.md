# 🎬 ScreenMatch (sem interface web)

Projeto desenvolvido como parte dos estudos em Java, com foco em lógica de programação orientada a objetos, manipulação de dados e boas práticas de desenvolvimento backend.

## 📌 Sobre o Projeto

O **ScreenMatch** é uma aplicação Java que simula um catálogo de filmes, séries e títulos de streaming, permitindo:

- Cadastro e exibição de filmes
- Avaliações com cálculo de média
- Categorização entre títulos e séries
- Cálculo de tempo total de exibição
- Recomendações com base em critérios internos

Apesar do nome, este projeto **não possui interface gráfica** ou web (versão CLI — linha de comando). Seu objetivo é exercitar conceitos fundamentais de backend em Java.

---

## 🛠️ Tecnologias e Conceitos Utilizados

- **Java 17** (ou versão equivalente)
- Programação Orientada a Objetos (POO)
- Tratamento de exceções
- Polimorfismo, herança e interfaces
- Estruturas de controle e coleções (`ArrayList`)
- Boas práticas de organização em pacotes

---

## 📁 Estrutura de Pastas

```
screenmatch-sem-web/
│
├── model/                 → Classes que representam os modelos de negócio (Filme, Serie, Titulo)
├── calculos/              → Lógica de recomendações e totalizador de tempo
├── principal/             → Classe com método main (ponto de entrada da aplicação)
└── README.md              → Documentação do projeto
```

---

## 🚀 Como Executar Localmente

### Pré-requisitos

- Java JDK instalado (versão 17 ou superior)
- Editor como IntelliJ, Eclipse ou VSCode com suporte a Java

### Passos

1. Clone este repositório:
   ```bash
   git clone https://github.com/Izah-Silva/screenmatch-sem-web.git
   cd screenmatch-sem-web
   ```

2. Abra o projeto no seu IDE Java preferido.

3. Localize a classe com o método `main` (geralmente em `Principal.java` ou similar).

4. Execute o projeto. A saída será exibida no console com as informações dos filmes, recomendações e tempo total.

---

## 📊 Exemplo de Saída

```
Filme: O Senhor dos Anéis
Ano: 2001
Duração: 178 minutos
Avaliações: ⭐⭐⭐⭐☆

Série: Breaking Bad (5 temporadas)
Tempo total estimado: 3000 minutos

Recomendado? ✔️
```

---

## ✅ Funcionalidades Desenvolvidas

- [x] Cadastro de filmes e séries
- [x] Cálculo da média de avaliações
- [x] Validação de dados
- [x] Interface `Recomendavel` com lógica de recomendação
- [x] Totalizador de tempo de exibição
- [ ] Testes automatizados (em breve!)

---

## 🧪 Testes

> Testes automatizados ainda não foram implementados.  
> Como próximo passo, pretendo incluir testes com **JUnit** para garantir a estabilidade das funcionalidades principais.

---

## 📈 Melhorias Futuras


- [ ] Testes unitários com JUnit
- [ ] Interface web com Spring Boot e Thymeleaf
- [ ] Armazenamento em banco de dados

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙋‍♀️ Sobre a Autora

Desenvolvido por **Izabela da Silva Pereira Vieira**, engenheira de software em formação com foco em backend, apaixonada por tecnologia, dados e boas práticas de código limpo.

📫 Entre em contato comigo pelo [LinkedIn](https://www.linkedin.com/in/izabela-vieira/) ou veja outros projetos no [GitHub](https://github.com/Izah-Silva).

---
