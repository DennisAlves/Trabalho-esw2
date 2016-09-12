# Trabalho ES 2
Desenvolvimento de um gerenciador para estoque de eletronicos.

## Descrição do negócio
No que trabalhamos no dia a dia temos uma necessidade de organizar e facilitar na distribuição de materiais. Entretanto temos dificuldades e a necessidade de um sistema para organizar e orientar a distribuição dos materiais. O trabalho se passa em um almoxarifado onde ficam estocados os materiais e equipamentos, toda remeça que recebe tem um protocolo a ser efetuado “Protocolo de entrada de materiais” que é uma anotação simples que faz o controle de entrada do estoque. Quando temos uma quantidade de materiais usados ou desgastados, fazemos um “Protocolo de uso ou desgaste de materiais” que controla a quantidade desgastada, perdidos ou usada. No fim de cada semestre temos que entregar esse dois “Protocolos” para o financeiro, para que possamos efetuar uma requisição de materiais ou equipamentos. No financeiro tem pré-estabelecido uma quantidade de materiais e equipamento com forme a demanda de cada semestre, eles compararam os protocolos de entra e os de uso/desgastes e faz uma estimativa dos materiais que usará no próximo semestre fazendo uma estimativa de preço ou orçamento dos materiais, depois que os materiais chegam o financeiro faz uma verificação nas notas fiscais verificando se os materiais estejam correspondendo com as notas, se não estiver correspondendo com as notas é reenviado para os fornecedores para que possa efetuar a troca ou para solicitar o envio dos materiais que falta. O material é entregue ao almoxarifado que faz uma segunda verificação de materiais e faz uma contagem de materiais que é entregue ao financeiro.

## Regras de negócios

* *RN01* **Tipo de material** - Os materiais podem ser muito utilizados ou pouco utilizados, também são classificados em: resistentes ou frágeis.
* *RN02* **Quantidade limite dos materiais** - As quantidades de cada tipo de materiais e equipamentos possuem um limite por semestre.
* *RN03* **Orçamento** - Todas as demandas de materiais solicitados tem um valor de custo limite, ou seja, um limite de orçamento.
* *RN04* **Relatorio de materiais usados ou descartados** - O Almoxarifado tem um relatório de perdas e de desgaste de materiais e equipamentos.
* *RN05* **Tempo de Solicitação de materiais** - A entrega do pedido de materiais é de 20 a 30 dias antes do inicio dos semestres.
* *RN06* **Verificação do material** - Para todos os materiais recebidos verifica-se a nota fiscal dos produtos e é feita uma comparação com a solicitação, se os produtos corresponderem o material é liberado para o almoxarife.
* *RN07* **Solicitações de materiais** - Todo semestre tem uma solicitação de material que o colaborador do almoxarifado efetua, quando há necessidade de novos materiais ou novas tecnologias.

## Diagramas de Atividades

**Diagrama de Atividade 00**
![Diagrama de Atividade 00](/img/atividades/diagrama-atividade0.png)
