# USP - Projeto - Fonte de Tensão Variável
Aqui, serão disponibilizados os arquivos e detalhes sobre a elaboração de um projeto de fonte de tensão variável, feita por alunos do ICMC (USP) para a disciplina de Eletrônica para Computação.

## Instruções
Será construída uma fonte capaz de transformar corrente alternada de tensão 127 Volts em corrente contínua, sendo a tensão desta ajustável e variável entre 3 a 12 Volts.

## Componentes utilizados
**Quantidade** | **Componentes** | **Preço** (unidade) | **Total**   
-----------|-------------|-----------------|------
10x | Diodo Retificador | R$0,20 | R$2,00
1x | Diodo Zener (13V) | R$0,50 | R$0,50
1x | Potenciômetro 1W | R$4,75 | R$4,75
1x | Transistor (0,8A) | R$0,70 | R$0,70
1x | Led 5mm | R$0,50 | R$0,50
10x | Resistor 1K | R$0,07 | R$0,70
10x | Resistor 2K | R$0,07 | R$0,70
1x | Capacitor | R$1,05 | R$1,05
1x | Fusível 20A | R$1,10 | R$1,10
----------|----------|----------| **R$12,00**

## Ficha Técnica 
### Diodo Retificador
Em termos gerais, o diodo retificador é um dispositivo semicondutor utilizado para converter sinais em corrente alternada para corrente contínua. No projeto em questão, possibilitará o aproveitamento de ambos os ciclos da corrente alternada de origem.

### Diodo Zener 
Devido às características desse componente, também é conhecido como "diodo regulador de tensão máxima". Isso se deve ao fato do componente ser fabricado para trabalhar com a polarização reversa, isto é, ao atingir a tensão de ruptura, ela se torna praticamente constante. Dessa forma, nos termos deste projeto, se a tensão for menor do que 12v, o diodo não conduz e não interfere no circuito, se for maior, deixará a corrente passar e manterá a tensão em 12v naquele ponto. Logo, o diodo zener manterá constante a tensão máxima desta fonte de tensão variável, não ultrapassando os 12v. 

### Potenciômetro
Nada mais é que um resistor variável, o qual, neste projeto de fonte de tensão variável, permitirá o controle do valor da tensão resultante entre 3v e 12v.

### Transistores
São componentes eletrônicos utilizados para permitir a passagem da corrente elétrica de forma ajustável. No projeto, foi usado também para evitar o desperdício de corrente elétrica pelo Diodo Zener.

### Resistores
São componentes eletrônicos que complementam o circuito, fazendo com que a corrente elétrica seja limitada e impedindo que a corrente do circuito ultrapasse os valores limites dos demais componentes utilizados.

### Capacitor
Componente elétrico capaz de acumular cargas elétricas na presença de uma diferença de potencial entre seus terminais, fornecendo, assim, corrente continua caso a tensão interna encontre-se superior à externa

### Fusível
Componente eletrônico utilizado para fins de segurança, impedindo a passagem de correntes muito altas e, assim, protegendo os demais componentes do circuito em eventuais picos de corrente elétrica.

## Circuito Construído
![image](https://user-images.githubusercontent.com/106783529/178118865-d62cf76a-c01c-4f21-aaf0-ca49457fe16d.png)
**Simulação Falstad:** https://tinyurl.com/2ct48ao7

## Integrantes do Grupo:
  Aluno(a) | Nº USP 
-----------|---------
Camila Donda Ronchi | 13672220
Joao Gabriel Manfre Nazar | 13733652
Lucas Lombardi Castro | 13672978
Lucas Piovani Ferreira | 13836813

