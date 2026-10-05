# SOLTURI · Campanhas 2026

Painel das campanhas **Bateu Levou** (mensal) e **High Ticket** (semestral).
Arquivo único e estático: todos os dados já estão dentro do `index.html`.

## Publicar no GitHub Pages (primeira vez)

1. Entre em https://github.com e clique em **New repository**.
2. Dê um nome (ex.: `solturi-campanhas`) e crie o repositório.
3. Na página do repositório, clique em **Add file → Upload files**.
4. Arraste os arquivos desta pasta: `index.html`, `README.md` e `.nojekyll`.
   (No Mac, o `.nojekyll` fica oculto: pressione Cmd + Shift + . para mostrá-lo.
   Se não conseguir enviá-lo, tudo bem — o painel funciona sem ele.)
5. Clique em **Commit changes**.
6. Vá em **Settings → Pages**.
7. Em *Build and deployment*, escolha **Source: Deploy from a branch**,
   **Branch: main** e pasta **/ (root)**. Clique em **Save**.
8. Aguarde 1 a 2 minutos e recarregue a página. O link aparece no topo, no formato:
   `https://SEU-USUARIO.github.io/solturi-campanhas/`

Esse é o link para enviar ao time comercial.

## Atualizar os dados

1. Gere o novo `index.html` (novo export de vendas).
2. No repositório, clique em **Add file → Upload files** e envie o novo `index.html`.
   Ele substitui o anterior.
3. Clique em **Commit changes**. Em 1 ou 2 minutos o link já mostra os dados novos
   (se não aparecer, recarregue com Ctrl + F5 / Cmd + Shift + R).

O link não muda entre atualizações.

## Privacidade

O painel contém nomes de representantes e valores de faturamento.
Em contas gratuitas do GitHub, o Pages só funciona com repositório **público**:
qualquer pessoa com o link consegue abrir a página, e o conteúdo do repositório
fica visível no GitHub. A página está marcada para não ser indexada pelo Google,
mas isso não é uma proteção de acesso.
