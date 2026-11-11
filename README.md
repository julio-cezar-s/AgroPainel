# AgroPainel

Painel de ferramentas para agropecuária (custos, produção e pecuária). Site de um único arquivo HTML, sem instalação e sem dependências externas.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `AgroPainel.html` | O site completo (todas as ferramentas). É o único arquivo que contém o app. |
| `index.html` | Página mínima que redireciona para `AgroPainel.html`, para o endereço principal do site funcionar. |
| `.nojekyll` | Arquivo vazio que diz ao GitHub Pages para publicar os arquivos como estão. |
| `README.md` | Este texto. |

## Atualizar o site depois

Abra o repositório, clique em **Add file → Upload files**, envie o novo `AgroPainel.html` com o mesmo nome (ele substitui o antigo) e clique em **Commit changes**. Em 1 a 3 minutos o site é atualizado.

## Observações

- Os cálculos salvos ficam no navegador de cada pessoa (IndexedDB), não no GitHub. Use **Dados e Backup** dentro do app para exportar e importar.
- Trocar o endereço do site (ou abrir em outro navegador) começa com o histórico vazio; importe o backup para recuperar.
- As ferramentas são auxiliares de cálculo e não substituem a orientação de um técnico.
