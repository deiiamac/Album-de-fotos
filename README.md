# Álbum de Fotos

Este projeto é uma aplicação web em React que funciona como um álbum de fotos interativo. Ele exibe imagens aleatórias da API do Unsplash e permite buscar fotos por termo e categoria, além de abrir uma visualização ampliada ao clicar em uma imagem.

## Tecnologias utilizadas

- React
- Vite
- JavaScript
- Axios para requisições HTTP
- CSS para estilização
- API do Unsplash para busca e exibição de imagens

## O que o projeto faz

- Carrega fotos aleatórias ao abrir a aplicação
- Permite pesquisar fotos por palavras-chave
- Permite filtrar por categoria
- Exibe a foto selecionada em uma visualização ampliada

## Requisitos

- Node.js 18 ou superior
- npm ou yarn

## Como rodar localmente

1. Clone este repositório:

   ```bash
   git clone <url-do-repositorio>
   cd "Album de Fotos"
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Crie um arquivo `.env` na raiz do projeto e adicione sua chave da API do Unsplash:

   ```env
   VITE_UNSPLASH_API_KEY=sua_chave_aqui
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Acesse a aplicação no navegador:
   ```text
   http://localhost:5173
   ```

## Build para produção

Para gerar a versão otimizada para produção, execute:

```bash
npm run build
```
