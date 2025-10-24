# Portfólio - Caio Manfio

Este diretório contém o arquivo `index.html` do portfólio pessoal de Caio Manfio.

Resumo das alterações recentes

- Melhorias para modo escuro (contraste de texto, fundos e ícones).
- Padronização de badges de tecnologia com a classe `.tech-badge`.
- Consolidação do KorpuzBot no cartão em "Meus Projetos" com resumo do README.
- Inclusão de novo projeto: "Sites comerciais com IA integrado".
- Atualização das Soft Skills e Automação & Ferramentas (incluindo LLaMA 3).
- Integração de WhatsApp (link no bloco de telefone e botão flutuante) com mensagem predefinida.
- Remoção do formulário de contato — apenas opções de contato permanecem.

Como testar localmente

1. Abra um terminal na pasta do projeto.
2. Inicie um servidor estático (Python recomendado):

```powershell
cd "c:\Users\usuario\Nova pasta"; python -m http.server 8000
```

3. Abra no navegador: http://localhost:8000
4. Verifique:
   - Tema claro/escuro (clique no botão do cabeçalho).
   - Funcionamento dos ícones (feather icons carregados corretamente).
   - Clique no botão WhatsApp (FAB) e no link dentro da seção de contato — deve abrir WhatsApp Web no desktop ou o app no celular.
   - Verifique os cards em "Meus Projetos" para alinhamento das badges.

Notas técnicas

- O projeto utiliza Tailwind CSS via CDN e Feather Icons via CDN embutidos no `index.html`.
- Preferi ajustes inline no `index.html` para simplicidade; se quiser, podemos extrair estilos para um arquivo CSS separado.

Próximos passos sugeridos (opcionais)

- Substituir os ícones genéricos por SVGs oficiais (ex: logo do WhatsApp, LLaMA, HTML5).
- Adicionar eventos de analytics para cliques importantes (WhatsApp, visita a projetos).
- Revisar links de GitHub / LinkedIn quando estiverem disponíveis.

---

Se quiser que eu aplique alguma das melhorias opcionais agora, diga qual e eu faço em seguida.