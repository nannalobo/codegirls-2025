Módulo 1 – Introdução à AWS e Conceitos Básicos

## 📌 Resumo

Este módulo introdutório nos apresenta um resumo da história da Amazon, conceitos básicos da AWS, sua infraestrutura global, modelo de negócio, regiões, serviços gerenciados, como criar uma conta na AWS e também algumas práticas de segurança. 


## 📖 História da AWS 

Em 1994, a Amazon iniciava suas atividades como uma loja física de livros. 

A AmazonWeb Services (AWS) foi lançada em 2006, para oferecer serviços de infraestrutura. 

A  seta em seu logo faz alusão ao fato de ter produtos de A a Z. 


## 🌎 Infraestrutura Global

A infraestrutura global da AWS é considerada a mais segura, abrangente e confiável quando se fala de plataforma de nuvem. 

São mais de 200 serviços em todo o mundo. 

A AWS possui uma rede global de data centers, chamados de "Regions" e "Availability Zones"


## ⚙️ Conceitos Fundamentais

- Regions - áreas geográficas contendo várias Availability Zones
- Availability Zones - data centers independentes fisicamente, mas conectados logicamente, para garantir alta disponbilidade. Temos no mínimo 2 e no máximo 3. 

Posso ter 1 Region com no mínimo 2 Availabilty Zones, pois caso haja falha em uma, tem outra. 

A AWS abrange 105 zonas de disponibilidade em 33 regiões geográficas por todo o mundo, com planos para mais 12 zonas de disponibilidade e outras 4 regiões da AWS na Alemanha, Malásia, Nova Zelândia e Tailândia. 

Mapa: https://aws.amazon.com/pt/about-aws/global-infrastructure 

Em São Paulo temos uma location que provê para todo o Brasil. Temos de 2 a 3 data centers. 

Existem algumas Regions que são de governos, como por exemplo o Pentágono, que não são identificados onde ficam. 




## 🔒 Práticas de Segurança

- Criar conta root e guardar as informações
- Não compartilhar dados da conta
- Se atentar ao email com cobranças
- Autenticação MFA
- Estabelecer barreiras de proteção para permissões

Exemplo: Criar usuário IAM dev-bootcamp, dando acesso somente a S3 e EC2, e ativar autenticação MFA.

Para mais infos, ler a doc de User Guide com as best practices.


