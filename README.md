# Título do Projeto

Um parágrafo da descrição do projeto

## Começando

Essas instruções fornecerão uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste. Consulte [Deploy](#Deploy) para obter notas sobre como implantar o projeto em um sistema ativo.

1. Crie um fork do projeto
```sh
[NOME_REPOSITORIO](URL_REPOSITORIO)
```

2. Faça o clone do seu fork na sua máquina e acesse a raiz
```sh
git clone URL_DO_SEU_FORK
```

3. Adicione o remote do repositorio principal do projeto
```sh
git remote add upstream URL_REPOSITORIO
```

4. Crie uma branch para desenvolvimento a partir da branch que você precisa desenvolver ( Considere usar sempre a branch de produção )
```sh
git checkout -b development remotes/upstream/master
```

5. Use o comando abaixo para que os commits não sejam adicionados a branch do repositório principal e sim a branch do seu fork
```sh
git push -u origin development
```

### Pré-requisitos

O que você precisa para instalar o software e como instalá-lo

```
Dar exemplos
```

### Instalando

Uma série de exemplos passo a passo que mostram como obter um ambiente de desenvolvimento em execução

Diga qual será o passo

```
Dê o exemplo
```

E repita

```
até terminar
```

## Executando os testes

Explique como executar os testes automatizados para este sistema

### Divida em testes de ponta a ponta

Explique o que esses testes testam e por que

```
Dê um exemplo
```

### E testes de estilo de codificação

Explique o que esses testes testam e por que

```
Dê um exemplo
```

## Deploy

Adicione notas adicionais sobre como implantar isso em um sistema ativo

## Construído com

* [NOME_FRAMEWORK](URL/docs/) - Framework usado no projeto

## Contribuindo

Por favor leia [CONTRIBUTING.md](CONTRIBUTING.md) para obter detalhes sobre nosso código de conduta e o processo de envio de solicitações pull para nós.

## Versionamento

Para as versões disponíveis, consulte as [tags neste repositório](URL_TAGS_PROEJETO).

## Autores

Consulte também a lista de [colaboradores](URL_PROJETO_CONTRIBUIDORES) que participaram deste projeto.

## Licença

Este projeto está licenciado sob a licença NOME_LICENÇA - Consulte o arquivo [LICENSE.md](LICENSE.md) para obter detalhes
