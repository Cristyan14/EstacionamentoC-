# Sistema de Estacionamento - C#

Este é um sistema simples de estacionamento desenvolvido em C# que permite:

- Cadastrar veículos pelo número da placa.
- Remover veículos e calcular o valor a pagar baseado no tempo estacionado.
- Listar todos os veículos atualmente estacionados.

---

## Funcionalidades

- Entrada do preço inicial e preço por hora.
- Adicionar veículos ao estacionamento.
- Remover veículos com cálculo do valor total.
- Listar veículos estacionados.
- Interface simples via console.

---

## Como rodar

1. Certifique-se de ter o [.NET SDK](https://dotnet.microsoft.com/download) instalado.

2. Clone este repositório:

   ```bash
   git clone <url-do-seu-repositorio>
Navegue até a pasta do projeto:

bash
Copiar
Editar
cd DesafioC
Execute o projeto usando o .NET CLI:

bash
Copiar
Editar
dotnet run
Estrutura do projeto
Estacionamento.cs — classe que gerencia as operações do estacionamento.

Program.cs — código principal que controla o fluxo do programa e interação com o usuário.

DesafioC.csproj — arquivo de configuração do projeto.

Requisitos
.NET 5.0 ou superior (recomendo .NET 6 ou .NET 7)

Console para interação com o usuário.

Observações
Código estruturado com namespaces para facilitar manutenção.

Tratamento básico de entradas para evitar erros comuns.

Pode ser expandido para interface gráfica ou banco de dados.

yaml
Copiar
Editar
