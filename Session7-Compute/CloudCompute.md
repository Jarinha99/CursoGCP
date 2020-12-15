# Cloud Compute

## Tipos

#### GCE - Computer Engine

Serviço de máquinas virtuais
- Windows / Linux
- HDD / SDD
- Pré definida / Configurável
- Faturamento por segundos
- Desconto por uso prolongado 
- Desconto por uso contínuo
- Máquinas Preemptivas
  - Custo mais baixo.
  - Somem em X tempo configurado.
  - Próprio para escalabidade rápida de um momento específico.
- Baixo custo

#### GAE - App Engine

Plataforme como serviço, Serveless, apenas sobe a aplicação no App Engine, e todo o gerenciamento da máquina e do ambiente é do GCP.

- Java/PHP/NodeJS/C#/Go/Python
- Versionamento
- Monitoramento da aplicação
- Ambiente Standard e Flexível
- **Apenas 1 APP por projeto**

#### GKE - Kubernetes Engine

- Aplicativos em Containeres
- Gestão de Kubernetes
- Suporte a Docker
- Escalonamento automático
- Upgrade automático
- Reparo automático
- Segurança
- Limitação de Recursos por container

#### Cloud Functions

- Função como Serviço
- Serveless
- NodeJS/Pyhton/Go
- Acionado Direto
- Acionado por eventos
- Escalonamento automático
- Micro services
- Cobrança por Execução

#### Cloud Run

- Aplicativos em Containeres
- Serveless
- Containeres sem estado
  - Containeres que não persistem dados
- Baseado em Knative
- Invocáveis por HTTP
- Escalonamento automático
