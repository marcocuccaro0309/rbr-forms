# RBR Onboarding Forms

Form HTML standalone per onboarding clienti e promozioni RBR. Submit diretto al webhook Make universale `RBR-Clienti` system.

## URLs live

- **Hub**: https://marcocuccaro0309.github.io/rbr-forms/
- **Nuovo cliente**: https://marcocuccaro0309.github.io/rbr-forms/onboard-cliente.html
- **Nuova promozione**: https://marcocuccaro0309.github.io/rbr-forms/onboard-promo.html

## Webhook target

Onboard cliente → `https://hook.eu1.make.com/2ibcw2eug488u7bs3d9hj47ota77tctr` → `rbr_clients` Data Store

Onboard promo → `https://hook.eu1.make.com/ccoosmjr8fm6hp3voxsddjrvdgzle88w` → `rbr_coupons` Data Store

## Aggiornare

```bash
cd /tmp/rbr-forms
# edit *.html
git add . && git commit -m "..." && git push
# GitHub Pages auto-rebuild in 1-2 min
```

Fonte: `/Users/marco/Desktop/AI/RBR AI/shared/forms/`
