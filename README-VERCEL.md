# Borracharia Central — pacote Vercel

Este pacote é um site estático multipágina, sem Manus Auth, backend ou dependência de runtime Manus.

## Deploy pela interface da Vercel

1. Extraia o ZIP.
2. No painel da Vercel, importe a pasta extraída ou envie o repositório.
3. Selecione **Other** como framework/preset.
4. Deixe o **Build Command** vazio.
5. Deixe o **Output Directory** como `.`.
6. Clique em **Deploy**.

## Rotas

- `/` — Home
- `/servicos/` — Serviços
- `/sobre/` — Sobre
- `/contato/` — Contato

A localização fica em `/contato/#localizacao`, acessível pelo item **Localização** do menu. O mapa usa um Google Maps incorporado e interativo; WhatsApp, Instagram, Facebook e Google Maps continuam como links externos oficiais.

## Desenvolvimento local opcional

Na pasta extraída, qualquer servidor estático funciona. Exemplos:

```bash
python3 -m http.server 3000
```

ou:

```bash
npx serve .
```

Não é necessário configurar variáveis de ambiente, autenticação ou banco de dados.
