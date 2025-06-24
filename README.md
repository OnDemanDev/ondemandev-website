# 🌐 OnDemandDev Frontend

> **Status:** ✅ Deploy automático funcionando via GitHub Actions + K3s API

Site institucional da OnDemandDev com deploy automático e analytics integrado.

## � Deploy Automático

Este repositório está configurado para **deploy automático** sempre que houver push na branch `main`.

### Como funciona:
1. **Push** → GitHub Actions ativa
2. **Validação** do HTML e código Umami
3. **Deploy** via K3s API (sem SSH)
4. **Atualização** automática do site

## ✨ Características

- ✅ **HTML Estático**: Sem dependências, carregamento rápido
- ✅ **Responsivo**: Design adaptável para todos os dispositivos  
- ✅ **Analytics Integrado**: Umami Analytics para tracking de visitantes
- ✅ **LGPD/GDPR Compliant**: Sem cookies, respeitando privacidade
- ✅ **SEO Otimizado**: Meta tags e estrutura semântica
- ✅ **Deploy Automático**: GitHub Actions + K3s API


## 🔧 Desenvolvimento

### Editar Conteúdo
1. Edite o arquivo `ondemand-dev-site.html`
2. Faça commit e push
3. Execute deploy manual no servidor

### Adicionar Tracking Events
```html
<!-- Exemplo de evento customizado -->
<button onclick="umami.track('contact-click')">
  Entre em Contato
</button>
```

## 🌐 URLs

- **Site Principal**: https://ondemandev.com.br
- **Analytics Dashboard**: https://analytics.ondemandev.com.br
- **Repositório**: https://github.com/LucasFeuser/ondemandev-frontend


