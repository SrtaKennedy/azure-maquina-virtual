# Criando Máquinas Virtuais na Azure

**Criação e Gerenciamento de Máquinas Virtuais no Microsoft Azure**

Este projeto foi desenvolvido no laboratório da Azure, com o objetivo de aplicar conhecimentos sobre infraestrutura como serviço (IaaS) criando e configurando máquinas virtuais (VMs) na plataforma Microsoft Azure.

### O que aprendi:
- Como criar uma máquina virtual no Azure usando o portal web;
- Configurar tamanho, imagem (SO), grupo de recursos e autenticação;
- A importância da alta disponibilidade e resiliência regional na configuração de VMs;
- Como aplicar práticas de governança como tags e políticas de custo;
- Diferenças entre escalabilidade vertical e horizontal aplicadas às VMs;
- Monitoramento básico e uso do Azure Resource Manager (ARM).

### Etapas realizadas
- Acesso ao Portal Azure
- Criação de um grupo de recursos para organização dos recursos
- Criação da VM com imagem Ubuntu Server 20.04
- Configuração de:
    - Tamanho (SKU)
    - Autenticação via chave SSH
    - Porta RDP/SSH liberada
- Testes de conexão via SSH
- Visualização de métricas e monitoramento da instância
- Encerramento e exclusão dos recursos para evitar cobranças

### Conceitos aplicados
- IaaS (Infraestrutura como Serviço): Uso de VMs como modelo sob demanda.
- Alta disponibilidade e escalabilidade: Garantia de funcionamento mesmo com falhas.
- Modelo de responsabilidade compartilhada: O Azure fornece a infraestrutura; o cliente gerencia o SO e os dados.