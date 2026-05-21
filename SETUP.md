# Briefing Davvero — Configuração

## Preview local

```bash
cd /Users/getuliolima/Desktop/Davvero
python3 -m http.server 9876
```

Abra: http://localhost:9876/index.html

## E-mail (Formspree)

1. Crie um formulário em [formspree.io](https://formspree.io)
2. Em `index.html`, substitua `YOUR_FORM_ID`:

```html
action="https://formspree.io/f/SEU_ID_AQUI"
```

3. Envie um teste e confirme o e-mail no painel Formspree.

## Assets

| Arquivo | Uso |
|---------|-----|
| `assets/logo.svg` | Logo Raipp no hero |
| `assets/Rodapé-Desk.svg` | Rodapé ≥ 768px |
| `assets/Rodapé-Mobile.svg` | Rodapé &lt; 768px |

## Publicar

Netlify Drop, Vercel ou Cloudflare Pages — pasta estática com `index.html` e `assets/`.
