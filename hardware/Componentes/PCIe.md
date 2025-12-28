# PCI Express

#### É um padrão de barramentos que serve para conectar periféricos, como SDDs, à placa-mãe do computador. 

#### É possível encontrar outras refrências a ele, como "interface", "slot" ou "soquete". 

#### Criado em 1993 para substituir padrões ancestrais, como AGP, VESA e USB. Atualmente, é usada a quinta geração do padrão PCI Express, o PCI 5.0 estão disponíveis na Intel e na AMD. O PCI Express é gerido por uma empresa a PCI-SIG. Ela desenvolve, normaliza e padroniza o barramento para toda a indústria.

---

## O que é barramento?

Barramento é a interface física e lógica por onde um periférico se comunica com o restante do sistema. Por exemplo, supondo que seu PC tenha uma placa de vídeo dedicada, há enorme probabilidade de que ela esteja conectada em um slot PCIe. O barramento é usado também para outros tipos de placas e recursos, como placas de rede, de som, unidades SSD, placas de captura.

## A importância do PCIe

O PCIe é importante por várias razões. O PCIe, que começou em 2004 por iniciativa da Intel para substituir o PCI convencional e o AGP, padronizou a interface para consumidores e fabricantes. Antes a placa-mãe precisava ter vários espaços para vários tipos barramento, o PCIe sanou esse problema.

--- 

## Caminhos de comunicação 

A placa sem os chips e apêndices receb o nome de PCB, o termo é uma sigla para "plca de circuito impresso". Nessas placas existem listras que conectam os controladores e chips da placa. Essas linhas ligam o processador, o chipset e os slots PCIe da placa. Os slots podem ter, cada um deles, uma banda máxima definida pelo fabricante. Ou podem compartilhar a banda disponível, o que é mais comum. 

O PCI-Express suporta tecnicamente até uma largura de x32. No entanto, a maioria das placas-mãe do consumidor possui algumas dessas larguras de PCIe: x1, x2, x4, x8, x16.

Os números indicam as vias de comunicação e a quantidade de vias define a velocidade com que os dados são transferidos, assim como o tamanho físico do barramento. É por isso que a placa tem um PCIe minúsculo: ele opera em 1x.

Porém, sua placa-mãe também tem outros barramentos PCIe maiores. Digamos que sejam dois, e tanto como outro podem funcionar com 8x ou 16x, depende da demanda do periférico que ligar neles. 

A largura de banda para cada faixa PCIe 5.0 é de 4 GB/s. Ou seja, 4 GB/s por faixa significa que, se usar um dispositivo PCI-Express 5.0 x16, ele terá até 64GB/s de largura de banda disponível. 


<img width="683" height="375" alt="image" src="https://github.com/user-attachments/assets/6db760e5-36aa-435f-a940-2ad35888623c" />

---

## N~umero de caminhos influi no tamanho do slot

A disponibilidade de caminhos para conectar um slot ao restante da placa define a capacidade de transferência de dados do slot. O número de caminhos também define o tamaho físico do slot. O menor é x1, em seguida o x4 e os demais podem operar como x8 e x16, dependendo da configuração do sistema. 
Outro detalhe interessante é que, em geral, uma placa x1, x4 ou x8 pode funcionar perfeitamente em um slot x16, desde que receba alimentação de energia adequada. 

<img width="647" height="289" alt="image" src="https://github.com/user-attachments/assets/34715208-c34b-4f86-9d41-a9fd9b7d9c90" />

---

## Gerações da PCIe

* PCIE 1.0
* PCIE 2.0
* PCIE 3.0
* PCIE 4.0
* PCIE 5.0
* PCIE 6.0

Placas-mãe com suporte ao PCIe 5.0 já estão no mercado há alguns meses. As CPUs Core de 12
