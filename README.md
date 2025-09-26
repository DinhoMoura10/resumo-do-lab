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

---

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

---

# 📦 Contas de Armazenamento do Azure

Uma Conta de Armazenamento do Azure é um recurso que fornece um namespace exclusivo no Azure para seus dados. Toda Conta de Armazenamento deve seguir três princípios fundamentais:

- **Nome globalmente EXCLUSIVO:** O nome da sua conta de armazenamento deve ser único em todo o Azure.
- **Acesso via Internet:** Fornece acesso aos dados de qualquer lugar do mundo através de HTTP ou HTTPS.
- **Configuração de Serviços e Redundância:** Permite determinar os serviços de armazenamento que você usará e as opções de redundância para garantir a durabilidade e a disponibilidade dos dados.

## Serviços de Armazenamento

### Blob do Azure
Recomendado para guardar dados massivos e não estruturados, como texto ou dados binários. É ideal para imagens, documentos, arquivos de mídia e logs.

### Disco do Azure
Fornece discos de bloco de alto desempenho e duráveis para máquinas virtuais (VMs), aplicativos e outros serviços.

### Fila do Azure
Um serviço para armazenar grandes quantidades de mensagens. Permite o armazenamento e a recuperação de mensagens de até 64KB, facilitando a comunicação assíncrona entre componentes de aplicativos.

### Arquivos do Azure
Configura compartilhamentos de arquivos de rede totalmente gerenciados e altamente disponíveis que podem ser acessados usando o protocolo padrão Server Message Block (SMB).

### Tabelas do Azure
Fornece uma opção de armazenamento NoSQL de chave/atributo para dados estruturados não relacionais. Possui um design sem esquema, tornando-o flexível para diversas aplicações.

---

## 🛠️ Ferramentas de Gerenciamento e Transferência de Dados

### AZCopy

**AZCopy** é uma ferramenta de linha de comando poderosa e de alto desempenho, projetada para copiar dados de e para o Armazenamento do Azure. É otimizada para transferências rápidas, especialmente para grandes volumes de dados.

#### Funcionalidade
- Copia arquivos ou diretórios inteiros de um computador local para o Azure Blob Storage, Azure File Storage e Azure Data Lake Storage.
- Copia dados entre diferentes contas de armazenamento do Azure.
- Sincroniza diretórios, copiando apenas os arquivos que foram alterados.

#### Melhor uso
- Migrações em larga escala.
- Uploads de arquivos muito grandes.
- Scripts de automação e tarefas de backup.
- Transferências de dados de alta velocidade.

#### Disponibilidade
- É uma ferramenta de linha de comando, acessada via Terminal (macOS/Linux) ou Prompt de Comando/PowerShell (Windows).
- É compatível com Windows, macOS e Linux.

### Gerenciador de Armazenamento do Azure (Azure Storage Explorer)

O **Gerenciador de Armazenamento do Azure** é um aplicativo de desktop com uma interface gráfica do usuário (GUI) que simplifica o gerenciamento de dados em seu armazenamento do Azure. Ele permite que você se conecte a várias contas de armazenamento e realize tarefas comuns de forma visual.

#### Funcionalidade
- Gerencia Blobs, Arquivos, Tabelas, Filas e Azure Cosmos DB.
- Cria, exclui, move e renomeia contêineres e diretórios.
- Faz o upload e download de arquivos com um simples arrastar e soltar.
- Permite a visualização e edição de metadados.
- Gerencia o controle de acesso (ACLs) para contêineres e blobs.

#### Melhor uso
- Tarefas de gerenciamento de armazenamento do dia a dia.
- Gerenciamento visual e intuitivo sem a necessidade de comandos.
- Explorar e visualizar o conteúdo do seu armazenamento.

#### Disponibilidade
- É um aplicativo de desktop independente.
- Compatível com Windows, macOS e Linux.

### Sincronização de Arquivos do Azure (Azure File Sync)

A **Sincronização de Arquivos do Azure** é um serviço que transforma seu servidor de arquivos local em um cache rápido de seu compartilhamento de arquivos do Azure, mantendo-o sempre sincronizado. Ele oferece o melhor dos dois mundos: a velocidade do acesso local e a escalabilidade e o backup da nuvem.

#### Funcionalidade
- **Sincronização bidirecional:** Mantém os arquivos do servidor local e do compartilhamento de arquivos do Azure sincronizados.
- **Tiering de nuvem (Cloud Tiering):** Libera espaço no disco local movendo os arquivos menos acessados para a nuvem, mantendo apenas um ponteiro (stub) no local. Quando um arquivo é acessado, ele é baixado automaticamente.
- **Múltiplos servidores:** Permite que você sincronize vários servidores locais com o mesmo compartilhamento de arquivos do Azure, criando um espaço de nome unificado.

#### Melhor uso
- Substituir servidores de arquivos locais caros e complexos.
- Consolidar compartilhamentos de arquivos de filiais em um único ponto central.
- Reduzir a necessidade de grandes volumes de armazenamento local.
- Centralizar backups de arquivos na nuvem.

#### Disponibilidade
- É um serviço do Azure que requer a instalação de um agente em um servidor Windows local.

---

## 🛡️ Segurança, Identidade e Conformidade no Azure

A segurança é um pilar fundamental no Azure. Abaixo estão alguns dos principais serviços e conceitos para proteger seus recursos.

### Microsoft Entra ID (Anteriormente Azure Active Directory)

O **Microsoft Entra ID** é o serviço de gerenciamento de identidade e acesso baseado em nuvem da Microsoft. Ele ajuda a garantir que apenas as pessoas certas tenham acesso aos recursos certos.

#### Conceitos Fundamentais

-   **Autenticação:** É o processo de verificar a identidade de uma pessoa ou serviço que tenta acessar um recurso. Ele solicita credenciais legítimas (como usuário/senha, biometria ou um token) para provar quem você é.
-   **Autorização:** Após a autenticação bem-sucedida, a autorização determina o nível de acesso que essa identidade tem. Ela define quais dados podem ser acessados e quais ações (leitura, escrita, exclusão) podem ser executadas.

#### Principais Funcionalidades

-   **Autenticação Multifator (MFA):** Adiciona uma camada crítica de segurança ao exigir dois ou mais fatores de autenticação para verificar a identidade de um usuário. Exemplos incluem algo que você sabe (senha), algo que você tem (código no celular) e algo que você é (biometria).
-   **Acesso Condicional (Conditional Access):** Permite criar políticas de acesso automatizadas. Ele utiliza sinais (como usuário, localização, dispositivo, aplicativo e risco em tempo real) para tomar decisões e aplicar políticas de segurança, como exigir MFA ou bloquear o acesso.
-   **Controle de Acesso Baseado em Função (RBAC):** Garante um gerenciamento de acesso de granularidade fina, aplicando o princípio do menor privilégio. Você atribui funções (como "Leitor", "Colaborador" ou "Proprietário") a usuários ou grupos, concedendo apenas as permissões necessárias para realizarem seu trabalho.

### Modelo de Segurança Confiança Zero (Zero Trust)

**Confiança Zero** é um modelo de segurança estratégico que não confia em nenhuma identidade, dentro ou fora da rede. Ele opera sob o princípio "nunca confie, sempre verifique". Seus três pilares são:

1.  **Verificar explicitamente:** Sempre autenticar e autorizar com base em todos os pontos de dados disponíveis.
2.  **Usar o acesso de privilégio mínimo:** Limitar o acesso do usuário com acesso just-in-time e just-enough-access (JIT/JEA).
3.  **Assumir a violação:** Minimizar o raio de alcance de danos e segmentar o acesso.

### Microsoft Defender para Nuvem (Microsoft Defender for Cloud)

O **Microsoft Defender para Nuvem** é uma solução de gerenciamento de postura de segurança (CSPM) e proteção de carga de trabalho na nuvem (CWPP). Ele fornece proteção unificada contra ameaças para cargas de trabalho no Azure, em ambientes locais e em outras nuvens (como AWS e GCP).

-   **Recomendações de Segurança:** Analisa continuamente seus recursos e fornece uma "pontuação de segurança" com recomendações práticas para corrigir vulnerabilidades.
-   **Detecção de Ameaças:** Utiliza análise avançada e inteligência contra ameaças para detectar e alertar sobre atividades maliciosas, como malware, acesso incomum e outras ameaças.
-   **Proteção Abrangente:** Protege VMs, bancos de dados, contêineres, armazenamento e outros serviços do Azure.

# [cite_start]Módulo 3: Gerenciamento e Governança de Custos no Azure [cite: 3]

[cite_start]Este documento resume os principais conceitos de gerenciamento de custos e governança no Microsoft Azure, com base nos tópicos da certificação AZ-900. [cite: 1]

## [cite_start]Fatores que Afetam os Custos [cite: 22, 25, 28, 31, 34, 37]

[cite_start]Entender os fatores que influenciam os custos é fundamental para uma gestão financeira eficiente na nuvem. [cite: 13]

* [cite_start]**1) Tipo de Recurso:** Os custos são específicos do recurso, portanto, o uso que um medidor rastreia e o número de medidores associados a um recurso dependem do tipo de recurso. [cite: 23]
* [cite_start]**2) Consumo:** Com um modelo pago conforme o uso, o consumo é um dos maiores geradores de custos. [cite: 26]
* [cite_start]**3) Manutenção:** Monitorar seu volume do Azure e manter seu ambiente pode ajudá-lo a identificar e reduzir os custos que não são necessários, como ao desligar máquinas virtuais subutilizadas. [cite: 29]
* [cite_start]**4) Área Geográfica:** O mesmo tipo de recurso pode custar valores diferentes dependendo da área geográfica, o que afeta os custos do Azure. [cite: 32]
* [cite_start]**5) Tráfego de Rede:** Embora algumas transferências de dados de entrada sejam gratuitas, o custo para dados de saída ou dados entre recursos do Azure é afetado por zonas de cobrança. [cite: 35]
* [cite_start]**6) Assinatura:** O tipo e a configuração da assinatura também podem afetar o custo. [cite: 38] [cite_start]Por exemplo, a avaliação gratuita permite explorar alguns recursos do Azure gratuitamente. [cite: 38]

## Ferramentas de Estimativa de Custos

O Azure oferece ferramentas para ajudar a prever e analisar os gastos.

### [cite_start]Calculadora de Preços [cite: 51, 54, 58]
[cite_start]A calculadora de preços é uma ferramenta que ajuda a estimar o custo dos produtos do Azure. [cite: 56] [cite_start]As principais opções de configuração incluem: [cite: 57]
* [cite_start]Região [cite: 60]
* [cite_start]Camada [cite: 61]
* [cite_start]Opções de cobrança [cite: 62]
* [cite_start]Opções de suporte [cite: 63]
* [cite_start]Programas e ofertas [cite: 64]

### [cite_start]Calculadora de Custo Total de Propriedade (TCO) [cite: 66, 70]
[cite_start]É uma ferramenta para estimar a economia de custos possível ao migrar para o Azure. [cite: 68] [cite_start]Um relatório compara os custos das infraestruturas locais com os custos de uso de produtos e serviços do Azure na nuvem. [cite: 69]

## [cite_start]Gerenciamento de Custos do Azure [cite: 75, 81]

[cite_start]O **Azure Cost Management** é uma ferramenta completa para monitorar e otimizar os custos na nuvem. [cite: 17] Suas funcionalidades incluem:
* [cite_start]**Relatórios de Cobrança:** Fornece relatórios de cobrança. [cite: 73]
* [cite_start]**Enriquecimento de Dados:** Permite o enriquecimento de dados para análise. [cite: 74]
* [cite_start]**Orçamentos:** Ajuda a definir um orçamento de gastos. [cite: 78]
* [cite_start]**Alertas:** Envia notificações quando o custo excede os limites definidos. [cite: 79]
* [cite_start]**Recomendações:** Oferece recomendações de custo. [cite: 80]

## [cite_start]Marcas (Tags) [cite: 83, 89]

As marcas são um componente essencial para a organização e governança de recursos.

* [cite_start]**Metadados:** Fornecem metadados aos recursos do Azure. [cite: 85]
* [cite_start]**Organização:** Permitem organizar os recursos em uma taxonomia de maneira lógica. [cite: 86]
* [cite_start]**Estrutura:** Consistem em um par nome-valor. [cite: 87]
* [cite_start]**Análise de Custos:** São muito úteis para reunir informações de cobrança. [cite: 88]


