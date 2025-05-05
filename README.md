Como Criar Máquinas Virtuais na Azure
Acesse o Portal Azure

Vá para: https://portal.azure.com

Criar uma Nova Máquina Virtual

Clique em “Criar um recurso” > “Computação” > “Máquina Virtual”.

Configurações Básicas

Escolha a assinatura e o grupo de recursos (crie um se necessário).

Defina o nome da VM, região, imagem do sistema operacional (Windows, Ubuntu, etc.).

Escolha o tamanho da VM (ex: B1s para testes, D-series para produção).

Usuário e Autenticação

Crie um usuário e senha, ou use chave SSH (recomendado para Linux).

Disco e Rede

Selecione o tipo de disco (HDD ou SSD).

Configure rede virtual, sub-rede, e se quer IP público.

Revisar e Criar

Revise todas as configurações e clique em “Criar”.

Como Usar a Máquina Virtual
Acesso via RDP (Windows):

Baixe o arquivo de conexão RDP pelo portal e use a senha cadastrada.

Acesso via SSH (Linux):

Use terminal ou Putty:
ssh usuario@IP-publico

Gerenciar via Azure Portal:

Iniciar, parar, reiniciar, redimensionar e monitorar a VM diretamente pelo portal.

Dicas para Melhor Uso das VMs na Azure
Escolha o tamanho certo

Evite pagar por recursos ociosos. Redimensione a VM conforme a necessidade.

Use Auto Shutdown

Configure desligamento automático fora do horário de uso para economizar.

Snapshots e Backup

Use snapshots e o Azure Backup para proteger seus dados e restaurar rapidamente.

Redes Seguras

Evite deixar portas como RDP e SSH abertas para o mundo. Use regras de NSG (firewall) ou bastion host.

Monitoramento

Habilite o Azure Monitor e Log Analytics para acompanhar desempenho e eventos.

Tags e Organização

Use tags (ex: projeto, ambiente, dono) para organizar e controlar custos.
