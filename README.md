# Central D12 — downloads

Instaladores oficiais para atualizar manualmente o aplicativo da Central D12. O download é público; o acesso aos dados da Central exige login.

## Versão atual

Desktop **0.2.3**, com a Central **1.113.0** incluída.

- [Mac com chip Apple (M1, M2, M3, M4 e posteriores)](https://github.com/Grupo-D12/central-d12-downloads/releases/download/desktop-v0.2.3/Central-D12-0.2.3-mac-arm64.dmg)
- [Mac Intel](https://github.com/Grupo-D12/central-d12-downloads/releases/download/desktop-v0.2.3/Central-D12-0.2.3-mac-x64.dmg)
- [Windows 64 bits (Intel/AMD)](https://github.com/Grupo-D12/central-d12-downloads/releases/download/desktop-v0.2.3/Central-D12-0.2.3-x64-setup.exe)
- [Arquivos da versão e verificação SHA-256](https://github.com/Grupo-D12/central-d12-downloads/releases/tag/desktop-v0.2.3)

## Como atualizar

1. Feche a Central D12 instalada.
2. No Mac, abra o DMG e arraste **Central D12** para **Aplicativos**, substituindo a versão anterior. Requer macOS 13 ou posterior.
3. No Windows, execute o instalador e mantenha o mesmo local da instalação anterior. Requer Windows 10 ou posterior, em 64 bits.
4. Abra o aplicativo atualizado e entre com sua conta, se solicitado. Não apague os dados do aplicativo para atualizar.

Estes pacotes não têm certificado comercial: o Mac usa assinatura ad-hoc, sem notarização; o Windows não tem assinatura Authenticode. O sistema pode mostrar um aviso ou exigir aprovação manual. Em computadores administrados pela empresa, uma política do sistema pode impedir a instalação. A Central também está disponível em [central.grupod12.com](https://central.grupod12.com).

Este repositório contém somente distribuição e empacotamento do cliente. O repositório da plataforma e os dados da operação permanecem privados. Não há atualização automática ou instalação silenciosa nos computadores dos usuários.

## Empacotamento Windows

O workflow manual usa um executor Windows padrão do GitHub Actions neste repositório público. Ele recebe apenas o aplicativo Mac já empacotado e a configuração pública de empacotamento, confere SHA-256, gera o instalador Windows e o envia para uma release em rascunho. Não acessa o código privado da plataforma nem usa credenciais de produção. Não usa armazenamento de artefatos ou cache do Actions.

O aplicativo inclui os avisos de licença das dependências distribuídas. A integração da Central D12 é proprietária do Grupo D12.
