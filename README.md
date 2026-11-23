# CashAI

Marketplace de plugins para o Claude com conhecimento para **quem quer fazer renda extra pela internet no Brasil** com marketing digital: caminhos para começar, plataformas (Hotmart, Kiwify, marketplaces), tráfego pago e orgânico, quanto cobrar, métricas e como evitar golpes.

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
      legislacao-e-compliance.md
```

## Aviso

Conteúdo educativo. Valores e taxas mudam com frequência — confirme nas plataformas e fontes oficiais. Nenhuma estratégia garante ganhos.
