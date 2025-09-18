# Meu-Desafio-AWS-CloudFormation

## Descrição
Este repositório documenta minha experiência no desafio de implementar uma infraestrutura automatizada usando AWS CloudFormation, como parte do curso na DIO. O objetivo foi criar uma stack (pilha) na AWS e aprender a automatizar recursos na nuvem.

## O que eu fiz
- Desenvolvi um template YAML ("meu-template.yaml") para criar uma instância EC2 (servidor virtual).
- Tentei criar stacks chamadas "TesteAWS2025" e "TesteAWS2025-v2" para testar a automação.
- Encontrei erros durante a criação das stacks (status "ROLLBACK_COMPLETE"), possivelmente devido a um ID de AMI inválido ou configuração incorreta.
- Documentei o processo com capturas de tela na pasta `/images`.

## Lições Aprendidas
- Aprendi que o AWS CloudFormation usa templates (YAML ou JSON) para automatizar a criação de recursos na nuvem.
- Descobri que é importante usar um ID de AMI válido e específico para a região (ex.: us-east-1).
- Entendi que erros como "CREATE_FAILED" requerem análise dos eventos para correção.
- Percebi a importância de renomear arquivos corretamente (ex.: .yaml ao invés de .yaml.txt) ao trabalhar com templates.

## Próximos Passos
- Corrigir o template com um ID de AMI válido (ex.: procurar um AMI como "ami-0c55b159cbfafe1f0" para Amazon Linux 2 em us-east-1).
- Tentar criar uma nova stack com o template ajustado.
- Explorar outros recursos AWS, como buckets S3, para praticar mais.

## Capturas de Tela
- Veja a pasta `/images` para prints das tentativas de criação das stacks e erros encontrados.

## Recursos Úteis
- [Documentação AWS CloudFormation](https://aws.amazon.com/cloudformation/)
- [Guia de Markdown do GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Data
- Concluído em: 18/09/2025
