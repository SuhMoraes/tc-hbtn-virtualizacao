## Apresente uma solução de como deve ser a criação de uma máquina virtual no Hyper-V.

<hr>

## Como criar máquina virtual com Windows.

Caso não venha habilitado o Hyper-V por padrão, segue as instruções abaixo:

[ Habilitando o Hyper-V ]
- Vá até o painel de controle.
- Depois vá para Programas e Recursos.
- Dentro de Programas e recursos, clique em 'Ativar ou esativar recusos do Windows'.
  Irá abrir uma janela 'Recursos do Windows'.
- Procure a pasta chamada 'Hyper-V' e clique para ser habilitada.
- E após de ser habilitado, clique 'OK', na janela 'Recursos do Windows'

Após hablitar  Hyper-V, aperecerá uma mensagem dizendo 'fazendo aplicações no sistema'.
Espere essas aplicações terminarem e o computador irá pedir para ser reiniciado.
Então apartir daí que iremos criar a nossa máquina virtual.


Com o acesso a internet, já configurado.

Digite na barra de tarefas 'Gerenciador do Hyper-V' e vamos configurar a máquina virtual.
 - Com botão direito do mouse clique em cima do nome do servidor destacado. -> Novo -> Máquina Virtual
 - Irá abrir a janela 'Antes de Começar'
 - Nessa tela você vai configurar Máquina Virtual:
   - Antes de Começar -> Clique Avançar
   - Especificar Nome e Local -> Coloque um nome -> Clique Avançar
   - Especificar Geração -> Clique Geração 2 -> Clique Avançar
   - Atribuir Memória -> Escolha a quantidade de memória da sua máquina virtual -> Clique no Checkbox 'Use a Memória Dinãmica para esta máquina' -> Clique Avançar
   - Configurar Rede -> Conecte a rede confiurada -> Clique Avançar
   - Conectar Disco Rígido -> Defina o tamanho de GB  -> Clique Avançar
   - Opções de Instalação -> Selecione a  ISO do SO para instalação  -> Clique Avançar
   - Concluindo o Assistente de Nova Máquina Virtual -> Concluir
   
Pronto a Máquina Virtual será configurada e instalada.

<hr>

## Demonstre de uma maneira simples porque essa prática é considerada um hipervisor do Tipo 2.
- Porque são executados como uma camada de software em um sistema operacional, como outros programas de computador. Por isso são hipervisor do tipo 2.

<hr>

## Realize uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo é de 2011, qual a configuração ideal para um servidor suportar três máquinas virtuais dos mesmos tipos apresentados no artigo:

_"Virtualização e Seus Benefícos para Empresas com Hyper-v; um Estudo de Caso na Indústria de Temperos Regina Ltda”_, nos dias de hoje.


Básico     | PowerEdge T150 Server
--------- | ------
Processador  | Intel® Xeon® E-2378 (2.6 GHz, 16M Cache, 8 núcleos/16 threads, Turbo 65W, 3200 MT/s)
Memória | 16GB DDR4 3200MHz (1X16GB, ECC, UDIMM, BCC)
Armazenamento | SSD de 480GB SATA RI ISE 6Gbps 512e 2.5" com 3.5" Brkt AG, Cabled
Sistema operacional| Windows Server® 2022 Standard, 16 núcleos


