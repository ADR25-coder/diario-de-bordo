# Diário de Bordo — Relatório do Motorista

App de relatório de plantão: rotas, passageiros salvos, KM automático, checklist, mensagem para WhatsApp e relatório em Excel.

## Baixar o APK (Android)
Vá em **Releases** (lado direito da página do repositório) e baixe `DiarioDeBordo.apk` pelo celular.
A cada alteração enviada para `main`, um APK novo é gerado automaticamente.

## Versão web (opcional)
Ative em *Settings → Pages → Branch: `gh-pages`*. O app fica em `https://<usuario>.github.io/diario-de-bordo/` e pode ser instalado pelo navegador.

## Estrutura
- `www/` — o app (HTML único, funciona offline)
- `assets/logo.png` — ícone usado para gerar os ícones Android
- `.github/workflows/apk.yml` — compila o APK e publica
