> Para conhecimento de componentes, configuração e padrões do Mintlify, o skill já está instalado em `.agents/skills/mintlify`.

# Instruções do projeto de documentação — Mapa do Saber

## Sobre este projeto

- Site de documentação construído com [Mintlify](https://mintlify.com)
- Páginas são arquivos MDX com frontmatter YAML
- Configuração em `docs.json`
- `mint dev` para preview local
- `mint broken-links` para verificar links

## Terminologia (Mapa do Saber)

- **Admin** = painel administrativo Laravel (mapa-do-saber-admin) — uso interno, apenas administradores; não é foco da documentação pública
- **App** = aplicativo React/Vite (mapa-do-saber-app) — https://app.mapadosaber.com.br
- **Web** = site Next.js (mapa-do-saber-web) — https://www.mapadosaber.com.br
- Use "workspace" para o monorepo; "projeto" para admin/app/web individual
- Preferir "usuário" a "member" em português

## Preferências de estilo

- Voz ativa e segunda pessoa ("você")
- Frases concisas — uma ideia por frase
- Títulos em sentence case
- **Negrito** para elementos de UI: Clique em **Configurações**
- Formatação em código para nomes de arquivos, comandos, caminhos e referências
- Documentação em **português (pt-BR)**

## Limites de conteúdo

- Documentar APIs públicas, guias de uso e integração
- Não documentar rotinas internas de admin ou detalhes de implementação sensíveis
- Admin é acessado apenas por administradores — manter como conhecimento de regras, não destacar na doc
