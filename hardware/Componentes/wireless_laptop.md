# Redes sem Fio Laptop 

## Bluetooth

A especificação do bluetooth é descrita pelo padrão 802.15.1 pela IEEE. Os dispositivos Bluetooth podem lidar com voz, música, vídeos e dados. 

A distância de Rede de Área Pessoal Bluetooth é limitada pela quantidade de energia usada pelos dispositivos na PAN. Os dispositivos Bluetooth foram divididos em três classes. A rede Bluetooth mais comum é a classe 2, que tem um alcance de aproximadamente 33 pés.

### Classificações do Bluetooth

| Classe   | Potência Máxima Permitida (mW) | Distância Aproximada        |
|---------|--------------------------------|-----------------------------|
| Classe 1 | 100 mW                         | ~330 pés (100 m)            |
| Classe 2 | 2,5 mW                         | ~33 pés (10 m)              |
| Classe 3 | 1 mW                           | ~3 pés (1 m)                |

Cinco especificações de tecnologia de Bluetooth são capazes de diferentes taxas de transferência, intervalos e consumo de energia.

| Especificação | Versão | Taxa de Transferência de Dados |
| --------------|--------|--------------------------------|
| 1.0     | v1.2       | 3Mb/s                            |
| 2.0     | v2.0 + EDR | 3Mb/s                            |
| 3.0     | v3.0 + HS | 24Mb/s                            |
| 4.0     | v4.0 + LE | 1Mb/s                             |
| 5.0     | v5.0 + LE | 125 KB/s. 500KB/s, 1 MB/s, 2 MB/s |

Cada versão subsequente oferece recursos melhorados. Ex: as versões de 1 a 3 são tecnologias mais antigas com recursos limitados e alto consumo de energia. Versões posteriores, como a versão 4 e 5, sãoo direcionadas a dispositivos como energia limitada e não precisam de alta taxa de transferência de dados. Além disso, a versão 5 tem quatro taxas de dados diferentes para acomodar uma variedade de intervalos de transmissão.

Medidas de segurança estão incluídas no padrão Bluetooth. A primeira vez que um dispositivo Bluwtooth se conecta, o dispositivo é autenticado usando um PIN. Isso é conhecido como emparelhamento. O Bluetooth suporta criptografia de 128 bits e autenticação por PIN.

## Conexões de Laptop Bluetooth

O Windows ativa as conexões com dispositivos Bluetooth por padrão. Se a conexão não estiver ativa, procure um interruptor na parte frontal ou lateral do laptop. Alguns laptops podem ter uma tecla de função especial no teclado para ativar a conexão. Se um laptop não possuir o recurso da tecnologia Bluetooth que plugue em uma porta USB. 

Antes de instalar e configurar um dispositivo, verifique se o Bluetooth está ativado na BIOS. Ligue o dispositivo e deixe-o detectável. 

### Conectividade Bluetooth no Windows 10 
O conteúdo explica, de forma prática, como ativar, configurar e utilizar a conectividade Bluetooth no Windows 10 para conectar dispositivos externos, como fones de ouvido sem fio.

Inicialmente, é apresentado que existem **três maneiras principais** de acessar as configurações de Bluetooth no sistema operacional:

- **Central de Ações**: localizada no canto inferior direito da tela, permite ligar ou desligar o Bluetooth rapidamente e acessar diretamente as configurações.
- **Painel de Controle**: por meio do caminho *Hardware e Som* → *Adicionar um dispositivo*, possibilita localizar e conectar dispositivos Bluetooth.
- **Configurações do Windows**: acessando *Iniciar* → *Configurações* → *Dispositivos*, onde ficam centralizadas as opções de Bluetooth.

Independentemente do caminho escolhido, todos levam às configurações de Bluetooth, onde é possível gerenciar dispositivos já conectados ou adicionar novos.

Para realizar a conexão, o dispositivo Bluetooth (no exemplo, um fone de ouvido) precisa estar **ligado e em modo de emparelhamento**. Esse modo varia conforme o modelo do dispositivo e geralmente é ativado ao pressionar e segurar o botão de energia até que uma luz indicadora pisque, sinalizando que o dispositivo está pronto para ser detectado.

Com o dispositivo em modo de pareamento, o usuário deve clicar em **Adicionar Bluetooth ou outro dispositivo**, selecionar a opção **Bluetooth** e aguardar a busca por dispositivos disponíveis. Quando o dispositivo desejado aparecer na lista, basta selecioná-lo para iniciar o emparelhamento.

Após a conclusão do processo, o sistema confirma que o dispositivo está pronto para uso, permitindo a reprodução de áudio sem fio para voz e música. A conexão pode ser verificada pela Central de Ações, onde aparece o nome do dispositivo conectado.

Por fim, o conteúdo destaca que o Bluetooth pode ser desligado quando não estiver em uso, encerrando a conexão. Em utilizações futuras, caso o Bluetooth esteja ativado e o dispositivo esteja próximo, a reconexão pode ocorrer automaticamente, sem a necessidade de repetir todo o processo de pareamento.

---

## WAN WI-FI

Os laptops com recursos WAN por celular integrados não exigem instalação de software e nem acessórios ou antenas adicionais. Ao iniciar o laptop, os recursos de WAN integrados estarão prontos para uso. Se a conexão não estiver ativa, procure um interruptor na parte frontal ou lateral do laptop. Alguns laptops podem ter uma tecla de função especial no teclado para ativar a conexão. 

Muito telefones celulares oferecem a capacidade de conectar outros dispositivos. Essa conexão, conhecida como amarração, pode ser feita usando WI-FI, Bluetooth ou usando um cabo USB. Depois que um dispositivo é conectado, ele pode usar a conexão celular do telefone para acessar a Internet. Quando um celular permite que os dispositivos WI-FI se conectem e usem a rede de dados móveis, isso é chamado de hotspot. Pode-se também acessar uma rede celular usando um dispositivo de ponto de acesso celular.

Há também adaptadores sem fio mini PCIe e M. 2 para laptops que podem fornecer uma combinação de conectividade Wi-Fi, Bluetooth exigirão a instalação de um novo kit de antena, que tem fios que geralmente são roteador em torno da tela na tampa do laptop. Ao instalar uma placa de adaptador com funcionalidaded de celular, um SIM também precisará ser inserido.

---

## Wi-Fi

Os laptops normalmente acessam a Internet utilizando adaptadores sem fio. Os adaptadores sem fio podem ser embutidos ou conectados ao laptop por uma porta de expansão. Três principais tipos de adaptadores sem fio em laptops.

### Tipos de Adaptadores Sem Fio

| Tipo | Descrição | Exemplo |
| ---- | --------- | ------- |
| Mini-PCI| As placas Mini-PCI possuem 124 pinos e são capazes de padrões de conexão LAN sem Fio 802.11a, 802.11b e 802.11g. |  <img width="206" height="189" alt="image" src="https://github.com/user-attachments/assets/5f4969b8-511b-4dc9-bac8-77b1ee836aa8" /> |
| Mini-PCIe | As placas Mini-PCIe têm 54 pinos e suportam os mesmos padrões que a Mini-PCI, com a adição dos padrões de LAN sem fio 802.11n e 802.11ac. | <img width="146" height="126" alt="image" src="https://github.com/user-attachments/assets/b952d9e8-2e6e-4ca4-b411-3a4f54a1836b" /> |
| PCI Express Micro | Micro PCI Express - Normalmente, são encontrados em laptops mais novos e menores, como ultrabooks, pois têm metade do tamanho dos cartões Mini PCIe. Os cartões Micro PCI Express têm 54 pinos e suportam os mesmos padrões dos Mini PCIe. | <img width="91" height="153" alt="image" src="https://github.com/user-attachments/assets/96f95e0c-bdc1-4b49-bd4f-fb076505dd8e" /> |

---

## Conexão de um Laptop a uma Rede Sem Fio (Wi-Fi) no Windows

O conteúdo explica como conectar um laptop a uma rede sem fio no Windows, apresentando diferentes caminhos para acessar as opções de rede e realizar a conexão de forma segura.

Inicialmente, são mostradas **três maneiras principais** de acessar as configurações de rede sem fio:

- Pelo **ícone de rede Wi-Fi** no canto inferior direito da tela, que indica se o computador está desconectado e mostra as redes disponíveis.
- Pelo **menu Iniciar**, pesquisando e acessando o **Painel de Controle**.
- Clicando com o **botão direito no menu Iniciar** e acessando diretamente as **Conexões de Rede**.

No exemplo apresentado, é utilizado o caminho mais longo, começando pelo **Painel de Controle**. Dentro dele, o usuário acessa a opção **Rede e Internet**, onde estão disponíveis a **Central de Rede e Compartilhamento** e a opção **Conectar a uma rede**.

Ao clicar em **Conectar a uma rede**, o sistema exibe todas as redes sem fio disponíveis nas proximidades. O usuário então escolhe a rede desejada com base na intensidade do sinal e clica em **Conectar**.

Durante o processo, o Windows permite escolher se a conexão será feita **automaticamente** sempre que a rede estiver disponível ou se será necessário conectar manualmente a cada vez. No caso apresentado, a opção de conexão automática é desmarcada, optando pela conexão manual.

Em seguida, é solicitada a **chave de segurança** da rede Wi-Fi. Após inserir a senha correta, o sistema faz uma pergunta relacionada à **visibilidade do dispositivo na rede**, o que envolve compartilhamento de arquivos e configurações de firewall.

Como se trata de uma **rede de convidados**, a opção escolhida é **não tornar o dispositivo detectável** por outros computadores da rede, aumentando a segurança.

Após essas etapas, a conexão é concluída com sucesso, indicando que o computador está **conectado e seguro**, permitindo o acesso normal à internet e à navegação.

--



