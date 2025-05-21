# Componentes Arquiteturais do Azure

## Infraestrutura Física do Azure

O Azure opera uma vasta rede global de datacenters que formam sua infraestrutura física. Esses datacenters são agrupados em regiões, permitindo redundância e alta disponibilidade.

- **Regiões do Azure**:  
  Áreas geográficas que contêm um ou mais datacenters. Exemplos: "Leste dos EUA", "Oeste da Europa".

- **Zonas de Disponibilidade**:  
  Locais fisicamente separados dentro de uma mesma região, com energia, resfriamento e rede independentes, oferecendo maior resiliência.

- **Geografias do Azure**:  
  Agrupamento de regiões para atender requisitos legais de residência e conformidade de dados (ex: Geografia da União Europeia).

Essa estrutura garante serviços com baixa latência, alta disponibilidade e conformidade com regulamentações locais.

## Infraestrutura de Gerenciamento do Azure

O Azure oferece diversas ferramentas para gerenciar e monitorar recursos de forma eficiente:

- **Azure Portal**:  
  Interface gráfica web para criação, configuração e monitoramento de recursos.

- **Azure PowerShell e CLI**:  
  Ferramentas de linha de comando para automação e gerenciamento via scripts.

- **Azure Resource Manager (ARM)**:  
  Plataforma para implantar, gerenciar e monitorar recursos em grupo, com controle centralizado.

- **Modelos ARM**:  
  Arquivos JSON que definem infraestrutura e configurações, permitindo implantações consistentes e repetíveis.

- **Azure Monitor**:  
  Serviço de monitoramento que coleta, analisa e gera insights a partir de métricas e logs dos recursos.

Essas ferramentas ajudam na automação, governança e monitoramento eficiente dos recursos em nuvem.
