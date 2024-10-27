# Ferramentas de Implantação na Azure
Neste repositório, estarei documentando o passo a passo da execução do laboratório "Ferramentas de Implantação na Azure", fornecido pela Microsoft Learn, e a minha experiência de aprendizado com o laboratório.

## Objetivo do laborátorio
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui e escreva um resumo do que você aprendeu durante o desenvolvimento do lab. Para concluir este desafio, você deverá entregar o link de um repositório no GitHub contendo um arquivo README com o seu resumo. 

*******
### Índice  
  - [Conhecendo o Azure ARC](#conhecendo-o-azure-arc)
  - [Conhecendo o Azure ARM](#conhecendo-o-azure-arm)
  - [Conhecendo o Bicep](#conhecendo-o-bicep)
  - [Conclusão](#conclusão)

*******

## Conhecendo o Azure ARC

1 - Azure ARC é uma plataforma que permite o gerenciamento centralizado de recursos em ambientes híbridos e multicloud, estendendo os serviços do Azure para qualquer infraestrutura. Com ele, é possível gerenciar servidores, clusters Kubernetes e bancos de dados que estão fora do Azure, utilizando as mesmas ferramentas de monitoramento, políticas e segurança.

**Principais ferramentas e recursos do Azure ARC:**

    Gerenciamento de servidores: Habilita a gestão de servidores físicos e máquinas virtuais fora do Azure.
    Gerenciamento de Kubernetes: Simplifica a orquestração de clusters Kubernetes locais e em nuvens externas.
    Gerenciamento de dados: Oferece serviços como o Azure SQL Managed Instance em ambientes on-premise.


![ ](https://imgur.com/YuC2NZo.png)


## Conhecendo o Azure ARM

2 - Azure Resource Manager (ARM) é a camada de gerenciamento que permite a administração e automação de recursos no Azure. Com o ARM, os usuários podem organizar, provisionar e monitorar serviços através de templates declarativos e consistentes.

**Principais ferramentas e recursos do ARM:**

    Templates ARM: Arquivos JSON que permitem a implementação automatizada e repetível de recursos no Azure.
    Grupos de recursos: Facilita a organização e gerenciamento de múltiplos serviços de maneira coesa.
    Role-Based Access Control (RBAC): Controle granular de permissões sobre os recursos.
    Tags: Etiquetas para categorizar e identificar recursos de forma eficiente.


![ ](https://imgur.com/P0HsWJW.png)

## Conhecendo o Bicep

3 - Bicep é uma linguagem declarativa de código-fonte aberto projetada para simplificar a criação de templates de infraestrutura como código (IaC) no Azure. Ele serve como uma alternativa mais simples e concisa aos arquivos JSON utilizados nos Azure Resource Manager (ARM) Templates, facilitando o provisionamento de recursos na nuvem.

![ ](https://imgur.com/dSwJ8vy.png)

## Conclusão
Esse laboratório serviu para mostrar com detalhes as ferramentas de implantação do Azure.

### Referências
* ######