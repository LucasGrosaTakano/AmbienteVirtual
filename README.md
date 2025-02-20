# Ambiente Virtual Educacional

## Introdução ✓
Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. A atividade integra conceitos de Sistemas Operacionais, Redes de Computadores, Levantamento de Requisitos e Lógica de Programação. Nele, você pesquisará componentes para a montagem de um computador com custo máximo de R$5.000,00, e será configurado uma máquina virtual e instalado uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

## Levantamento de Requisitos ✓

- Requisitos Funcionais: O computador construído comporta facilmente os softwares (MySQL, Node.js e Python) requisitados para o uso educacional (banco de dados, desenvolvimento web e programação). Além de ser estável para o desenvolvimento e testes.

- Requisitos Não-Funcionais: O computador físico está dentro do limite de R$5.000,00 proposto, com o financeiro usado eficientemente, além de comportar e rodar as tarefas requisitadas.

### Requisitos para o Computador Físico ✓
- ~Processador (*CPU*)~ ✓
- ~Memória RAM~ ✓
- ~Armazenamento~ ✓
- ~Placa-mãe~ ✓
- ~Fonte de Alimentação~ ✓
- ~Teclado~ 
- ~Mouse~ 
- ~Monitor~ ✓
- ~Outros (placa de vídeo, cooler do processador)~ ✓
- **Orçamento Máximo:** ~R$ 5.000,00~ ✓

## Orçamento ✓

**Geral**: [PC Completo](https://meupc.net/build/bb3rq9)

- **Processador**: [AMD Ryzen 5 4500 3.6 GHz 6-Core](https://meupc.net/link/Kabum/Fs6rE3)

- **Memória RAM**: [Kingston Fury Beast (Preto) 16 GB (2x8GB)](https://meupc.net/peca/64gcGS/memoria-kingston-fury-beast-kf432c16bbk216)

- **Armazenamento**: [Kingston SSD A400 480 GB 2.5"](https://meupc.net/peca/kwi558/ssd-kingston-a400-a400480gb)

- **Placa-mãe**: [Asus TUF Gaming A520M-Plus Micro ATX AM4](https://meupc.net/peca/UMx2r9/placa-mae-asus-tuf-gaming-a520m-plus)

- **Fonte**: [Gamemax 600W 600 W Certificado 80+ White  ATX12V](https://meupc.net/peca/cU63BA/fonte-gamemax-600w)

- **Teclado**: [Redragon Kumara](https://meupc.net/peca/AB2fS8/teclado-redragon-kumara-k552)

- **Mouse**: [Redragon Cobra Chroma M711 Com fio](https://meupc.net/peca/jwq68q/mouse-redragon-cobra-chroma-m711)

- **Monitor**: [Monitor  AOC 24G2E1 23.8″ 1920 x 1080 100 Hz](https://meupc.net/peca/Ho28is/monitor-aoc-24g2e1)

- **Outros**:

  - **Placa de vídeo**: [MSI GeForce GTX 1650 4 GB VENTUS XS](https://meupc.net/peca/bxq9r8/placa-video-msi-geforce-gtx-1650-geforcegtx16504gb)

  - **Gabinete**: [Rise Mode Galaxy Glass M Mini (Preto) MicroATX Mini Tower](https://meupc.net/peca/baF42G/gabinete-rise-mode-galaxy-glass-m-mini-rmgaggmnfb)

  - **Cooler do Processador**: [Rise Mode Gamer G800 Hidráulico](https://meupc.net/peca/PX3X42/cooler-processador-rise-mode-gamer-g800)

  - **Mousepad**: [Havit HV-MP830](https://meupc.net/peca/qWqF98/mousepad-havit-hv-mp830-hvmp830)


Total no cartão: **R$4.873,55**

Total no boleto **R$4.249,62**

## Escolha do Sistema Operacional ✓

Utilizaremos o sistema operacional Linux, com sua distribuição alternativa Ubuntu devido a suas qualidades. Este sistema operacional fornece uma comunidade muito acolhedora, que possui fóruns e tutoriais para soluções de problemas, permitindo que o uso educacional seja mais efetivo para o desenvolvimento das habilidades dos alunos.

![UBUNTU](https://s2.glbimg.com/AnXNMtY3VON9i-ZO89UgGFg1X2g=/288x0/s.glbimg.com/jo/g1/f/original/2016/07/18/ubuntulogo.png)

## Máquina Virtual (VM Virtual Box)

### Manual de Instalação

### Requisitos para a Máquina Virtual
- **Processador (CPU):** ???
- **Memória RAM:** É necessário ter 4GB RAM no mínimo para o programa não ficar lento.
- **Armazenamento:** 10 GB de HD
- **Rede:** Configuração via NAT para acesso à internet, pois iremos necessitar que outro dispositivo se conecte à rede e sem necessidade de configurar a internet.


### Manual de Instalação do Linux no VirtualBox

#### Pré-requisitos

- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

### Passo a Passo

#### 1. Instalação do VirtualBox
- **VirtualBox:** Baixe e instale a versão mais recente do (VirtualBox[(https://www.virtualbox.org/]
Instruções para instalação do virtualbox:

1° Clique no link proposto acima

2° Pressione o botão de download para iniciar a instalação
3° Escolha a versão Linux do VirtualBox (Linux distributions)

4° Escolha a distribuição Linux da Ubuntu, versão 24.10 (a mais recente)



#### 2. Criação da Máquina Virtual
1. **Clique em "Novo":**
   - **Nome:** 
   - **Tipo:**
   - **Versão:** 

2. **Configuração de Memória:**
   - ...

3. **Criação do Disco Rígido Virtual:**
   - ......
   - ......
   - ......

#### 3. Configuração de Rede
- Selecione a máquina virtual criada e clique em "Configurações".
- ......
- ......

#### 4. Configuração do Disco de Instalação
- .......
- .......

#### 5. Iniciando a Instalação do Ubuntu
1. **Inicie a Máquina Virtual:**
   - ...........

2. **Instalação Passo a Passo:**
   - ......
   - ......
   - Se solicitado, conecte à internet para atualizações (opcional).

#### 6. Pós-Instalação e Testes
- Após a instalação, a máquina virtual reiniciará.
- Faça login com as credenciais criadas.
- Abra o terminal e verifique a instalação dos softwares executando os seguintes comandos:
  ```bash
  mysql --version
  node -v
  python3 --version

https://meupc.net/build/zgq48C
Preço : 3.639,05
Total no boleto: 3.265,99
