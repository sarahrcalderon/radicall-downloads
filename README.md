# Radicall Beta para Windows

A Radicall é uma plataforma de comunicação com servidores, mensagens, canais de voz e compartilhamento de tela.

Este repositório é destinado exclusivamente à distribuição de instaladores e informações públicas de instalação. Não contém o código-fonte original da aplicação.

## Downloads

Consulte a seção Releases deste repositório. A versão inicial prevista é **0.1.0-beta.1**, para Windows x64, marcada como pré-lançamento. Os links só estarão disponíveis após publicação e verificação.

## Estado da Beta

Esta versão está em testes e pode apresentar problemas. Foi relatado timeout de login; o fluxo completo de autenticação ainda não foi homologado. Não há atualização automática habilitada.

O instalador ainda não possui assinatura digital. Podem ocorrer avisos legítimos do Windows SmartScreen. Não desative proteções nem contorne decisões de confiança; confirme a procedência com o responsável pela distribuição.

## Instalação e integridade

Baixe o instalador, SHA256SUMS.txt e README-INSTALACAO.md da mesma Release. Confira o hash antes de executar e siga as instruções. São necessários Windows x64, Microsoft Edge WebView2 e conexão à internet. A compatibilidade em Windows limpo continua em homologação.

Não são necessários Node.js, servidor de desenvolvimento ou acesso ao projeto. O cliente utiliza serviços remotos por HTTPS. O JavaScript e os assets incorporados podem ser analisados tecnicamente; minificação não impede engenharia reversa.

Para suporte, procure o responsável pelo convite. Nunca compartilhe senha, token de confirmação, token de sessão ou código MFA.
