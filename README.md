# 🔎 Site de Pesquisa

Um projeto simples e funcional desenvolvido com **HTML**, **CSS** e **JavaScript**, que permite pesquisar informações em uma base de dados local (`dados.js`).  
Além disso, conta com um **modo claro/escuro** interativo que altera o tema do site dinamicamente.

---
## 🖱 Acesse o Projeto

🚀 O projeto está disponível online!  
Você pode acessá-lo clicando no link abaixo:

👉 **[Site de Pesquisa](https://site-pesquisa-lake.vercel.app/)**  

*(Hospedado via [Vercel](https://vercel.com) – deploy automático e gratuito)*

---

## 🛠 Funcionalidades

- 🔎 **Pesquisa dinâmica:** filtra e exibe resultados com base em palavras-chave digitadas pelo usuário.  
- 🌙 **Alternância de tema:** botão para trocar entre modo claro e modo escuro.  
- 📜 **Resultados dinâmicos:** os resultados são renderizados diretamente no HTML via JavaScript.  
- 📱 **Design responsivo:** layout adaptável a celulares, tablets e desktops.  

---

## 📁 Estrutura do Projeto

```
.
├── index.html        # Estrutura principal da página
├── styles.css        # Estilos e temas (claro/escuro)
├── app.js            # Lógica da pesquisa e alternância de tema
└── dados.js          # Base de dados local usada na busca

```

---

## ⚙️ Como Usar

Siga as etapas abaixo para executar o projeto localmente:

**1. Baixe ou clone o repositório:**
   ```bash
   git clone https://github.com/grazidibf/site-pesquisa.git
   ```
**2. Abra o arquivo principal**:

   * Localize o arquivo `index.html` na pasta do projeto.

   * Clique duas vezes sobre ele ou abra diretamente pelo navegador de sua preferência.

   > 💡 *Dica:* não é necessário configurar servidor — o projeto roda totalmente no navegador.

**3. Utilize a ferramenta de pesquisa:**

   * Digite um termo no campo de busca.
   * Clique em **Pesquisar** para visualizar os resultados correspondentes.

**4. Experimente os temas:**

   * Clique no botão 🌙 para ativar o modo escuro.
   * Clique novamente (☀️) para voltar ao modo claro.



## 🔧 Tecnologias Utilizadas

* **HTML5** – Estrutura do site
* **CSS3** – Estilização e responsividade
* **JavaScript** – Lógica da aplicação e interação com o usuário
* **Google Fonts (Chakra Petch)** – Tipografia moderna e legível

---

## ✍ Exemplo de Uso

```
Pesquisar: "rápida"
→ Resultado: "Pesquisa Rápida" com link e descrição explicativa
```

---

## 📝 Explicação dos Principais Arquivos

### `dados.js`

Contém uma lista de objetos JavaScript representando as categorias de pesquisa.
Cada objeto possui:

* `titulo` → Nome do tipo de pesquisa
* `descricao` → Explicação detalhada
* `link` → Fonte de referência
* `tags` → Palavras-chave relacionadas

### `app.js`

* Captura o texto digitado no campo de busca.
* Converte o texto e os dados para **minúsculas** para busca insensível a maiúsculas/minúsculas.
* Filtra os resultados e exibe na seção `#resultados-pesquisa`.
* Implementa o **modo escuro/claro** com troca de ícone 🌙/☀️.

### `styles.css`

Define variáveis de cor no `:root` e ajusta os temas com classes `.light-theme` e `.dark-theme`.
Inclui ainda ajustes de **responsividade** com media queries.

---

## 💡 Possíveis Melhorias Futuras

* Adicionar **busca em tempo real** (sem precisar clicar em "Pesquisar").
* Customizar o conteúdo do site.
* Permitir **adicionar novos dados** dinamicamente.
* Salvar a preferência de tema no **localStorage**.
---

## 🖊 Autoria

Desenvolvido por **Graziella B. Fonseca**

✉ Contato: [grazi.dibf@gmail.com](mailto:grazi.dibf@gmail.com)

---

## 📜 Licença

Este projeto está licenciado sob os termos da **[Licença MIT](LICENSE)**.
