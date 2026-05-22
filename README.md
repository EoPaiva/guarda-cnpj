# Guarda-CNPJ — docs públicos

Esta pasta contém os arquivos HTML estáticos da política de privacidade,
termos de uso e landing pública.

## Como hospedar no GitHub Pages

1. Crie um repositório no GitHub (ex: `guarda-cnpj-site`).
2. Faça commit desta pasta `docs/` na branch principal.
3. Vá em **Settings → Pages**.
4. Em **Source**, selecione a branch principal e a pasta `/docs`.
5. Aguarde 1-2 minutos. O site fica em `https://<usuario>.github.io/<repo>/`.

## URLs que ficam disponíveis

- `/` → `index.html` (landing pública)
- `/privacy.html` → Política de Privacidade
- `/terms.html` → Termos de Uso
- `/non-affiliation.html` → Aviso de Não Afiliação

## URLs necessárias para Chrome Web Store

Quando submeter na Chrome Web Store, use:

- **Privacy Policy URL**: `https://<usuario>.github.io/<repo>/privacy.html`
- **Homepage URL**: `https://<usuario>.github.io/<repo>/`
- **Support URL**: `mailto:contato@guarda-cnpj.app` ou Issue Tracker do GitHub

## Domínio próprio (opcional)

Para usar `guarda-cnpj.app` ou similar:

1. Registre o domínio (Registro.br, Namecheap, Cloudflare).
2. Adicione arquivo `CNAME` em `docs/` com o domínio.
3. Configure DNS apontando para `<usuario>.github.io`.
4. Habilite HTTPS em **Settings → Pages**.
