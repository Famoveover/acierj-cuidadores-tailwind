# ACIERJ - Associação de Cuidadores

Este projeto é o site institucional da Associação dos Cuidadores da Pessoa Idosa, da Saúde Mental e com Deficiência do Estado do RJ (ACIERJ).

## Sobre o Projeto

O site foi desenvolvido utilizando [Tailwind CSS](https://tailwindcss.com/) para estilização moderna e responsiva, com HTML puro e CSS customizado. Ele apresenta informações sobre a associação, serviços, eventos, benefícios para associados e formas de contato.

## Estrutura de Pastas

- `index.html` — Página inicial
- `sobre.html` — Quem somos
- `servicos.html` — Serviços oferecidos
- `eventos.html` — Eventos
- `associe-se.html` — Associe-se à ACIERJ
- `contato.html` — Contato
- `style.css` — Estilos customizados
- `src/input.css` — Arquivo de entrada do Tailwind CSS
- `dist/output.css` — CSS gerado pelo Tailwind para produção
- `acierj.png` — Logo da associação

## Como rodar o projeto

1. Instale o [Node.js](https://nodejs.org/) e o [npm](https://www.npmjs.com/).
2. Instale o Tailwind CSS localmente:
   ```powershell
   npm install -D tailwindcss
   npx tailwindcss init
   ```
3. Configure o arquivo `tailwind.config.js` conforme suas necessidades.
4. Compile o CSS:
   ```powershell
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```
5. Abra o arquivo `index.html` no navegador para visualizar o site.

## Personalização

- As cores, fontes e componentes podem ser ajustados nos arquivos `style.css` e `src/input.css`.
- Para adicionar novas páginas, crie arquivos `.html` e siga o padrão das páginas existentes.

## Créditos

Desenvolvido por ACIERJ — Associação dos Cuidadores do Estado do RJ.

## Licença

Este projeto é de uso institucional da ACIERJ. Para uso externo, consulte a diretoria da associação.
