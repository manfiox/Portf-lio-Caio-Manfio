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
  python -m http.server 8000