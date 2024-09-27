
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

<h1>Configurando uma instância de Banco de Dados na Azure</h1>

Para configurar uma instância de banco de dados na Azure, incluindo a criação de uma máquina virtual e bancos de dados SQL, siga estas etapas:

1. Criar uma Máquina Virtual

Passo 1: Acessar o Portal do Azure
- Acesse o [Portal do Azure](https://portal.azure.com/).

Passo 2: Criar uma Nova Máquina Virtual
- No painel esquerdo, clique em "Criar um recurso".
- Selecione "Máquina Virtual".

Passo 3: Configurar a Máquina Virtual
- Assinatura: Escolha sua assinatura do Azure.
- Grupo de Recursos: Crie um novo grupo ou escolha um existente.
- Nome da Máquina Virtual: Dê um nome à sua VM.
- Região: Escolha a região onde deseja criar a VM.
- Imagem: Selecione a imagem desejada (ex: Windows Server, Ubuntu, etc.).
- Tamanho: Escolha o tamanho da VM com base em suas necessidades (CPU, memória).
- Configurações Administrativas: Defina o nome de usuário e a senha ou utilize autenticação com chave SSH.

Passo 4: Configurações de Rede
- Configure a rede virtual, sub-rede e regras de firewall. Certifique-se de permitir acesso ao banco de dados.

Passo 5: Revisar e Criar
- Revise suas configurações e clique em "Criar".

<h1>Criar Bancos de Dados SQL</h1>

Passo 1: Criar um Banco de Dados SQL
- No painel do Azure, clique em "Criar um recurso".
- Selecione "Banco de Dados SQL".

Passo 2: Configurar o Banco de Dados SQL
- Assinatura: Escolha sua assinatura do Azure.
- Grupo de Recursos: Escolha o grupo existente ou crie um novo.
- Nome do Banco de Dados: Dê um nome ao seu banco de dados.
- Servidor: Crie um novo servidor ou escolha um existente. Para criar um novo:
- Defina um nome do servidor.
- Escolha uma localização (região).
- Defina um nome de administrador e senha.

Passo 3: Configurações de Desempenho
- Escolha o nível de serviço e a camada de desempenho (DTUs ou vCores), dependendo da carga esperada.

Passo 4: Configurações de Backup
- Defina as opções de backup e retenção conforme necessário.

Passo 5: Revisar e Criar
- Revise suas configurações e clique em "Criar".


Dicas
- Segurança: Sempre utilize práticas de segurança recomendadas, como redes virtuais, grupos de segurança e autenticação forte.
- Custos: Monitore os custos associados à VM e ao banco de dados para evitar surpresas na fatura.

