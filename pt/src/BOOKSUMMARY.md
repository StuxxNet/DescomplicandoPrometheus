# [Descomplicando o Prometheus](https://www.linuxtips.io/course/descomplicando-prometheus) - O LIVRO
### Conteúdo do Livro

<details>
<summary>DAY-1</summary>

- **[DAY-1](pt/src/day-1/README.md) - Em revisão...**
    - [Por que precisamos de ferramentas como o Prometheus?](pt/src/day-1/README.md#por-que-precisamos-de-ferramentas-como-o-prometheus)
    - [O que é monitorar?](pt/src/day-1/README.md#o-que-e-monitorar)
        - [O monitoramento e a observabilidade](pt/src/day-1/README.md#o-monitoramento-e-a-observabilidade)
    - [O que é o Prometheus?](pt/src/day-1/README.md#o-que-e-o-prometheus)
        - [A arquitetura do Prometheus](pt/src/day-1/README.md#a-arquitetura-do-prometheus)
    - [Instalando o Prometheus](pt/src/day-1/README.md#instalando-o-prometheus)
        - [Executando o Prometheus em um node Linux](pt/src/day-1/README.md#executando-o-prometheus-em-um-node-linux)
        - [Instalação do Prometheus no Linux](pt/src/day-1/README.md#instalação-do-prometheus-no-linux)
    - [A sua lição de casa](pt/src/day-1/README.md#a-sua-lição-de-casa)
    - [Desafio do Day-1](pt/src/day-1/README.md#desafio-do-day-1)
    - [Final do Day-1](pt/src/day-1/README.md#final-do-day-1)

</details>

&nbsp;

<details>
<summary>DAY-2</summary>

- **[DAY-2](pt/src/day-2/README.md) - Em revisão...**
    - [O Data Model do Prometheus](pt/src/day-2/README.md#o-data-model-do-prometheus)
    - [As queries do Prometheus e o PromQL](pt/src/day-2/README.md#as-queries-do-prometheus-e-o-promql)
    - [O nosso primeiro exporter](pt/src/day-2/README.md#o-nosso-primeiro-exporter)
    - [Nosso Primeiro Exporter no Container](pt/src/day-2/README.md#nosso-primeiro-exporter-no-container)
    - [Os Targets do Prometheus](pt/src/day-2/README.md#os-targets-do-prometheus)
    - [Visualizando as métricas do nosso primeiro exporter](pt/src/day-2/README.md#visualizando-as-métricas-do-nosso-primeiro-exporter)
    - [Conhecendo um pouco mais sobre os tipos de dados do Prometheus](pt/src/day-2/README.md#conhecendo-um-pouco-mais-sobre-os-tipos-de-dados-do-prometheus) 
    - [gauge: Medidor](pt/src/day-2/README.md#gauge-medidor)
    - [counter: Contador](pt/src/day-2/README.md#counter-contador)
    - [summary: Resumo](pt/src/day-2/README.md#summary-resumo)
    - [histogram: Histograma](pt/src/day-2/README.md#histogram-histograma)
    - [Chega por hoje!](pt/src/day-2/README.md#chega-por-hoje)
    - [Lição de casa](pt/src/day-2/README.md#lição-de-casa)

</details>

&nbsp;

<details>
<summary>DAY-3</summary>

- **[DAY-3](pt/src/day-3/README.md) - Em revisão...**
    - [Criando o nosso segundo exporter](pt/src/day-3/README.md#criando-o-nosso-segundo-exporter)
        - [Criando o nosso exporter usando Go](pt/src/day-3/README.md#criando-o-nosso-exporter-usando-go)
        - [Adicionando o nosso exporter no container](pt/src/day-3/README.md#adicionando-o-nosso-exporter-no-container)
        - [Adicionando o novo Target no Prometheus](pt/src/day-3/README.md#adicionando-o-novo-target-no-prometheus)
    - [As Funções](pt/src/day-3/README.md#as-funções)
    - [A função rate](pt/src/day-3/README.md#a-função-rate)
    - [A função irate](pt/src/day-3/README.md#a-função-irate)
    - [A função delta](pt/src/day-3/README.md#a-função-delta)
    - [A função increase](pt/src/day-3/README.md#a-função-increase)
    - [A função sum](pt/src/day-3/README.md#a-função-sum)
    - [A função count](pt/src/day-3/README.md#a-função-count)
    - [A função avg](pt/src/day-3/README.md#a-função-avg)
    - [A função min](pt/src/day-3/README.md#a-função-min)
    - [A função max](pt/src/day-3/README.md#a-função-max)
    - [A função avg_over_time](pt/src/day-3/README.md#a-função-avg_over_time)
    - [A função sum_over_time](pt/src/day-3/README.md#a-função-sum_over_time)
    - [A função max_over_time](pt/src/day-3/README.md#a-função-max_over_time)
    - [A função min_over_time](pt/src/day-3/README.md#a-função-min_over_time)
    - [A função stddev_over_time](pt/src/day-3/README.md#a-função-stddev_over_time)
    - [A função by](pt/src/day-3/README.md#a-função-by)
    - [A função without](pt/src/day-3/README.md#a-função-without)
    - [A função histogram_quantile e quantile](pt/src/day-3/README.md#a-função-histogram_quantile-e-quantile)
    - [Praticando e usando as funções](pt/src/day-3/README.md#praticando-e-usando-as-funções)
    - [Operadores](pt/src/day-3/README.md#operadores)
        - [Operador de igualdade](pt/src/day-3/README.md#operador-de-igualdade)
        - [Operador de diferença](pt/src/day-3/README.md#operador-de-diferença)
        - [Operador de maior que](pt/src/day-3/README.md#operador-de-maior-que)
        - [Operador de menor que](pt/src/day-3/README.md#operador-de-menor-que)
        - [Operador de maior ou igual que](pt/src/day-3/README.md#operador-de-maior-ou-igual-que)
        - [Operador de menor ou igual que](pt/src/day-3/README.md#operador-de-menor-ou-igual-que)
        - [Operador de multiplicação](pt/src/day-3/README.md#operador-de-multiplicação)
        - [Operador de divisão](pt/src/day-3/README.md#operador-de-divisão)
        - [Operador de adição](pt/src/day-3/README.md#operador-de-adição)
        - [Operador de subtração](pt/src/day-3/README.md#operador-de-subtração)
        - [Operador de modulo](pt/src/day-3/README.md#operador-de-modulo)
        - [Operador de potenciação](pt/src/day-3/README.md#operador-de-potenciação)
        - [Operador de agrupamento](pt/src/day-3/README.md#operador-de-agrupamento)
        - [Operador de concatenação](pt/src/day-3/README.md#operador-de-concatenação)
        - [Operador de comparação de strings](pt/src/day-3/README.md#operador-de-comparação-de-strings)
        - [Chega de operadores por hoje](pt/src/day-3/README.md#chega-de-operadores-por-hoje)
    - [O Node Exporter](pt/src/day-3/README.md#o-node-exporter)
        - [Os Collectors](pt/src/day-3/README.md#os-collectors)
        - [Instalação do Node Exporter no Linux](pt/src/day-3/README.md#instalação-do-node-exporter-no-linux)
        - [Adicionando o Node Exporter no Prometheus](pt/src/day-3/README.md#adicionando-o-node-exporter-no-prometheus)
        - [Habilitando novos collectors no Node Exporter](pt/src/day-3/README.md#habilitando-novos-collectors-no-node-exporter)
    - [Algumas queries capturando métricas do Node Exporter](pt/src/day-3/README.md#algumas-queries-capturando-métricas-do-node-exporter)
    - [O Grafana](pt/src/day-3/README.md#o-grafana)
    - [Instalação do Grafana](pt/src/day-3/README.md#instalação-do-grafana)
    - [Adicionando o Prometheus como Data Source](pt/src/day-3/README.md#adicionando-o-prometheus-como-data-source)
    - [Criando o nosso primeiro Dashboard](pt/src/day-3/README.md#criando-o-nosso-primeiro-dashboard)
    - [Chega por hoje!](pt/src/day-3/README.md#chega-por-hoje)
    - [Lição de casa](pt/src/day-3/README.md#lição-de-casa)
    - [Referências](pt/src/day-3/README.md#referências)

</details>

&nbsp;

<details>
<summary>DAY-4</summary>

- **[DAY-4](pt/src/day-4/README.md) - Em revisão...**
    - [O que iremos ver hoje?](pt/src/day-4/README.md#o-que-iremos-ver-hoje)
    - [Conteúdo do Day-4](pt/src/day-4/README.md#conteúdo-do-day-4)
    - [O Grafana](pt/src/day-4/README.md#o-grafana)
    - [Instalando o Grafana](pt/src/day-4/README.md#instalando-o-grafana)
    - [Adicionando o Prometheus como Data Source](pt/src/day-4/README.md#adicionando-o-prometheus-como-data-source)
    - [Criando o nosso primeiro Dashboard](pt/src/day-4/README.md#criando-o-nosso-primeiro-dashboard)
    - [Alertmanager](pt/src/day-4/README.md#alertmanager)
    - [Instalando o Alertmanager](pt/src/day-4/README.md#instalando-o-alertmanager)

</details>

&nbsp;

<details>
<summary>DAY-5</summary>

- **[DAY-5](pt/src/day-5/README.md) - Em revisão...**

</details>

&nbsp;

<details>
<summary>DAY-6</summary>

- **[DAY-6](pt/src/day-6/README.md) - Em revisão...**
    - [O que iremos ver hoje](pt/src/day-6/README.md#o-que-iremos-ver-hoje)
    - [Conteúdo do Day-6](pt/src/day-6/README.md#conteúdo-do-day-6)
    - [O que é o kube-prometheus](pt/src/day-6/README.md#o-que-é-o-kube-prometheus)
    - [Instalando o nosso cluster Kubernetes](pt/src/day-6/README.md#instalando-o-nosso-cluster-kubernetes)
    - [Instalando o Kube-Prometheus](pt/src/day-6/README.md#instalando-o-kube-prometheus)
    - [Acessando o Grafana](pt/src/day-6/README.md#acessando-o-grafana)
    - [Acessando o Prometheus](pt/src/day-6/README.md#acessando-o-prometheus)
    - [Acessando o AlertManager](pt/src/day-6/README.md#acessando-o-alertmanager)
    - [Chega por hoje!](pt/src/day-6/README.md#chega-por-hoje)
    - [Lição de casa](pt/src/day-6/README.md#lição-de-casa)

</details>

&nbsp;

<details>
<summary>DAY-7</summary>

- **[DAY-7](pt/src/day-7/README.md) - Em revisão...**
    - [O que iremos ver hoje?](pt/src/day-7/README.md#o-que-iremos-ver-hoje)
    - [Conteúdo do Day-7](pt/src/day-7/README.md#conteúdo-do-day-7)
    - [Os ServiceMonitors](pt/src/day-7/README.md#os-servicemonitors)
    - [Criando um ServiceMonitor](pt/src/day-7/README.md#criando-um-servicemonitor)
    - [Os PodMonitors](pt/src/day-7/README.md#os-podmonitors)
    - [Criando um PodMonitor](pt/src/day-7/README.md#criando-um-podmonitor)
    - [Criando nosso primeiro alerta](pt/src/day-7/README.md#criando-nosso-primeiro-alerta)
    - [O que é um PrometheusRule?](pt/src/day-7/README.md#o-que-é-um-prometheusrule)
        - [Criando um PrometheusRule](pt/src/day-7/README.md#criando-um-prometheusrule)
    - [Chega por hoje!](pt/src/day-7/README.md#chega-por-hoje)
    - [Lição de casa](pt/src/day-7/README.md#lição-de-casa)

</details>

&nbsp;

<details>
<summary>DAY-8</summary>

- **[DAY-8](pt/src/day-8/README.md) - Em revisão...**
    - [O que iremos ver hoje?](pt/src/day-8/README.md#o-que-iremos-ver-hoje)
    - [Conteúdo do Day-8](pt/src/day-8/README.md#conteúdo-do-day-8)
    - [Vamos brincar com as métricas do Kubernetes](pt/src/day-8/README.md#vamos-brincar-com-as-métricas-do-kubernetes)
        - [O que podemos saber sobre os nodes do nosso cluster?](pt/src/day-8/README.md#o-que-podemos-saber-sobre-os-nodes-do-nosso-cluster)
        - [Quantos nós temos no nosso cluster?](pt/src/day-8/README.md#quantos-nós-temos-no-nosso-cluster)
        - [Qual a quantidade de CPU e memória que cada nó tem?](pt/src/day-8/README.md#qual-a-quantidade-de-cpu-e-memória-que-cada-nó-tem)
        - [O nó está disponível para receber novos pods?](pt/src/day-8/README.md#o-nó-está-disponível-para-receber-novos-pods)
        - [Qual a quantidade de informação que cada nó está recebendo e enviando?](pt/src/day-8/README.md#qual-a-quantidade-de-informação-que-cada-nó-está-recebendo-e-enviando)
        - [Quantos pods estão rodando em cada nó?](pt/src/day-8/README.md#quantos-pods-estão-rodando-em-cada-nó)
    - [Agora vamos saber se o nosso cluster está com problemas](pt/src/day-8/README.md#agora-vamos-saber-se-o-nosso-cluster-está-com-problemas)
        - [O que podemos saber sobre os pods do nosso cluster?](pt/src/day-8/README.md#o-que-podemos-saber-sobre-os-pods-do-nosso-cluster)
        - [Quantos pods estão rodando no nosso cluster?](pt/src/day-8/README.md#quantos-pods-estão-rodando-no-nosso-cluster)
        - [Quantos pods estão com problemas?](pt/src/day-8/README.md#quantos-pods-estão-com-problemas)
        - [Verificar os pods e os limites de memória e CPU configurados](pt/src/day-8/README.md#verificar-os-pods-e-os-limites-de-memória-e-cpu-configurados)
        - [Verificar se o cluster está com problemas relacionados ao disco](pt/src/day-8/README.md#verificar-se-o-cluster-está-com-problemas-relacionados-ao-disco)
        - [Verificar se o cluster está com problemas relacionados a memória](pt/src/day-8/README.md#verificar-se-o-cluster-está-com-problemas-relacionados-a-memória)
    - [E como saber se meus deployments estão com problemas?](pt/src/day-8/README.md#e-como-saber-se-meus-deployments-estão-com-problemas)
        - [Quantos deployments estão rodando no meu cluster?](pt/src/day-8/README.md#quantos-deployments-estão-rodando-no-meu-cluster)
        - [Quantos deployments estão com problemas?](pt/src/day-8/README.md#quantos-deployments-estão-com-problemas)
        - [Qual o status dos meus deployments?](pt/src/day-8/README.md#qual-o-status-dos-meus-deployments)
    - [E como saber se meus serviços estão com problemas?](pt/src/day-8/README.md#e-como-saber-se-meus-serviços-estão-com-problemas)
        - [Quantos serviços estão rodando no meu cluster?](pt/src/day-8/README.md#quantos-serviços-estão-rodando-no-meu-cluster)
        - [Todos os meus serviços estão com endpoints?](pt/src/day-8/README.md#todos-os-meus-serviços-estão-com-endpoints)
        - [Todos os meus serviços estão com endpoints ativos?](pt/src/day-8/README.md#todos-os-meus-serviços-estão-com-endpoints-ativos)
    - [Como eu posso modificar as configurações do meu Prometheus?](pt/src/day-8/README.md#como-eu-posso-modificar-as-configurações-do-meu-prometheus)
        - [Definindo o nosso Prometheus](pt/src/day-8/README.md#definindo-o-nosso-prometheus)
        - [Definindo o nosso Alertmanager](pt/src/day-8/README.md#definindo-o-nosso-alertmanager)

</details>

&nbsp;

<details>
<summary>DAY-9</summary>

- **[DAY-9](pt/src/day-9/README.md) - Em revisão...**
    - [O que iremos ver hoje?](#o-que-iremos-ver-hoje)
    - [Conteúdo do Day-9](#conteúdo-do-day-9)
    - [O que é Relabeling?](#o-que-é-relabeling)
    - [Como funciona o Relabeling?](#como-funciona-o-relabeling)
    - [Exemplos de uso do Relabeling](#exemplos-de-uso-do-relabeling)
        - [ Removendo uma métrica baseado em uma label](#-removendo-uma-métrica-baseado-em-uma-label)
        - [Junta duas labels em uma só](#junta-duas-labels-em-uma-só)
        - [Adicionando uma nova label](#adicionando-uma-nova-label)
        - [Armazenando somente métricas específicas](#armazenando-somente-métricas-específicas)
        - [Mapeando todas as labels do Kubernetes](#mapeando-todas-as-labels-do-kubernetes)
    - [As meta labels do Prometheus](as-metas-labels-do-prometheus)

</details>

&nbsp;

<details>
<summary>REVISAR</summary><!-- #TODO -->

- **[DAY-3](day-3) - Em revisão...**
- [Criando o nosso segundo exporter](day-3/#criando-o-nosso-segundo-exporter)
	- [Criando o nosso exporter usando Go](day-3/#criando-o-nosso-exporter-usando-go)
	- [Adicionando o nosso exporter no container](day-3/#adicionando-o-nosso-exporter-no-container)
	- [Adicionando o novo Target no Prometheus](day-3/#adicionando-o-novo-target-no-prometheus)
- [As Funções](day-3/#as-funções)
  - [A função rate](day-3/#a-função-rate)
  - [A função irate](day-3/#a-função-irate)
  - [A função delta](day-3/#a-função-delta)
  - [A função increase](day-3/#a-função-increase)
  - [A função sum](day-3/#a-função-sum)
  - [A função count](day-3/#a-função-count)
  - [A função avg](day-3/#a-função-avg)
  - [A função min](day-3/#a-função-min)
  - [A função max](day-3/#a-função-max)
  - [A função avg_over_time](day-3/#a-função-avg_over_time)
  - [A função sum_over_time](day-3/#a-função-sum_over_time)
  - [A função max_over_time](day-3/#a-função-max_over_time)
  - [A função min_over_time](day-3/#a-função-min_over_time)
  - [A função stddev_over_time](day-3/#a-função-stddev_over_time)
  - [A função by](day-3/#a-função-by)
  - [A função without](day-3/#a-função-without)
  - [A função histogram_quantile e quantile](day-3/#a-função-histogram_quantile-e-quantile)
- [Praticando e usando as funções](day-3/#praticando-e-usando-as-funções)
- [Operadores](day-3/#operadores)
	- [Operador de igualdade](day-3/#operador-de-igualdade)
	- [Operador de diferença](day-3/#operador-de-diferença)
	- [Operador de maior que](day-3/#operador-de-maior-que)
	- [Operador de menor que](day-3/#operador-de-menor-que)
	- [Operador de maior ou igual que](day-3/#operador-de-maior-ou-igual-que)
	- [Operador de menor ou igual que](day-3/#operador-de-menor-ou-igual-que)
	- [Operador de multiplicação](day-3/#operador-de-multiplicação)
	- [Operador de divisão](day-3/#operador-de-divisão)
	- [Operador de adição](day-3/#operador-de-adição)
	- [Operador de subtração](day-3/#operador-de-subtração)
	- [Operador de modulo](day-3/#operador-de-modulo)
	- [Operador de potenciação](day-3/#operador-de-potenciação)
	- [Operador de agrupamento](day-3/#operador-de-agrupamento)
	- [Operador de concatenação](day-3/#operador-de-concatenação)
	- [Operador de comparação de strings](day-3/#operador-de-comparação-de-strings)
	- [Chega de operadores por hoje](day-3/#chega-de-operadores-por-hoje)
- [O Node Exporter](day-3/#o-node-exporter)
	- [Os Collectors](day-3/#os-collectors)
	- [Instalação do Node Exporter no Linux](day-3/#instalação-do-node-exporter-no-linux)
	- [Adicionando o Node Exporter no Prometheus](day-3/#adicionando-o-node-exporter-no-prometheus)
	- [Habilitando novos collectors no Node Exporter](day-3/#habilitando-novos-collectors-no-node-exporter)
- [Algumas queries capturando métricas do Node Exporter](day-3/#algumas-queries-capturando-métricas-do-node-exporter)
- [O Grafana](day-3/#o-grafana)
  - [Instalação do Grafana](day-3/#instalação-do-grafana)
  - [Adicionando o Prometheus como Data Source](day-3/#adicionando-o-prometheus-como-data-source)
  - [Criando o nosso primeiro Dashboard](day-3/#criando-o-nosso-primeiro-dashboard)
- [Chega por hoje!](day-3/#chega-por-hoje)
- [Lição de casa](day-3/#lição-de-casa)
- [Referências](day-3/#referências)

&nbsp;

- **[DAY-4](day-4) - Em revisão...**
- [O que iremos ver hoje?](day-4/#o-que-iremos-ver-hoje)
- [Conteúdo do Day-4](day-4/#conteúdo-do-day-4)
- [O Grafana](day-4/#o-grafana)
  - [Instalando o Grafana](day-4/#instalando-o-grafana)
  - [Adicionando o Prometheus como Data Source](day-4/#adicionando-o-prometheus-como-data-source)
  - [Criando o nosso primeiro Dashboard](day-4/#criando-o-nosso-primeiro-dashboard)
- [Alertmanager](day-4/#alertmanager)
  - [Instalando o Alertmanager](day-4/#instalando-o-alertmanager)

&nbsp;

- **[DAY-5](day-5) - Em revisão...**

&nbsp;

- **[DAY-6](day-6) - Em revisão...**
- [O que iremos ver hoje](day-6/#o-que-iremos-ver-hoje)
- [Conteúdo do Day-6](day-6/#conteúdo-do-day-6)
- [O que é o kube-prometheus](day-6/#o-que-é-o-kube-prometheus)
  - [Instalando o nosso cluster Kubernetes](day-6/#instalando-o-nosso-cluster-kubernetes)
  - [Instalando o Kube-Prometheus](day-6/#instalando-o-kube-prometheus)
  - [Acessando o Grafana](day-6/#acessando-o-grafana)
  - [Acessando o Prometheus](day-6/#acessando-o-prometheus)
  - [Acessando o AlertManager](day-6/#acessando-o-alertmanager)
- [Chega por hoje!](day-6/#chega-por-hoje)
- [Lição de casa](day-6/#lição-de-casa)

&nbsp;

- **[DAY-7](day-7) - Em revisão...**
- [O que iremos ver hoje?](day-7/#o-que-iremos-ver-hoje)
- [Conteúdo do Day-7](day-7/#conteúdo-do-day-7)
  - [Os ServiceMonitors](day-7/#os-servicemonitors)
  - [Criando um ServiceMonitor](day-7/#criando-um-servicemonitor)
  - [Os PodMonitors](day-7/#os-podmonitors)
  - [Criando um PodMonitor](day-7/#criando-um-podmonitor)
  - [Criando nosso primeiro alerta](day-7/#criando-nosso-primeiro-alerta)
  - [O que é um PrometheusRule?](day-7/#o-que-é-um-prometheusrule)
    - [Criando um PrometheusRule](day-7/#criando-um-prometheusrule)
- [Chega por hoje!](day-7/#chega-por-hoje)
- [Lição de casa](day-7/#lição-de-casa)

&nbsp;

- **[DAY-8](day-8) - Em revisão...**
- [O que iremos ver hoje?](day-8/#o-que-iremos-ver-hoje)
- [Conteúdo do Day-8](day-8/#conteúdo-do-day-8)
  - [Vamos brincar com as métricas do Kubernetes](day-8/#vamos-brincar-com-as-métricas-do-kubernetes)
    - [O que podemos saber sobre os nodes do nosso cluster?](day-8/#o-que-podemos-saber-sobre-os-nodes-do-nosso-cluster)
      - [Quantos nós temos no nosso cluster?](day-8/#quantos-nós-temos-no-nosso-cluster)
      - [Qual a quantidade de CPU e memória que cada nó tem?](day-8/#qual-a-quantidade-de-cpu-e-memória-que-cada-nó-tem)
      - [O nó está disponível para receber novos pods?](day-8/#o-nó-está-disponível-para-receber-novos-pods)
      - [Qual a quantidade de informação que cada nó está recebendo e enviando?](day-8/#qual-a-quantidade-de-informação-que-cada-nó-está-recebendo-e-enviando)
    - [Quantos pods estão rodando em cada nó?](day-8/#quantos-pods-estão-rodando-em-cada-nó)
  - [Agora vamos saber se o nosso cluster está com problemas](day-8/#agora-vamos-saber-se-o-nosso-cluster-está-com-problemas)
    - [O que podemos saber sobre os pods do nosso cluster?](day-8/#o-que-podemos-saber-sobre-os-pods-do-nosso-cluster)
      - [Quantos pods estão rodando no nosso cluster?](day-8/#quantos-pods-estão-rodando-no-nosso-cluster)
      - [Quantos pods estão com problemas?](day-8/#quantos-pods-estão-com-problemas)
      - [Verificar os pods e os limites de memória e CPU configurados](day-8/#verificar-os-pods-e-os-limites-de-memória-e-cpu-configurados)
      - [Verificar se o cluster está com problemas relacionados ao disco](day-8/#verificar-se-o-cluster-está-com-problemas-relacionados-ao-disco)
      - [Verificar se o cluster está com problemas relacionados a memória](day-8/#verificar-se-o-cluster-está-com-problemas-relacionados-a-memória)
  - [E como saber se meus deployments estão com problemas?](day-8/#e-como-saber-se-meus-deployments-estão-com-problemas)
      - [Quantos deployments estão rodando no meu cluster?](day-8/#quantos-deployments-estão-rodando-no-meu-cluster)
      - [Quantos deployments estão com problemas?](day-8/#quantos-deployments-estão-com-problemas)
      - [Qual o status dos meus deployments?](day-8/#qual-o-status-dos-meus-deployments)
  - [E como saber se meus serviços estão com problemas?](day-8/#e-como-saber-se-meus-serviços-estão-com-problemas)
      - [Quantos serviços estão rodando no meu cluster?](day-8/#quantos-serviços-estão-rodando-no-meu-cluster)
      - [Todos os meus serviços estão com endpoints?](day-8/#todos-os-meus-serviços-estão-com-endpoints)
      - [Todos os meus serviços estão com endpoints ativos?](day-8/#todos-os-meus-serviços-estão-com-endpoints-ativos)
  - [Como eu posso modificar as configurações do meu Prometheus?](day-8/#como-eu-posso-modificar-as-configurações-do-meu-prometheus)
    - [Definindo o nosso Prometheus](day-8/#definindo-o-nosso-prometheus)
    - [Definindo o nosso Alertmanager](day-8/#definindo-o-nosso-alertmanager)

&nbsp;

- **[DAY-9](day-9) - Em revisão...**
- [O que iremos ver hoje?](day-9#o-que-iremos-ver-hoje)
- [Conteúdo do Day-9](day-9#conteúdo-do-day-9)
- [O que é Relabeling?](day-9#o-que-é-relabeling)
  - [Como funciona o Relabeling?](day-9#como-funciona-o-relabeling)
  - [Exemplos de uso do Relabeling](day-9#exemplos-de-uso-do-relabeling)
    - [ Removendo uma métrica baseado em uma label](day-9#-removendo-uma-métrica-baseado-em-uma-label)
    - [Junta duas labels em uma só](day-9#junta-duas-labels-em-uma-só)
    - [Adicionando uma nova label](day-9#adicionando-uma-nova-label)
    - [Armazenando somente métricas específicas](day-9#armazenando-somente-métricas-específicas)
    - [Mapeando todas as labels do Kubernetes](day-9#mapeando-todas-as-labels-do-kubernetes)
- [As meta labels do Prometheus](day-9#as-metas-labels-do-prometheus)

</details>