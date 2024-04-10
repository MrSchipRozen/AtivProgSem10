# AtivProgSem10
# AtivProgSem10


# Automação do Terraform com GitHub Actions

## Visão Geral

Terraform é uma ferramenta de infraestrutura como código (IaC) que permite construir, alterar e versionar infraestrutura de maneira segura e eficiente. GitHub Actions é uma plataforma de CI/CD que automatiza seus pipelines de construção, teste e implantação. Integrar o Terraform com o GitHub Actions possibilita o gerenciamento automatizado da infraestrutura, garantindo que as mudanças na infraestrutura sejam consistentes e rastreáveis.

## Tecnologias Utilizadas

- **Terraform**: Ferramenta open-source de infraestrutura como código que permite definir e provisionar recursos de infraestrutura de forma declarativa.
- **GitHub Actions**: Serviço de automação de CI/CD integrado ao GitHub para executar workflows de build, teste e deployment diretamente a partir de um repositório GitHub.
- **Terraform Cloud**: Plataforma como serviço (PaaS) que estende o Terraform, proporcionando colaboração, governança e automação de workflows.
- **AWS (Amazon Web Services)**: Provedor de serviços na nuvem usado para hospedar a infraestrutura que será gerenciada pelo Terraform no tutorial.

## Conceitos Aprendidos

- **Terraform Cloud**: Uma versão hospedada do Terraform que oferece colaboração avançada, governança e recursos de automação.
- **GitHub Actions**: Permite a automação de workflows dentro do repositório do GitHub, incluindo a integração com Terraform para a implementação de infraestrutura.
- **Fluxo de trabalho do Terraform com GitHub Actions**: 
  1. **Planejamento**: Para cada commit em uma branch de pull request, um plano é gerado e pode ser revisado no Terraform Cloud.
  2. **Aplicação**: A configuração é aplicada quando a branch principal é atualizada.

## Configuração do Ambiente

- Criação de um workspace no Terraform Cloud.
- Adição de credenciais da AWS ao workspace do Terraform Cloud.
- Geração de um token de usuário API do Terraform Cloud.

<img width="949" alt="123" src="https://github.com/MrSchipRozen/AtivProgSem10/assets/99350292/df3d0d18-4e49-45fe-b6ad-60fc2e86653e">


## Workflows do GitHub Actions

- **Terraform Plan**: Define o workflow que executa `terraform plan`.
- **Terraform Apply**: Define o workflow que executa `terraform apply`.

# Prints em funcionamento


<img width="1800" alt="Screenshot 2024-04-10 at 11 34 37" src="https://github.com/MrSchipRozen/AtivProgSem10/assets/99350292/0db83c8f-ed90-4f72-83f3-2e621a9853f3">
