# CPF SEGURO · Documento de Produto (editável)

Documento interno do CPF Seguro com edição inline + exportação PDF/HTML.

**URL pública (GitHub Pages):** https://hunterms.github.io/pdf-tier/

## Como usar

1. Abre a URL acima no navegador (Chrome ou Safari recomendado)
2. Clica em **✏️ Editar** no toolbar
3. Clica em qualquer texto pra editar inline
4. Auto-save no navegador (localStorage)
5. **⬇ Baixar PDF** quando quiser exportar
6. **💾 HTML** pra baixar a versão editada como arquivo

## Botões do toolbar

| Botão | Ação |
|---|---|
| Fechar | Fecha a aba |
| ⬇ Baixar PDF | PDF idêntico ao que tá na tela (preserva gradientes/cores) |
| 🖨 Imprimir | Print do navegador (alternativa) |
| ✏️ Editar | Liga/desliga modo edição inline |
| 💾 HTML | Baixa HTML com edições aplicadas |
| ↺ Resetar | Volta ao original (apaga edições do localStorage) |

## Importante

**Edições ficam salvas no localStorage do navegador que você está usando.** Se trocar de navegador ou device, as edições não vão junto. Pra sincronização entre dispositivos, precisa de backend (não implementado).

## Stack

- HTML/CSS/JS puro
- SF Pro Rounded font embedded (WOFF2 base64)
- html2pdf.js (via CDN) pra exportação PDF
- localStorage pra persistência de edições

## Conteúdo

5 páginas:
1. Capa
2. Visão geral · 3 fases
3. Sou eu! · autenticação universal
4. CPF Seguro · pausar e reativar
5. Pessoa de confiança · delegação humana segura

---

Equipe de Produto · Maio 2026 · v3
