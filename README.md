# Projeto Fonte Retificadora

## Projeto da Disciplina SSC0180 - Eletrônica para Computação

## Alunos:
Gabriel Alves Kuabara (KU) - N° USP 11275043 - [GitHub](https://github.com/GKuabara)

Guilherme Machado Rios (Bio) - N° USP 11222839 - [GitHub](https://github.com/Guibi0)

Guilherme Lourenço de Toledo (Vinho) - N° USP 11795811 - [GitHub](https://github.com/guitld)

Victor Henrique de Sa Silva (Spider) - N° USP 11795759 - [GitHub](https://github.com/VictorHenrique)

## Instrucoes:
Projeto de fonte retificadora de tensão contínua entre 3V a 12V com capacidade de 100mA.
A partir de uma tomada de 127V de corrente alternada e frequência de 60Hz, a fonte deve ser capaz de deixar a corrente contínua com tensão ajustável entre 3V a 12V.

## Imagem do Circuito Falstad:

## Link do Circuito [Falstad]()

## Componentes do Circuito:

## Tabela de Preços dos Componentes:

## Escolha dos componentes:
| **Quantidade** | **Componentes**   | **Especificações** | **Valor R$ **|
|----------------|-------------------|--------------------|--------------|
|         1x     | [Transformador](https://produto.mercadolivre.com.br/MLB-1299159736-transformador-1515v-1a-trafo-bivolt-_JM?matt_tool=82322591&matt_word&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgKeMy0nJofiC6KaxPgJOotdfYedegX4Cvw1K8ZATrrtRfrb-_nViN8aAoY1EALw_wcB&quantity=1) | 15V |  $29.90|
|         4x     | [Diodo](https://www.arduoeletro.com/diodo-1n-4007?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgJ0wxy2Hp_5nHJ2fnSKeIm5tyTmb2PZhb8mVqMMBYZ7-NIENwZE6ToaAscCEALw_wcB) | Normal |  $0.40|
|         1x     | [Capacitor Eletrolítico](https://www.eletrogate.com/capacitor-eletrolitico-470uf-x-50v?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgLso8jSTPGNfktENiS4ayUPJ60zbvoOe042wGCr6aaPkcPtqIjnEsEaAlifEALw_wcB) | 470uF |  $0.90|
|         1x     | [Resistor](https://www.banggood.com/pt/20pcs-2W-1_8KR-Metal-Film-Resistor-Resistance-1-1_8k-ohm-Resistor-p-1556816.html?gmcCountry=BR&currency=BRL&createTmp=1&utm_source=googleshopping&utm_medium=cpc_bgcs&utm_content=lijing&utm_campaign=ssc-br-all-newcustom-1119-re0318&ad_id=397733948343&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgKlRw1ruHRbicr8bXyCeORU6S4tgGMs7auLzgB2TiJkNsuFjTpwQgQaAp7TEALw_wcB&cur_warehouse=CN) | 1.8k |  $0.42|
|         1x     | [Resistor](https://produto.mercadolivre.com.br/MLB-1342907792-resistor-330-ohms-100-unidades-_JM?matt_tool=79246729&matt_word&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgLQmDXTySOG5SPVeSkZzxwxIkQ18u9yLq5I2XRCE6nhx1F0_QvOYmUaAspBEALw_wcB&quantity=1) | 330ohms |  $0.13|
|         1x     | [Resistor](https://produto.mercadolivre.com.br/MLB-937733782-kit-10-x-resistor-22k-ohm-14w-1-projeto-arduino-raspberry-_JM?matt_tool=79246729&matt_word&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgKAe7Wy7yk2gXiOZ5dqMArm00GkyamfaNH7T7loakiJhOX3ozAropwaAhECEALw_wcB&quantity=1) | 2.2k |  $0.86|
|         1x     | [Diodo](https://www.americanas.com.br/produto/1397103736?opn=YSMESP&sellerid=4145166000157&epar=bp_pl_00_go_am_todas_geral_gmv&WT.srch=1&acc=e789ea56094489dffd798f86ff51c7a9&i=5dd8ae5049f937f6254fab94&o=5df60079f8e95eac3dac6177&gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgIA358SW4MTZbxC3F3oDX6124FH0DvY33t5ULAEiQPJIl66QkP-IVgaApfTEALw_wcB) | Zener |  $0.60|
|         1x     | [Potenciômetro](https://shopee.com.br/5PCS-WTH118-2W-1A-Potenci%C3%B4metro-4-7k-ohm-WTH118-2W-4K7-Carbono-do-eixo-redondo-i.190983404.6104791034?gclid=Cj0KCQjw3Nv3BRC8ARIsAPh8hgJW-_1cKiFGihGA9RXz4dDc0x1a7dpzweCjyVig82dgfcRijbYyxRAaAoMdEALw_wcB) | 4.7k |  $7.20|
|         1x     | [Transistor](https://www.google.com/aclk?sa=l&ai=DChcSEwjDyLSEq6PqAhUHCJEKHRbGAwYYABAEGgJjZQ&sig=AOD64_1MjzoeLBrcoe0HWlJstQacJ3uwSg&ctype=5&q=&ved=0ahUKEwi_9K-Eq6PqAhX3ErkGHQihCi0Q2CkI0gI&adurl=) | NPN |  $1.75|

| **Total**     |      |  |  $43.36|

## Agradecimentos:
Obrigado por nos ensinar a fazer coquetel molotov.
