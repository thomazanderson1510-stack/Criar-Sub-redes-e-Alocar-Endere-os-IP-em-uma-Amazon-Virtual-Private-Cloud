📌 Sobre o projeto

Neste laboratório, realizei a criação e configuração de uma Virtual Private Cloud (VPC) na Amazon Web Services (AWS), com o objetivo de compreender os conceitos de redes virtuais, endereçamento IPv4, sub-redes públicas e conectividade com a internet.

O ambiente foi desenvolvido utilizando o recurso VPC e muito mais, disponibilizado pela AWS.

🎯 Objetivos

Criar uma VPC personalizada.

Configurar um bloco CIDR IPv4.

Criar uma sub-rede pública.

Configurar um Internet Gateway.

Compreender o funcionamento das tabelas de rotas.

Entender como funciona a conectividade entre uma VPC e a internet.

🛠️ Serviços e recursos utilizados

Amazon VPC

Subnets (Sub-redes)

Internet Gateway (IGW)

Route Tables (Tabelas de rotas)

IPv4 e CIDR

⚙️ Configuração do ambiente

Recurso

Configuração

Nome da VPC

First-vpc

CIDR IPv4

192.168.0.0/18

IPv6

Desabilitado

Zona de disponibilidade

us-west-2a

Quantidade de sub-redes públicas

1

Quantidade de sub-redes privadas

0

CIDR da sub-rede pública

192.168.1.0/26

Internet Gateway

First-igw

🌐 Arquitetura implementada

A infraestrutura foi configurada com uma VPC contendo uma única sub-rede pública.

O Internet Gateway permite a comunicação da VPC com a internet, enquanto a tabela de rotas define o caminho que o tráfego deve seguir.

Fluxo de conectividade:

Internet → Internet Gateway → Tabela de rotas → Sub-rede pública

📸 Evidências do laboratório

1. VPC criada

<img width="1720" height="630" alt="image" src="https://github.com/user-attachments/assets/23d46bec-a63c-459e-b835-3f43d776ef39" />


2. Sub-rede pública

<img width="1717" height="675" alt="image" src="https://github.com/user-attachments/assets/19d7ef68-b04d-447a-9865-908d68d02de4" />


3. Internet Gateway
<img width="1700" height="308" alt="image" src="https://github.com/user-attachments/assets/9032d352-c9bc-4b0a-9635-93dee4a54437" />



4. Tabela de rotas

<img width="1647" height="439" alt="image" src="https://github.com/user-attachments/assets/5424ca0a-31d0-4166-ad4e-1187786c1537" />


5. Mapa de recursos da VPC

<img width="1241" height="182" alt="image" src="https://github.com/user-attachments/assets/f5e2463f-12fb-482a-97bf-8ca60e9f051b" />


📚 Conhecimentos adquiridos

Durante a execução deste laboratório, desenvolvi conhecimentos sobre:

Criação de redes virtuais na AWS.

Planejamento de endereçamento IPv4 utilizando CIDR.

Segmentação de redes por meio de sub-redes.

Diferenças entre sub-redes públicas e privadas.

Funcionamento do Internet Gateway.

Funcionamento das tabelas de rotas.

Fundamentos de arquitetura de redes em Cloud Computing.

🚀 Conclusão

Este laboratório foi importante para fortalecer meus conhecimentos em redes e infraestrutura na nuvem, compreendendo na prática como funciona a criação de uma rede virtual na AWS e sua comunicação com a internet.

Continuo desenvolvendo meus conhecimentos em AWS e Cloud Computing, buscando evoluir na área de infraestrutura e engenharia Cloud.
