# CashAI

Marketplace de plugins para o Claude com conhecimento sobre **como gerar renda no Brasil com marketing digital**: modelos de negócio, plataformas (Hotmart, Kiwify, marketplaces), tráfego pago e orgânico, precificação e métricas, MEI/Simples Nacional, LGPD, CDC e CONAR.

## Instalar no Claude (web/desktop)

1. Abra **Configurações → Plugins (ou Personalizar) → Adicionar → Adicionar marketplace**.
2. Cole o link do repositório: `https://github.com/dayssonrodrigues/cashai`
3. Instale o plugin **cashai**.
4. Pergunte, por exemplo: *"Tenho 10h por semana e R$ 500, como começo a ter renda com marketing digital?"*

> O repositório precisa estar **público** (ou sua conta GitHub precisa estar conectada ao Claude com acesso a ele).

## Instalar no Claude Code

```
/plugin marketplace add dayssonrodrigues/cashai
/plugin install cashai@cashai
```

## Estrutura

```
.claude-plugin/marketplace.json          # catálogo do marketplace
plugins/cashai/
  .claude-plugin/plugin.json             # manifesto do plugin
  skills/renda-marketing-digital-brasil/
    SKILL.md                             # instruções da skill
    references/                          # base de conhecimento
      modelos-de-negocio.md
      plataformas-e-pagamentos.md
      trafego-e-canais.md
      precificacao-e-metricas.md
      tributacao-e-formalizacao.md
      legislacao-e-compliance.md
```

## Aviso

Conteúdo educativo. Valores, taxas e regras tributárias mudam com frequência — confirme nas fontes oficiais e com um contador. Nenhuma estratégia garante ganhos.
