# Métricas em Dotnet

## Criando uma Métrica Personalizada
### Criando Console Application
Rodar o comando na pasta desejada
`dotnet new console`

### Adicionando Package para usar Métricas
Rodar o comando `dotnet add package System.Diagnostics.DiagnosticSource`

### Substituindo o código
Acessar o arquivo Program.cs dentro do projeto e substituir pelo código do tutorial. 

### Executando o código
Na raiz do projeto, rodar o comando `dotnet run`

### Configurando para Exibir as Métricas
Em outro terminal, na pasta do projeto rodar o comando `dotnet tool update -g dotnet-counters`

### Exibindo as Métricas
Após atualizar as dependencias com o dotnet-counters, rodar o comando `dotnet-counters monitor -n nome-do-programa-criado --counters HatCo.Store` 

PS: é necessário que o Console Application esteja rodando em outro terminal.

### Imagens da Execução Passo a Passo

#### Criando Console Application
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/5ce0be3a-1ea4-42bd-9c72-ff99e69bd546)

#### Adicionando Package para usar Métricas
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/f298d5a7-b5d9-4675-80c9-f9575281ea1b)

#### Substituindo o código
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/8b680cdc-6878-49ec-9bf3-b61da170fbc5)

#### Executando o código
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/adc83df2-c1f8-4fb9-a9c0-8b0c1777a770)

#### Configurando para Exibir as Métricas
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/68d1c343-e95d-4c71-a18b-9446650eb16a)

#### Exibindo as Métricas
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/36f1f5d5-79a6-47e5-9be2-5077bf6b1984)


## Medidor por meio de Injeção de Dependência
### Criando Web Application
Rodar o comando na pasta desejada
`dotnet new webapi`

### Adicionando Package para usar Métricas
Rodar o comando `dotnet add package System.Diagnostics.DiagnosticSource`

### Substituindo o código
Acessar o arquivo Program.cs dentro do projeto e substituir pelo código do tutorial adaptado. 

### Executando o código
Na raiz do projeto, rodar o comando `dotnet run`

### Exibindo Métricas
Rodar o comando `dotnet-counters monitor -n nome-do-programa-criado --counters HatCo.Store` 

### Imagens da Execução Passo a Passo
#### Criando Web Application
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/dffa68d8-53ad-4387-84b4-24a08bfb2245)

#### Substituindo o código
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/ca535da5-b88f-4789-a819-52e75eb3fbbf)

#### Executando o código
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/f527b5ca-42b2-49ea-b191-6abfef7719fc)

#### Exibindo Métricas
![image](https://github.com/FelipeSaadi/dotnet-metrics/assets/54749257/7633ed0c-454b-4446-8863-2ffbe41d9e99)




