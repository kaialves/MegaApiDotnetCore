<h1 align="center">
  <br />
  <img
    src="./_docs/assets/icon.png"
    alt="Mega Man Robots API Documentação"
    width="150"
  />
  <br />
  <b>Mega Man Robots API</b>
  <br />
  <sub
    ><sup><b>(MEGA-MAN-ROBOTS)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml"
  >
    <img
      src="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg"
      alt=""
    />
  </a>
  <a href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/felipeAguiarCode/MegaApiDotnetCore"
      alt="Latest Release"
    />
  </a>
</h1>

<p align="center">
 

# Documentando API's

O repositório MegaApiDotnetCore é uma API desenvolvida em .NET Core 3.1 que fornece dados em formato JSON sobre os chefes da série Mega Man. Este serviço backend utiliza diversas tecnologias modernas para gerenciamento de dados e manipulação de respostas da API.

  #**Tecnologias Utilizadas**
-.NET Core 3.1
*Entity Framework Core
+ASP.NET Core Web API
Injeção de Dependência
Banco de Dados SQL Server

  #**Requisitos**
Para executar a API, é necessário ter instalados:
.NET Core 3.1 SDK
SQL Server ou outro banco de dados compatível
Postman (opcional, para testar os endpoints)

#**Endpoints da API:**
GET /api/v1/robots: Retorna uma lista de todos os robôs.
```
    [
    {
        "id": 1,
        "name": "Cut Man",
        "game": "Mega Man 1",
        "weakness": "Super Arm"
    }
]
```
  
GET /api/v1/robots/{id}: Retorna detalhes de um robô específico pelo ID.

``` 
{
    "id": 2,
    "name": "Guts Man",
    "game": "Mega Man 1",
    "weakness": "Hyper Bomb"
}
```
  
POST /api/v1/robots: Endpoint para criar uma nova entrada de robô.
```
{
    "name": "Elec Man",
    "game": "Mega Man 1",
    "weakness": "Rolling Cutter"
}
```
  
