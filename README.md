# Terraform AWS Lab

Este repositório contém a infraestrutura como código (IaC) para provisionar recursos AWS em dois ambientes: `dev` e `prd`.

## Estrutura

- `modules/`: Módulos reutilizáveis para VPC, EC2 e Security Groups.
- `environments/`: Configurações específicas para cada ambiente.
- `scripts/`: Scripts auxiliares.

## Pré-requisitos

- Terraform >= 1.0
- AWS CLI configurado

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/USERNAME/terraform-aws-lab.git
   cd terraform-aws-lab
