/PetSoLive (Main Solution Folder)
├── /PetSoLive.Web (Presentation Layer)
│   ├── /Controllers
│   │   ├── HomeController.cs
│   │   ├── AccountController.cs
│   │   ├── AdoptionController.cs
│   │   ├── AssistanceController.cs
│   │   ├── PetController.cs  <-- Added PetController
│   ├── /Views
│   │   ├── /Home
│   │   │   ├── Index.cshtml
│   │   │   ├── About.cshtml
│   │   ├── /Account
│   │   │   ├── Login.cshtml
│   │   │   ├── Register.cshtml
│   │   ├── /Adoption
│   │   │   ├── Index.cshtml
│   │   │   ├── Details.cshtml
│   │   ├── /Pet   <-- Added Pet Folder
│   │   │   ├── Details.cshtml  <-- Added Pet Details View
│   │   ├── /Assistance
│   │       ├── Create.cshtml
│   │       ├── List.cshtml
│   ├── /wwwroot
│       ├── /css
│       ├── /js
│       ├── /images
│   ├── Program.cs
│   ├── Startup.cs
│   ├── appsettings.json
│   ├── appsettings.Development.json
├── /PetSoLive.Core (Core Layer)
│   ├── /Entities
│   │   ├── User.cs
│   │   ├── Pet.cs
│   │   ├── Announcement.cs
│   │   ├── Adoption.cs
│   ├── /Enums
│   │   ├── AdoptionStatus.cs
│   ├── /Interfaces
│   │   ├── IRepository.cs
│   │   ├── IAdoptionService.cs
│   │   ├── IAssistanceService.cs
│   │   ├── IUserService.cs
│   │   ├── IPetService.cs  <-- Added IPetService
│   ├── /DTOs
│   │   ├── UserDto.cs
│   │   ├── PetDto.cs
│   ├── /Helpers
│       ├── NotificationHelper.cs
├── /PetSoLive.Data (Data Access Layer)
│   ├── /Repositories
│   │   ├── UserRepository.cs
│   │   ├── PetRepository.cs
│   │   ├── AdoptionRepository.cs
│   │   ├── AnnouncementRepository.cs
│   ├── ApplicationDbContext.cs
│   ├── /Migrations
│       ├── [Migration Files]
├── /PetSoLive.Business (Business Logic Layer)
│   ├── /Services
│   │   ├── AdoptionService.cs
│   │   ├── AssistanceService.cs
│   │   ├── UserService.cs
│   │   ├── PetService.cs  <-- Added PetService
│   ├── BusinessRules.cs
├── /PetSoLive.Tests (Testing Layer)
│   ├── /UnitTests
│   │   ├── AdoptionServiceTests.cs
│   │   ├── AssistanceServiceTests.cs
│   ├── /IntegrationTests
│       ├── UserControllerTests.cs
│   ├── PetSoLive.Tests.csproj
├── PetSoLive.sln
