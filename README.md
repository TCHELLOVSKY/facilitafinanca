# Controle Financeiro — PWA

## Publicar no Netlify

1. Envie o conteúdo desta pasta para a raiz do repositório GitHub.
2. No Netlify, conecte o repositório. O arquivo `netlify.toml` configura a publicação da raiz; não é necessário comando de build.
3. Use o endereço HTTPS fornecido pelo Netlify. O service worker e a instalação precisam de HTTPS (ou `localhost`).
4. Abra o site no celular. Toque em **INSTALAR** quando o navegador oferecer a instalação. Se o navegador não abrir o aviso, use o menu dele e escolha **Instalar aplicativo** ou **Adicionar à tela inicial**.
5. No iPhone/iPad, abra no Safari, toque em **Compartilhar** e escolha **Adicionar à Tela de Início**.

Depois de instalado, abra pelo ícone adicionado à tela inicial. A tela inicial do PWA mostra **ENTRAR** e abre o controle financeiro dentro do app instalado. Os dados atuais são guardados no armazenamento local do navegador/dispositivo; não são sincronizados entre aparelhos.

O navegador controla quando oferece o aviso de instalação. O botão tenta abrir esse aviso quando disponível e mostra instruções específicas quando o navegador não oferece a API de instalação. O PWA não consegue forçar uma aba comum do site a trocar para o app instalado; para entrar na versão instalada, abra o ícone da tela inicial.
