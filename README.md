# Resumo para Prova 1 - Desenvolvimento Web 1

Este documento é um resumo dos principais conceitos de **Desenvolvimento Web 1**
(DW1) com foco na linguagem **HTML**. Ele foi criado para auxiliar nos estudos
para a **Prova 1**.

---

Os PDFs das aulas estão disponíveis na pasta [`/Aulas`](./Aulas).

---

**Autor:** Daniel Henrique Bellé

---

## Como clonar um repositório do GitHub

Para aprender como clonar um repositório do GitHub, assista ao vídeo no link
abaixo:

[Como clonar um repositório do GitHub](https://www.youtube.com/watch?v=5ctmK6fV1NQ)

---

## Como instalar, configurar e entender o GitHub

Para aprender como instalar, configurar e entender mais sobre o GitHub, assista
ao vídeo no link abaixo:

[Como instalar, configurar e entender o GitHub](https://youtu.be/VmkEZ9qEPDU)

---

## 1. Conceitos Básicos

- **WWW**: Sistema de informação com:

  - **URLs**: Localização dos recursos.
  - **HTTP**: Protocolo de comunicação.
  - **HTML**: Linguagem de marcação.

- **HTML**: Linguagem de marcação com **tags** no formato:

  ```html
  <tag>conteúdo</tag>
  ```

- **Estrutura Básica**:
  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>Título</title>
      <meta charset="UTF-8" />
    </head>
    <body>
      Conteúdo
    </body>
  </html>
  ```

---

## 2. Elementos HTML

| Elemento       | Descrição                         | Exemplo                           |
| -------------- | --------------------------------- | --------------------------------- |
| **Títulos**    | `<h1>` a `<h6>`                   | `<h1>Título</h1>`                 |
| **Parágrafos** | `<p>`                             | `<p>Texto</p>`                    |
| **Links**      | `<a href="url">`                  | `<a href="pagina.html">Link</a>`  |
| **Imagens**    | `<img src="img.jpg" alt="texto">` | `<img src="foto.jpg" alt="Foto">` |
| **Listas**     | `<ul>`, `<ol>`, `<li>`            | `<ul><li>Item</li></ul>`          |

---

## 3. Formulários

- **Estrutura**:
  ```html
  <form action="url" method="get|post"></form>
  ```

| Tipo         | Descrição                                                                | Exemplo                                                         |
| ------------ | ------------------------------------------------------------------------ | --------------------------------------------------------------- |
| **Texto**    | `<input type="text">`                                                    | `<input type="text" name="nome">`                               |
| **Senha**    | `<input type="password">`                                                | `<input type="password" name="senha">`                          |
| **Rádio**    | `<input type="radio">`                                                   | `<input type="radio" name="sexo" value="M">`                    |
| **Checkbox** | `<input type="checkbox">`                                                | `<input type="checkbox" name="opcao" value="1">`                |
| **Select**   | `<select>` com `<option>`                                                | `<select name="estado"><option value="RS">RS</option></select>` |
| **Textarea** | `<textarea>`                                                             | `<textarea name="msg" rows="4"></textarea>`                     |
| **Botões**   | `<input type="submit">`, `<input type="reset">`, `<input type="button">` | `<input type="submit" value="Enviar">`                          |

- **Atributos**: `name`, `value`, `placeholder`, `required`, `readonly`,
  `disabled`, `checked`, `selected`.

---

## 4. Tabelas

- **Exemplo**:

  ```html
  <table border="1">
    <tr>
      <th>Cabeçalho</th>
      <td>Dado</td>
    </tr>
  </table>
  ```

- **Atributos**:
  - `colspan`: Mesclar colunas.
  - `rowspan`: Mesclar linhas.

---

## 5. Multimídia

- **Vídeo**:

  ```html
  <video width="320" controls>
    <source src="video.mp4" type="video/mp4" />
  </video>
  ```

- **Áudio**:
  ```html
  <audio controls>
    <source src="audio.mp3" type="audio/mpeg" />
  </audio>
  ```

---

## 6. HTTP

- **Métodos**:

  - `GET`: Dados enviados na URL.
  - `POST`: Dados enviados no corpo da requisição.

- **Códigos de Status**:

  - `200`: OK.
  - `404`: Não encontrado.
  - `500`: Erro no servidor.

- **HTTPS**: Versão segura do HTTP com criptografia.

---

## 7. Navegação

- **Links**:
  - Mesma pasta: `<a href="pagina.html">`
  - Pasta abaixo: `<a href="pasta/pagina.html">`
  - Pasta acima: `<a href="../pagina.html">`
  - Raiz: `<a href="/pasta/pagina.html">`

---

## 8. Outros

- **Favicon**:

  ```html
  <link rel="icon" href="favicon.ico" />
  ```

- **iframe**:

  ```html
  <iframe src="url"></iframe>
  ```

- **Caracteres Especiais**:
  - `&nbsp;`: Espaço.
  - `&lt;`: `<`.
  - `&gt;`: `>`.

---

Este resumo cobre os principais tópicos de HTML necessários para a **Prova 1**
de Desenvolvimento Web 1. Bons estudos!
