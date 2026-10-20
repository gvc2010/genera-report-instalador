# Genera Report

**Automate. Extract. Deliver.**

Extraia os relatórios dos sistemas de gestão das suas empresas (Bling, Omie, Tiny,
Conta Azul, Sienge, Asaas, Kiwify, Shopify, Nuvemshop e outros) direto para o Excel,
de um ou vários clientes, na hora ou agendado.

## Baixar

**[⬇ Baixar o Genera Report (Windows)](https://github.com/gvc2010/genera-report-instalador/releases/latest/download/Genera_Report_Setup.exe)**

O link sempre baixa a versão mais recente. Funciona no Windows 10 e 11 (64 bits),
inclusive em servidor acessado por área de trabalho remota (RDP).

## Instalar

1. Abra o arquivo `Genera_Report_Setup.exe` que foi baixado.
2. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em
   **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece
   porque o instalador ainda não tem certificado digital; o arquivo é o publicado aqui.
3. Siga o instalador até o fim. O Genera Report abre sozinho.

Não precisa de senha de administrador: o app instala só para o seu usuário do Windows.
Cada pessoa instala no próprio usuário.

## Primeiro uso

**Trabalhando sozinho:** abra a aba **Clientes**, cadastre o cliente, escolha o sistema,
informe o acesso e clique em **Conectar** (ou **Testar conexão**). Depois é só extrair.

**Em equipe:** várias pessoas usam os mesmos clientes, cada uma com o próprio usuário e
senha, sem recadastrar. Tudo fica criptografado numa pasta que a equipe acessa (no
servidor ou na rede).

- **Quem administra:** **Configurações → Equipe → Criar equipe**, escolha a pasta e,
  em **Pessoas da equipe**, cadastre cada pessoa com uma senha provisória. Use
  **Salvar convite...** para gerar um arquivo `.grconvite` com a pasta e o usuário.
- **Quem entra:** **Configurações → Equipe → Entrar numa equipe**, clique em
  **Abrir convite...**, digite o usuário e a senha provisória e crie a sua senha.
  Os clientes aparecem já conectados.

> O computador precisa acessar a pasta da equipe. Se aparecer "sem acesso à pasta da
> equipe", confira a rede ou a VPN: o app continua com a última cópia e envia as
> alterações quando a pasta voltar.

Também dá para levar clientes de um computador para outro num arquivo `.grclientes`
com senha: **Clientes → Exportar...** e **Importar...**.

## No dia a dia

- **Extrações:** escolha o cliente (ou vários), marque os relatórios, o período e
  clique em **Extrair**. Um cliente pode ter mais de um sistema.
- **Agendamentos:** extrações automáticas no horário marcado. Em equipe, o
  **agendador do servidor** roda os agendamentos mesmo sem ninguém conectado e os
  arquivos caem na pasta de cada cliente (um administrador do Windows ativa uma vez em
  Configurações → Equipe).
- **Base acumulada:** opção no cadastro do cliente que junta todos os períodos num CSV
  por relatório, pronto para o Power BI.
- **Saúde dos clientes:** conexões vencidas, falhas e pastas com problema num lugar só.

## Dúvidas comuns

- **Esqueci minha senha da equipe:** peça ao administrador **Redefinir senha** em
  Pessoas da equipe; você entra com a provisória e cria outra.
- **O app pediu para "Entrar de novo":** sua senha foi trocada em outro computador.
  Entre com a senha nova em Configurações → Equipe.
- **"Reconectar" num cliente:** a autorização daquele sistema venceu. Abra o cliente
  na aba Clientes e clique em Conectar.
- **Alguém saiu da equipe:** o administrador remove a pessoa; a senha dela deixa de
  abrir os clientes e ninguém mais precisa trocar nada.

## Atualizações

O próprio app avisa quando sai uma versão nova: clique em **Atualizar agora**.
Não é preciso baixar de novo por aqui.

Versões anteriores e o que mudou em cada uma: [Releases](https://github.com/gvc2010/genera-report-instalador/releases).
