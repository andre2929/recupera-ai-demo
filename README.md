# RECUPERA.AI — Painel (demo pública)

Site estático de **demonstração** do painel RECUPERA.AI, hospedado no GitHub Pages para mostrar ao cliente (CDL Campo Grande).

🔗 **Ao vivo:** https://andre2929.github.io/recupera-ai-demo/

⚠️ **Dados 100% fictícios** (30 devedores de teste). Nenhuma pessoa ou cobrança real. O código do bot fica privado — aqui só vai a tela.

## Como atualizar a demo
No projeto principal (`recupera-ai/`):
```bash
npm run sim        # (opcional) roda a simulação pra atualizar as conversas
npm run site       # regera site/index.html com os dados atuais
cd site && git add -A && git commit -m "atualiza demo" && git push
```
O GitHub Pages republica sozinho em ~1 min.
