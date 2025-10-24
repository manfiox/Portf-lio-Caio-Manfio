<<<<<<< HEAD
=======
```markdown
>>>>>>> b334b4c2935579c9aa639740b8c9705d86ed5a35
# Portfólio — Caio Manfio

Bem-vindo ao repositório do portfólio pessoal de Caio Manfio. Este projeto contém o arquivo `index.html` com a versão estática do site de apresentação, incluindo seção de projetos, contatos e informações pessoais.

## Preview
Abra o arquivo `index.html` no navegador ou rode um servidor local conforme instruções abaixo para testar todas as funcionalidades (especialmente o botão do WhatsApp e as mudanças de tema).

## Principais funcionalidades
- Tema claro/escuro com troca por botão no cabeçalho.
- Cards de projetos com badges de tecnologia (`.tech-badge`) padronizadas.
- Integração com WhatsApp (link no bloco de telefone e botão flutuante com mensagem predefinida).
- Uso de Tailwind CSS via CDN e Feather Icons via CDN.
- Contato direto por links (formulário de contato removido intencionalmente).

## Resumo das alterações recentes
- Melhorias no modo escuro (contraste de texto, fundos e ícones).
- Padronização das badges de tecnologia com a classe `.tech-badge`.
- Consolidação do KorpuzBot no cartão em "Meus Projetos" com resumo do README.
- Inclusão de novo projeto: "Sites comerciais com IA integrado".
- Atualização das Soft Skills e seção de Automação & Ferramentas (incluindo LLaMA 3).
- Integração de WhatsApp (link no bloco de telefone e botão flutuante) com mensagem predefinida.
- Remoção do formulário de contato — permanecem apenas opções de contato via links.

## Tecnologias usadas
- HTML (estrutura)
- Tailwind CSS (via CDN)
- Feather Icons (via CDN)
- Pequenos trechos de JavaScript inline para comportamento de UI

## Como testar localmente

Recomendado: rode um servidor estático para evitar problemas com carregamento de recursos via CDN.

1) Abra um terminal na pasta do projeto (a pasta com `index.html`).

2) Inicie um servidor estático:

- Windows / PowerShell:
  ```powershell
  cd "c:\caminho\para\o\projeto"
<<<<<<< HEAD
  python -m http.server 8000
=======
  python -m http.server 8000
  ```

- macOS / Linux:
  ```bash
  cd "/caminho/para/o/projeto"
  python3 -m http.server 8000
  ```

3) Abra no navegador:
- http://localhost:8000

4) Checklist rápido de verificação:
- [ ] Alterne entre tema claro e escuro (clique no botão no cabeçalho).
- [ ] Verifique se os ícones (Feather Icons) aparecem corretamente.
- [ ] Clique no botão WhatsApp (FAB) ou no link de telefone — deve abrir WhatsApp Web no desktop ou o app no celular com mensagem predefinida.
- [ ] Confira os cards em "Meus Projetos" para alinhamento e exibição das badges.
- [ ] Verifique responsividade em diferentes larguras de tela.

## Notas técnicas
- A solução optou por ajustes inline no `index.html` por simplicidade. Se preferir, podemos extrair estilos e scripts para arquivos separados (`styles.css` / `scripts.js`).
- Tailwind é carregado via CDN — para um projeto em produção, considere construir CSS a partir do pipeline do Tailwind para reduzir tamanho.
- Ícones atuais são via Feather; recomenda-se substituir por SVGs oficiais para logos (WhatsApp, HTML5, etc.) quando desejar maior fidelidade visual.

## Sugestões / Próximos passos
- Extrair estilos inline para `styles.css` e scripts para `scripts.js`.
- Substituir ícones genéricos por SVGs oficiais (WhatsApp, LLaMA, HTML5).
- Adicionar analytics para eventos importantes (cliques em WhatsApp, visitas a projetos).
- Adicionar screenshots ou demo hospedado (GitHub Pages).
- Incluir um arquivo LICENSE (por exemplo MIT) caso queira tornar o conteúdo aberto com licença explícita.

## Como contribuir
1. Fork este repositório.
2. Crie uma branch com sua melhoria: `git checkout -b feature/minha-melhoria`.
3. Faça commits claros e testes locais.
4. Abra um Pull Request descrevendo a alteração.

Se preferir, posso abrir uma branch e um PR com o README atualizado por você — diga se quer que eu faça isso.

## Contato
- WhatsApp: (link integrado no site) — utilize o botão flutuante de WhatsApp no `index.html`.
- Para alterações no repositório e colaboração: abra uma issue ou PR.

---

Se quiser que eu aplique este README.md diretamente no repositório (criar branch + PR), me autorize que eu faço isso agora e digo os próximos passos.
```
>>>>>>> b334b4c2935579c9aa639740b8c9705d86ed5a35
