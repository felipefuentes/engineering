# Engineering – Hub de Tecnologia

Este repositório contém a página HTML `hub-de-tecnologia.html`, um hub executivo de links e atalhos de tecnologia.

## Como executar localmente

Opções rápidas para visualizar a página durante o desenvolvimento:

1) Abrir diretamente no navegador
- Localize o arquivo `hub-de-tecnologia.html`
- Clique duas vezes para abrir no navegador padrão

2) Servidor HTTP simples (recomendado para evitar limitações de CORS)
- Com Python 3 instalado:
  ```bash
  cd engineering_repo
  python -m http.server 8000
  ```
  Acesse: http://localhost:8000/hub-de-tecnologia.html

- Com Node.js instalado:
  ```bash
  npx --yes serve -l 8000
  ```
  Acesse: http://localhost:8000/hub-de-tecnologia.html

## Estrutura
- `hub-de-tecnologia.html`: Página principal (HTML puro)

## Fluxo de contribuição
- Crie uma branch descritiva a partir de `main` (ex.: `feature/melhoria-atalhos`)
- Faça commits pequenos e claros
- Abra um Pull Request para revisão

## Próximos passos sugeridos
- Revisar acessibilidade (semântica, contraste, navegação por teclado)
- Otimizar performance (minificação, assets externos, pré-carregamento de fontes)
- Padronizar formatação (EditorConfig/Prettier) e CI simples para validação HTML
