# 🚗 Lafastreet | Concessionária

Landing page de uma concessionária de veículos desenvolvida com **HTML, CSS e JavaScript puro**, apresentando uma interface moderna e responsiva para divulgação de veículos.

> Projeto desenvolvido para fins **educacionais e demonstrativos de desenvolvimento web**.

---

## 📸 Sobre o projeto

A **Lafastreet** é uma concessionária fictícia criada para demonstrar conceitos fundamentais de desenvolvimento front-end.

O projeto apresenta uma página única com:

* Menu de navegação.
* Seção principal (Hero).
* Catálogo de veículos.
* Filtros por categoria.
* Cards de veículos.
* Seção institucional.
* Formulário de contato.
* Layout responsivo para dispositivos móveis.

---

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando apenas tecnologias nativas da web:

* **HTML5** — estrutura da página.
* **CSS3** — estilização, layout e responsividade.
* **JavaScript** — filtros de veículos e interação com o formulário.
* **Unsplash** — imagens utilizadas nos veículos e no banner principal.

Não foram utilizados frameworks ou bibliotecas externas de JavaScript.

---

## ✨ Funcionalidades

### 🏠 Página inicial

A seção inicial apresenta:

* Nome da concessionária.
* Chamada principal.
* Descrição da empresa.
* Botão para acessar o estoque.

### 🚘 Estoque de veículos

O catálogo apresenta diferentes veículos com:

* Nome.
* Ano.
* Tipo de câmbio.
* Quilometragem.
* Preço.
* Imagem.

Atualmente, o projeto possui seis veículos demonstrativos:

| Veículo       | Categoria |  Ano |
| ------------- | --------- | ---: |
| Range Rover   | SUV       | 2024 |
| Mercedes-Benz | Sedan     | 2023 |
| Porsche 911   | Esportivo | 2022 |
| Volvo XC60    | SUV       | 2024 |
| Audi A4       | Sedan     | 2024 |
| Ford Mustang  | Esportivo | 2023 |

---

### 🔎 Filtro de veículos

É possível filtrar os veículos por categoria:

* **Todos**
* **SUV**
* **Sedan**
* **Esportivo**

O filtro é realizado diretamente no navegador utilizando JavaScript.

---

### 📱 Design responsivo

A interface possui adaptação para dispositivos menores.

Em telas com largura inferior a `800px`:

* O menu de navegação é ocultado.
* O título principal é reduzido.
* Os veículos passam de três colunas para uma coluna.

---

### 📩 Formulário de contato

O formulário permite que o usuário informe:

* Nome.
* E-mail.
* Mensagem.

Atualmente, o formulário funciona apenas como uma demonstração de front-end.

Após o envio, uma mensagem de confirmação é exibida na página e os campos são limpos.

> **Observação:** nenhuma mensagem é realmente enviada para um servidor ou e-mail.

---

## 🎨 Identidade visual

A interface utiliza uma estética escura com destaque em verde-limão.

### Principais cores

| Cor          | Código    | Utilização                 |
| ------------ | --------- | -------------------------- |
| Verde-limão  | `#dfff00` | Destaques, botões e preços |
| Preto        | `#101010` | Fundo principal            |
| Cinza escuro | `#181818` | Header e seções            |
| Cinza        | `#999999` | Textos secundários         |
| Branco       | `#FFFFFF` | Textos principais          |

---

## 📁 Estrutura do projeto

A estrutura básica do projeto é:

```text
lafastreet/
│
├── index.html
└── README.md
```

Todo o HTML, CSS e JavaScript estão atualmente concentrados no arquivo `index.html`.

---

## 🚀 Como executar

Como o projeto utiliza apenas HTML, CSS e JavaScript puro, não é necessário instalar dependências.

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/lafastreet.git
```

### 2. Entre na pasta

```bash
cd lafastreet
```

### 3. Abra o projeto

Abra o arquivo:

```text
index.html
```

Você também pode utilizar uma extensão como **Live Server** no Visual Studio Code para executar o projeto em um servidor local.

---

## 🌐 Demonstração

Caso o projeto seja publicado utilizando GitHub Pages, ele poderá ser acessado através de:

```text
https://seu-usuario.github.io/lafastreet/
```

Substitua `seu-usuario` pelo seu nome de usuário do GitHub.

---

## 🧠 Conceitos demonstrados

Este projeto foi desenvolvido para demonstrar conhecimentos em:

* Estrutura semântica com HTML5.
* CSS Flexbox.
* CSS Grid.
* Responsividade.
* Media Queries.
* Manipulação do DOM.
* Eventos JavaScript.
* Funções JavaScript.
* `querySelectorAll()`.
* `dataset`.
* Manipulação de classes CSS.
* Formulários HTML.
* Validação básica com HTML.
* `addEventListener()`.
* Interação entre HTML, CSS e JavaScript.

---

## 🔮 Possíveis melhorias

O projeto pode ser expandido futuramente com funcionalidades como:

* [ ] Sistema de busca de veículos.
* [ ] Mais filtros por preço, marca e ano.
* [ ] Página individual para cada veículo.
* [ ] Galeria de imagens dos veículos.
* [ ] Sistema de financiamento.
* [ ] Simulador de parcelas.
* [ ] Integração com WhatsApp.
* [ ] Envio real do formulário de contato.
* [ ] Painel administrativo.
* [ ] Banco de dados para o estoque.
* [ ] Sistema de cadastro de veículos.
* [ ] Login para administradores.
* [ ] API para gerenciamento do estoque.
* [ ] Integração com sistema de CRM.

---

## ⚠️ Observações

A **Lafastreet é uma concessionária fictícia** criada exclusivamente para fins educacionais e demonstrativos.

Os veículos, preços, informações e imagens apresentados no projeto são utilizados apenas como conteúdo de demonstração.

As imagens são carregadas externamente através do **Unsplash**, portanto é necessária uma conexão com a internet para carregá-las.

---

## 👨‍💻 Autor

Desenvolvido por **Gabriel Antonio Duarte Sales**.

Projeto desenvolvido como demonstração de desenvolvimento web utilizando tecnologias front-end nativas.

---

## 📄 Licença

Este projeto pode ser utilizado para fins de estudo e aprendizado.

Caso você reutilize ou modifique o projeto, recomenda-se manter os créditos do autor original.
