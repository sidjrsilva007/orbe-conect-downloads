# Orbe Conect para Windows

**Voz, tela e companhia.** Um aplicativo para pequenos grupos, criado por **Sidney Junio Silva**.

**[Baixar o instalador mais recente](https://github.com/sidjrsilva007/orbe-conect-downloads/releases/latest/download/OrbeConect-Setup.exe)** · **[Conhecer o aplicativo](https://orbe-conect.pages.dev/)** · **[Todas as versões](https://github.com/sidjrsilva007/orbe-conect-downloads/releases)**

## Instalar

1. Baixe `OrbeConect-Setup.exe`.
2. Abra o instalador e siga as etapas em português.
3. Inicie o Orbe Conect pelo atalho e entre na sua conta.

Requer Windows 10/11 de 64 bits. Não é preciso extrair ZIP ou instalar Node.js. O executável ainda não tem assinatura digital de editor.

## Novidades da versão 0.8.0

- Lembrar-me com sessão protegida pelo Windows no novo desktop, sem gravar a senha.
- Voz com tratamento configurável e teste local de quatro segundos.
- Áudio da tela separado das vozes, volume de até 200% e opção de ouvir somente a transmissão.

## Recursos

- Amigos por nome de usuário, solicitações com aceite e status online na mesma instalação do servidor.
- Comunidades privadas e convites individuais.
- Canais de texto com histórico e salas de voz para até dez pessoas.
- Compartilhamento de janela ou tela com áudio opcional no Windows.
- Microfone, som da chamada e áudio da transmissão com controles separados.
- Aviso de atualização dentro do aplicativo a partir da versão 0.3.0.

**Versão 0.7.0:** contas, comunidades, chat e sinalização usam Supabase e Cloudflare Pages. O computador do criador pode ficar desligado. Entre com seu usuário e senha e gere convites novos. O plano gratuito tem limites e pode pausar por inatividade. Chamadas em redes restritivas podem exigir TURN; a conectividade entre provedores diferentes ainda precisa ser validada.

## Atualizações do aplicativo

O Orbe Conect identifica novas versões dentro do aplicativo. Desde a 0.4.1, um ícone discreto de download aparece no topo. Clique para baixar, acompanhe a porcentagem e confirme **Abrir instalador**. O assistente mostra as etapas da atualização e permite abrir o Orbe ao concluir. Encerre a chamada antes de atualizar.

A opção **Verificar atualizações** também está disponível nas configurações. Quem utiliza a versão 0.2 precisa instalar o novo Setup.exe uma vez para habilitar o atualizador.

## Arquivos das versões

O download para uso normal é somente o **Setup.exe**. Os outros arquivos têm finalidade técnica:

| Arquivo | Finalidade |
| --- | --- |
| `OrbeConect-Setup.exe` | Instalador do aplicativo |
| `latest.yml` | Versão e checksum usados pelo atualizador |
| `OrbeConect-Setup.exe.blockmap` | Metadados para o download de atualização |
| `SHA256SUMS.txt` | Verificação manual da integridade do instalador |

Os arquivos automáticos de código-fonte que o GitHub apresenta nas releases correspondem a este repositório de informações de download. O código de desenvolvimento do aplicativo permanece em outro repositório, privado durante os testes.

Nenhum instalador inclui o banco, contas ou sessões da máquina de desenvolvimento. Preserve sua pasta de dados ao atualizar. Não envie senhas, sessões ou banco de dados em relatos de erro.

---

© 2026 **Sidney Junio Silva**, criador do Orbe Conect. Marca e identidade visual mantêm os créditos de autoria. Informações de licença acompanham o aplicativo.

Fechar no X mantém o Orbe Conect na área de notificação. Para encerrar, use **Sair** no menu do ícone. Salas com cinco ou mais participantes reduzem a tela para até 480p/15 fps para priorizar a voz. O desempenho depende do computador e da conexão; ainda não houve validação com dez pessoas em redes diferentes.

## Servidor compartilhado de testes
Na 0.7.0, o aplicativo se conecta ao mesmo endereço HTTPS para todos. O anfitrião precisa manter o computador ligado. Use o convite HTTPS, com usuário e senha individuais. A URL do túnel é temporária e pode mudar; o aplicativo consulta a configuração publicada no site. O túnel não equivale a hospedagem permanente.
