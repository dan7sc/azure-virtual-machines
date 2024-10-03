# Azure Virtual Machines
## Service Level Agreements (SLA) para Serviços Online
* Possui métricas que variam de 99% a 99.999%
    * Quando mais preciso o valor (mais próximo de 100%) menos tempo de inatividade do serviço
## Máquinas virtuais
* É possível criar máquinas virtuais no Azure com o seguinte passo:
    * Todos os serviçoes > Máquinas virtuais > Criar uma máquina virtual
* Podemos especificar a zona de disponibilidade da máquina virtual
    * Zona de disponibilidade separa fisicamente os recursos em uma região do Azure
    * Até 3 zonas de disponibilidade
* Podemos especificar o conjunto de dimensionamento de máquinas virtuais
    * Distribuir as VMs entre zonas e domínios de falha em escala
* Podemos especificar o conjunto de disponibilidade
    * distribuir as VMs automaticamente entre vários domínios de falha
* Podemos criar conta de armazenamento
    * LRS (armazenamento com redundância local)
        1. Opção de custo mais baixo
        2. Proteção básica contra falhas de drive e de rack do servidor
        3. Recomendada para cenários não críticos
    * GRS (armazenamento com redundância geográfica)
        1. Opção intermediária
        2. Funcionalidades de failover em uma região secundária
        3. Recomendada para cenários de backup
    * ZRS (armazenamento com redundância geográfica)
        1. Opção intermediária
        2. Proteção contra falhas no nível do datacenter
        3. Recomendada para cenários de alta disponibilidade
    * GZRS (armazenamento com redundância de zona geográfica)
        1. Solução de proteção de dados ideal
        2. Recomendada para cenários de dados críticos
