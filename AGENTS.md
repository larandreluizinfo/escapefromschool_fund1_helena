# Instruções para agentes de IA

Este repositório é um projeto escolar publicado no GitHub Pages.

## Regra obrigatória: commitar e enviar (push) todas as alterações

Toda e qualquer alteração feita neste repositório **deve** ser:

1. **Versionada com Git** — todo arquivo criado, editado ou removido entra no commit.
2. **Commitada** — com uma mensagem curta e descritiva em português (ex.: `Ajusta tela inicial do jogo`).
3. **Enviada para o GitHub** (`git push`) na branch `main`.

Nunca finalize uma tarefa deixando alterações apenas no disco local (working tree sujo).
O fluxo padrão é sempre:

```bash
git add -A
git commit -m "Descrição curta da alteração"
git push origin main
```

Se o push falhar, resolva o problema (ex.: `git pull --rebase origin main`) e envie novamente
antes de considerar a tarefa concluída.

## Publicação

O site é publicado automaticamente pelo **GitHub Pages** a cada push na branch `main`.

- URL do site: https://larandreluizinfo.github.io/escapefromschool_fund1_helena/
- O arquivo de entrada é o `index.html` na raiz do repositório.
- Sempre que uma alteração for enviada, confirme que o Pages continua funcionando.

## Autores

Felipe, Ana Elisa e Anabela.

## Estilo

- Conteúdo e comentários em português.
- Código simples, legível e adequado para um projeto escolar.
