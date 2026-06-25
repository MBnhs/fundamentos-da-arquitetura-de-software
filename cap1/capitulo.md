# Capítulo 1

## Papel do Arquiteto de Software 
Entender e analisar os sistemas de software em toda sua complexidade e tomar decisões às vezes com informações incompletas. <br>
Avaliam trade-offs dentro de contextos complexos e em constante mudança.

**Decisões baseadas nas particularidades de cada ambiente.**

**Final do séc. XX**: infra e recursos compartilhados da maneira mais eficaz possível.

**Em 2002**: era inviável (custos) pensar em arquitetura de microsserviços (cada serviço com sua própria máquina isolada com seu próprio banco de dados).

> "Todas as arquiteturas são produtos de seu contexto."

### A Arquitetura de Software pode ser definida em quatro dimensões:

- estilo de arquitetura
- características de arquitetura
- componentes lógicos
- decisões de arquitetura


### Características da arquitetura
O que os sistema deve fazer (capacidades do sistema).

### Componentes lógicos
Comportamento do sistema (domínios, entidades e fluxos de trabalho).<br>
Após análise das características da arquitetura e componentes lógicos, **o arquiteto saberá o suficiente para escolher um estilo de arquitetura**.

### Decisões de arquitetura
Estabelecimento de regras de como um sistema deve ser construído.<br>

## Leis de Arquitetura

### Primeira Lei da Arquitetura de Software

> Tudo na Arquitetura de Software é um trade-off.

#### Corolário 1:
> Se você acha que descobriu um algo que não é um trade-off, é mais provável que não tenha identificado o trade-off... ainda.

#### Corolário 2:
> Você não pode fazer uma análise de trade-off uma vez e achar que terminou.

Cada situação exigirá que reavaliemos todos os trade-offs.


### Segunda Lei da Arquitetura de Software
> Porque é mais importante do que como.

- Porque o arquiteto ou equipe anterior tomou certas decisões.
- Decisões da Arquitetura de Software raramente são binárias.


### Terceira Lei da Arquitetura de Software
> A maioria das decisões de Arquitetura de Software não é binária, em vez disso, existe um espectro entre extresmos.