
# Hello, I'm Thiago! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"> 

<br>

```csharp
using Thi4gobit;

public class AboutMe : Developer
{
    public string Name { get; set; } = "Thiago Bittencourt";
    public string Area { get; set; } = "Full Stack (70% back-end, 30% front-end)";
    public string Country { get; set; } = "Brazil";
    public string State { get; set; } = "Rio de Janeiro";
}
```

<br>

- ⚡ Bachelor of Electrical Engineering.
- 🎓 Graduate Degree in Building Information Modeling.
- 💻 Graduate Degree in Full Stack developer.
- 💡 Passionate about Technology, Development, Learning and Solve Problems.
- 🤝 Available to collaborate on innovative, disruptive projects and ideas.
- ❤️ When I'm not coding, you can find me studying, reading, doing exercise, playing Snes.
- ☕ I drink coffe when I'm coding or not.

<br>


# ⌨️ Languages



#### 🚀 Advanced / Daily Use
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dynamo](https://img.shields.io/badge/Dynamo-FFCE00?style=for-the-badge&logo=autodesk&logoColor=black)

#### 🛠️ Intermediate / Familiar With
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

#### 🛠️ Basic / Few times
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

<br>

# 📚 Libraries & Framework & Tools

#### 🚀 Advanced / Daily Use
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

#### 🛠️ Intermediate / Familiar With
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

#### 🛠️ Basic / Few times
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

<br>

### 🧱 BIM & Automation Tools

![Revit API](https://img.shields.io/badge/Revit_API-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Dynamo](https://img.shields.io/badge/Dynamo-FFCE00?style=for-the-badge&logo=autodesk&logoColor=black)
![IFC](https://img.shields.io/badge/IFC-00558C?style=for-the-badge&logo=buildingsmart&logoColor=white)






### 🧭 Arquitetura & Boas Práticas

<!-- Badges conceituais (cores curadas; não-oficiais) -->
![SOLID](https://img.shields.io/badge/SOLID-2E7D32?style=for-the-badge&logoColor=white)
![Arquitetura_em_Camadas](https://img.shields.io/badge/Arquitetura_em_Camadas-455A64?style=for-the-badge&logoColor=white)
![DDD](https://img.shields.io/badge/DDD-1565C0?style=for-the-badge&logoColor=white)
![CQRS](https://img.shields.io/badge/CQRS-6A1B9A?style=for-the-badge&logoColor=white)

#### 🧱 SOLID (resumo prático)
- **S**ingle Responsibility — cada classe com **um motivo** para mudar.  
- **O**pen/Closed — **extensível** sem precisar modificar o núcleo.  
- **L**iskov Substitution — heranças **substituíveis** sem quebrar contratos.  
- **I**nterface Segregation — interfaces **pequenas e específicas**.  
- **D**ependency Inversion — módulos de alto nível dependem de **abstrações**, não de detalhes.

#### 🏗️ Arquitetura em Camadas (clean layering)
Presentation (API/UI)
↓
Application (Use Cases, Orquestração)
↓
Domain (Entidades, Regras, Serviços de Domínio)
↓
Infrastructure (ORM, Repositórios, Mensageria, Files, HTTP)
- **Dependências sempre “para baixo”** (Presentation → … → Infrastructure).  
- **Domain** é o centro: **não** depende de nada externo.  
- **Application** coordena casos de uso e **não** contém regra de negócio.

#### 🧭 DDD (Domain-Driven Design)
- **Ubiquitous Language**: termos do negócio no **código e conversas**.  
- **Aggregates**: consistência por **raiz** (Aggregate Root).  
- **Entities/Value Objects**: identidade vs. imutáveis por valor.  
- **Domain Services**: regras que **não cabem** numa entidade só.  
- **Repositories**: **persistência** por agregado, atrás de **interfaces**.  
- **Bounded Contexts**: limites claros; integração por **contracts/events**.

#### 🔀 CQRS (Command Query Responsibility Segregation)
- **Commands** (escrita): mudam estado; **não retornam** dados ricos (apenas status/ID).  
- **Queries** (leitura): otimizadas para **consulta** (DTOs/view models), **sem efeitos colaterais**.  
- Pode (ou não) usar **Event Sourcing**; frequentemente combina com **mensageria** (ex.: RabbitMQ).

#### ⚙️ Esqueleto de projeto (exemplo)
/src
/Presentation (Controllers, Endpoints, DTOs de I/O)
/Application (UseCases, Handlers, DTOs de App, Ports)
/Domain (Entities, ValueObjects, Services, Regras)
/Infrastructure (EF Core, Repos, Mensageria, Files, Adapters)
/CrossCutting (DI, Logging, Config, Validators)

#### ✅ Regras de ouro
- **Domain sem dependências** de frameworks.  
- **Interfaces no Domain/Application**, implementações na **Infrastructure**.  
- **DI** no *composition root* (Presentation).  
- **Handlers**: `CommandHandler` (escrita) e `QueryHandler` (leitura).  
- **Validação** próxima ao **limite** (DTOs) e **invariantes** dentro do **Domain**.

