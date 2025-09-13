# ☁️ Conceitos Fundamentais de Cloud Computing com Azure

Este documento resume os principais modelos de nuvem (Pública, Privada e Híbrida) e os modelos de despesas associados (CapEx e OpEx), conceitos essenciais para entender a computação em nuvem e os serviços oferecidos pela Microsoft Azure.

## 🌩️ Modelos de Nuvem

Existem três modelos principais de implantação de nuvem, cada um com suas próprias vantagens e desvantagens.

### Nuvem Pública (Public Cloud)

Neste modelo, os recursos de computação são de propriedade e operados por um provedor de nuvem terceirizado (como a Microsoft) e entregues pela internet. Vários clientes compartilham a mesma infraestrutura de hardware, mas seus dados e aplicações são isolados e seguros.

- **Vantagens:**
  - **Escalabilidade:** Recursos podem ser aumentados ou diminuídos conforme a demanda.
  - **Modelo de Pagamento (OpEx):** Pague apenas pelo que usar, sem necessidade de investimento inicial em hardware.
  - **Alta Disponibilidade e Confiabilidade:** Provedores garantem a manutenção e a disponibilidade da infraestrutura.

- **Desvantagens:**
  - **Menor Controle:** Menos controle sobre a infraestrutura de hardware e a segurança subjacente.
  - **Conformidade Regulatória:** Pode haver preocupações com a conformidade para setores com regulamentações rígidas.

### Nuvem Privada (Private Cloud)

A nuvem privada consiste em recursos de computação usados exclusivamente por uma única empresa ou organização. Ela pode estar localizada no data center local da própria organização ou ser hospedada por um provedor de serviços terceirizado.

- **Vantagens:**
  - **Maior Controle e Segurança:** Controle total sobre os dados e a infraestrutura.
  - **Conformidade:** Facilita a conformidade com regulamentações mais rígidas de segurança e privacidade.

- **Desvantagens:**
  - **Custos Elevados (CapEx):** Requer um investimento inicial significativo em hardware e infraestrutura.
  - **Gerenciamento Próprio:** A organização é responsável pelo gerenciamento, manutenção e atualizações.

### Nuvem Híbrida (Hybrid Cloud)

A nuvem híbrida combina uma nuvem privada com uma ou mais nuvens públicas, permitindo que dados e aplicações sejam compartilhados entre elas. Isso oferece às empresas maior flexibilidade e mais opções de implantação.

- **Vantagens:**
  - **Flexibilidade:** Permite manter dados sensíveis em uma nuvem privada enquanto aproveita a escalabilidade da nuvem pública para aplicações menos críticas.
  - **Otimização de Custos:** Equilibra os custos ao usar o modelo de nuvem mais apropriado para cada carga de trabalho.

- **Desvantagens:**
  - **Maior Complexidade:** Exige gerenciamento e integração mais complexos entre os diferentes ambientes.

---

## 💲 Modelos de Despesas

Entender a diferença entre CapEx e OpEx é fundamental para compreender os benefícios financeiros da computação em nuvem.

### CapEx (Capital Expenditure - Despesas de Capital)

Refere-se ao gasto inicial com a compra de ativos físicos, como servidores, roteadores e outra infraestrutura de TI.
- Gasto inicial em infraestrutura física.
- O valor do investimento se deprecia (reduz) com o tempo.

### OpEx (Operational Expenditure - Despesas Operacionais)

Refere-se às despesas contínuas para manter um negócio ou sistema funcionando. Na nuvem, isso se traduz no modelo de pagamento conforme o uso.
- Gasto com produtos e serviços conforme a necessidade (pay-as-you-go).
- A cobrança é imediata e recorrente (geralmente mensal).

---

## ⚙️ Principais Conceitos de Nuvem

Este documento descreve os principais conceitos relacionados à computação em nuvem, incluindo alta disponibilidade, escalabilidade e outros princípios essenciais.

### Alta Disponibilidade (HA) e SLAs

A **Alta Disponibilidade (HA)** se concentra em garantir o tempo de atividade máximo para aplicações e serviços, independentemente de interrupções ou eventos disruptivos. Um componente-chave da HA é o **Acordo de Nível de Serviço (SLA)**, que é um compromisso do provedor de nuvem em relação ao desempenho e à disponibilidade.

### Princípios Fundamentais da Nuvem

Aqui estão vários conceitos fundamentais que definem a infraestrutura de nuvem moderna:

- **Escalabilidade:** A capacidade de ajustar o tamanho e a capacidade da sua infraestrutura para atender à demanda. Com a escalabilidade da nuvem, você paga apenas pelos recursos que estão sendo usados.

- **Elasticidade:** Esta é uma forma de escalabilidade que se adapta automaticamente a mudanças no uso. Ela permite que os recursos aumentem ou diminuam sua capacidade automaticamente e em tempo real, sem intervenção humana, para lidar com as flutuações da demanda.

- **Confiabilidade:** A confiabilidade da nuvem se baseia em uma estratégia robusta de recuperação de desastres. Ela garante que não haverá perda de dados, mesmo que ocorra um evento catastrófico em um data center ou região específica.

- **Previsibilidade:** A previsibilidade da nuvem permite que você gerencie com confiança tanto o desempenho quanto o custo da sua infraestrutura. Isso inclui a previsão de necessidades de recursos e despesas para evitar surpresas.

- **Segurança:** Embora o provedor de nuvem ofereça uma ampla gama de ferramentas de segurança, a implementação e a gestão dessas ferramentas são de responsabilidade do cliente. Isso é frequentemente chamado de **modelo de responsabilidade compartilhada**.

- **Governança:** A governança da nuvem ajuda a manter o controle sobre seus recursos e garante que eles estejam em conformidade com as políticas da sua organização. Ela inclui a auditoria de recursos e, em alguns casos, a aplicação automática de patches e atualizações de software.

- **Gerenciabilidade:** A facilidade com que os recursos de nuvem podem ser gerenciados e administrados. Ela oferece a flexibilidade de organizar e controlar seu ambiente da maneira que melhor se adapte às suas necessidades e preferências.

---

## 👩‍💻 Como Criar Recursos no Portal do Azure

Antes de começar, certifique-se de que você tem uma conta do Azure. A criação de recursos no Azure geralmente segue um processo claro e intuitivo, mas é importante saber onde encontrar as opções certas.

### Passo 1: Criar um Grupo de Recursos

Um **Grupo de Recursos** é um contêiner lógico que agrupa recursos do Azure (como máquinas virtuais, redes e contas de armazenamento) para facilitar o gerenciamento, o monitoramento e a exclusão de todos eles como uma única entidade.

1.  Acesse o **portal do Azure** em [https://portal.azure.com](https://portal.azure.com) e faça login.
2.  Na página inicial, procure por **"Grupos de recursos"** na barra de pesquisa superior e selecione-o na lista de serviços.
3.  Clique em **"+ Criar"** no canto superior esquerdo da página.
4.  Na tela de criação, preencha os seguintes campos:
    - **Assinatura:** Escolha a sua assinatura.
    - **Grupo de recursos:** Digite um nome único e significativo para o seu grupo de recursos (ex: `meu-primeiro-rg`).
    - **Região:** Selecione a região do Azure onde o grupo de recursos será hospedado (ex: `Brazil South`).
5.  Clique em **"Revisar + criar"** e, depois, em **"Criar"**.

Seu grupo de recursos será criado em poucos segundos.

### Passo 2: Criar uma Rede Virtual (VNet)

Uma **Rede Virtual (VNet)** é a base da sua rede privada no Azure. Ela permite que os recursos do Azure (como as máquinas virtuais) se comuniquem de forma segura entre si, com a internet e com redes locais.

1.  Dentro do grupo de recursos que você acabou de criar, clique em **"+ Criar"** ou volte para a barra de pesquisa do portal e procure por **"Redes virtuais"**.
2.  Clique em **"+ Criar"**.
3.  Na tela de criação da VNet, preencha os seguintes campos:
    - **Assinatura:** Escolha a mesma assinatura que você usou para o grupo de recursos.
    - **Grupo de recursos:** Selecione o grupo de recursos que você criou no passo anterior (ex: `meu-primeiro-rg`).
    - **Nome:** Digite um nome para a sua VNet (ex: `minha-vnet`).
    - **Região:** Certifique-se de que a região é a mesma do seu grupo de recursos.
4.  Clique na guia **"Endereços IP"**. Aqui, você define o espaço de endereço da sua VNet. O Azure já preencherá um espaço padrão (ex: `10.0.0.0/16`). Você pode mantê-lo ou ajustá-lo conforme sua necessidade.
5.  Role a página para baixo até a seção de sub-redes e clique em **"Adicionar sub-rede"**.
6.  Preencha os dados da sub-rede:
    - **Nome da sub-rede:** `default`.
    - **Intervalo de endereço da sub-rede:** Mantenha o valor padrão (ex: `10.0.0.0/24`). Uma sub-rede é um segmento da sua VNet.
7.  Clique em **"Adicionar"**.
8.  Clique em **"Revisar + criar"** e, depois, em **"Criar"**.

Sua Rede Virtual, agora contida no grupo de recursos, está pronta para hospedar recursos como máquinas virtuais.

# 🚀 Guia para Criar uma Máquina Virtual (VM) no Azure

Este guia detalhado oferece um passo a passo para a criação de uma **Máquina Virtual (VM)** no Microsoft Azure, ideal para quem está começando. Siga as instruções para configurar seu servidor de forma rápida e eficiente.

---
## Criacao de maquina virtual 

### 1. Acesso ao Portal do Azure

1.  Acesse o portal do Azure em **https://portal.azure.com**.
2.  Faça login com sua conta.

### 2. Início da Criação da VM

1.  Na barra de pesquisa no topo do portal, digite `Máquinas Virtuais`.
2.  Clique no resultado e, em seguida, no botão **+ Criar**.
3.  Selecione **Máquina virtual do Azure**.

### 3. Configurações Básicas da VM

Preencha os seguintes campos no painel "Básico":

-   **Assinatura**: Selecione sua assinatura do Azure.
-   **Grupo de recursos**: Crie um novo grupo para seus recursos. Clique em **Criar novo** e insira um nome descritivo (ex: `rg-meu-projeto`).
-   **Nome da máquina virtual**: Dê um nome único e fácil de identificar para sua VM (ex: `servidor-web-01`).
-   **Região**: Escolha a localização do datacenter. Selecione a região mais próxima de seus usuários para reduzir a latência.
-   **Imagem**: Selecione o sistema operacional que deseja utilizar (ex: `Ubuntu Server 20.04 LTS` ou `Windows Server 2022 Datacenter`).
-   **Tamanho**: Escolha o tamanho da VM com base nas suas necessidades de desempenho (vCPU e RAM).
-   **Conta do administrador**:
    -   Crie um **Nome de usuário**.
    -   Escolha o **Tipo de autenticação** (senha para Windows, chave SSH para Linux).

### 4. Configuração da Rede

Nesta etapa, você define as regras de entrada de tráfego para sua VM.

-   Em **Portas de entrada públicas**, selecione **Permitir portas selecionadas**.
-   Na lista suspensa **Selecionar portas de entrada comuns**, marque as portas necessárias para acesso:
    -   **SSH (22)**: Para acesso remoto via terminal a VMs Linux.
    -   **RDP (3389)**: Para acesso remoto a VMs Windows via Área de Trabalho Remota.

### 5. Revisão e Implantação

1.  Clique em **Revisar + criar**.
2.  Verifique o resumo das configurações e o custo mensal estimado.
3.  Se tudo estiver correto, clique em **Criar** para iniciar o processo de implantação.

