# Cloud Storage

## Descrição

**Cloud Storage** é o serviço de armazenamento em nuvem do GCP, armazenamento por Objeto.

## Formato

- Padrão de Buckets/Folders
  - Cada Bucket, é possível configurar de forma independente
    - Frequência de acesso
    - Região
    - Preço

## Configurações

#### Multi Regional

- Redundância Geográfica
- Disponibilidade de 99,99%
- Acesso frequente e imediato
- Usado para streaming de video, musica, jogos, sites e app mobile.

#### Regional

- Dados armazenados em uma região apenas
- Disponibilidade de 99,99%
- Acesso frequente e imediato
- Análise de dados, atender requisitos legais (Dados financeiros tem regras especiais para dados alocados fora do país)
- Custo de 1GB: 0.026$

#### Nearline

- Acesso apenas 1 vez por mês
- Disponibilidade de 99,95%
- Custos baixos de Armazenamento e alto para recuperação
- Usado para bakcups, archive.
- Custo de 1GB: 0.020$

#### Coldline

- Acesso apenas 1 vez por ano
- Disponibilidade de 99,95%
- Custos baixos de Armazenamento e alto para recuperação
- Usado para bakcups legais, desastre e recuperação.
- Custo de 1GB: 0.010$

#### Coldline

- Acesso apenas 1 vez por ano
- Disponibilidade de 99,95%
- Custos baixos de Armazenamento e alto para recuperação
- Usado para bakcups legais, desastre e recuperação.
- Custo de 1GB: 0.007$

## Caracteristicas

#### Life Cycle

Configuração Exemplo

- Inicialmente Multi Regional
- Caso o arquivo fique 30 dias sem acesso, é movido para Nearline
- Caso o arquivo fique 60 dias sem acesso, é movido para Coldline

#### Criptografia

Possível utilizar tanto do google, quanto uma chave própria do Cliente.

#### Versionamento

Versionamento de uploads do mesmo arquivo.

#### Política de retenção

Tempo mínimo configurado para poder ser deletado.

#### Repassar Pagamento pelo Solicitante

É possível configurar para que a pessoa que está acessando o arquivo que pague o acesso ao arquivo, e não o dono do Bucket.