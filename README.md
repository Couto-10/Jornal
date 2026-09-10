# 📰 WebJornal

Um portal de notícias web leve, dinâmico e responsivo desenvolvido com HTML, CSS e JavaScript puro. O sistema permite a exibição de matérias, consulta de arquivos antigos e conta com um painel de administração local.

---

#  💡 Conceito Fundamental

Em vez de criar dezenas de arquivos HTML manuais a cada semana, o site utiliza templates dinâmicos reutilizáveis que leem o arquivo central data/edicoes.json.

# Teste Aqui: https://couto-10.github.io/Jornal/

---

##  🧠 Principais Aprendizados

### Manipulação Dinâmica do DOM com Vanilla JS:

* Consumo e renderização de dados estruturados em JSON (data/edicoes.json) diretamente nas páginas.

* Utilização de templates dinâmicos reutilizáveis, evitando a criação manual de dezenas de arquivos HTML estáticos.

### Arquitetura Client-Side Decoupled:

* Separação clara das responsabilidades entre Estrutura (.html), Estilo (/css), Comportamento (/js) e Dados (/data).

* Gerenciamento de rotas e navegação simples passando parâmetros via URL (por exemplo, IDs de matérias em materia.html).

## Gerenciamento de Estado e Formulários:

- Criação de um painel administrativo local (admin.html) para simular o cadastro e manipulação de novos conteúdos.

- Entendimento do ciclo de vida dos dados na aplicação web (leitura, escrita e persistência local).

## Estruturação e Navegação Web:

- Organização de fluxo entre diferentes telas (Início, Matéria, Arquivo, Sobre e Admin).

- Boas práticas de semântica HTML e construção de layout responsivo para leitura otimizada de matérias.

---

## 🚀 Funcionalidades

- **Página Inicial (`index.html`):** Exibição das principais notícias e destaques do dia.
- **Leitura de Matérias (`materia.html`):** Visualização detalhada de reportagens individuais.
- **Arquivo de Notícias (`arquivo.html`):** Histórico de publicações passadas para consulta.
- **Painel Administrativo (`admin.html`):** Interface para gerenciamento de matérias e conteúdos.
- **Página Sobre (`sobre.html`):** Informações sobre o portal e a equipe editorial.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação das páginas.
- **CSS3:** Estilização e layout responsivo (localizado em `/css`).
- **JavaScript (Vanilla):** Lógica de navegação e manipulação de dados (localizado em `/js`).
- **JSON / Data:** Armazenamento local das matérias e conteúdos (localizado em `/data`).

---

## 📁 Estrutura do Projeto

```text
Jornal/
├── css/             # Arquivos de estilização
├── data/            # Arquivos de dados (notícias/conteúdo em JSON)
├── js/              # Scripts e lógica da aplicação
├── admin.html       # Painel de administração
├── arquivo.html     # Página de histórico/arquivo
├── index.html       # Página principal
├── materia.html     # Página de exibição de matéria
├── sobre.html       # Página institucional
└── README.md        # Documentação do projeto
