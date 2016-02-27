Symfony Bundle 2.0
===

Example structuring: (more coming soon)

```
├── Access
│   ├── Console
│   │   └── CreateAdCommand.php
│   └── HTTP
│       ├── Ad
│       │   ├── AdController.php
│       │   ├── Views
│       │   │   └── post.html.twig
│       │   └── routing.yml
│       ├── Admin
│       │   ├── AdminController.php
│       │   ├── Views
│       │   │   └── admin.html.twig
│       │   └── routing.yml
│       ├── AdminAPI
│       │   ├── AdminAPIController.php
│       │   └── routing.yml
│       └── routing.yml
├── DependecyInjection
│   ├── Configuration.php
│   └── SymfonyExtension.php
├── Domain
│   ├── Config
│   ├── Entity
│   │   └── Ad.php
│   ├── Manager
│   │   └── PostManager.php
│   ├── Repository
│   │   └── PostRepository.php
│   └── Service
│       ├── Adapter
│       │   └── MandrillEmailAdapterService.php
│       ├── Command
│       │   └── SendToFriendAdCommandService.php
│       ├── Decorator
│       │   └── AdDecoratorQueryService.php
│       ├── Facade
│       │   └── AdManipulatorFacadeService.php
│       ├── Query
│       │   └── FetchAdsQueryService.php
│       └── Strategy
│           └── BrandUrlGeneratorStrategy.php
├── README.md
└── SymfonyBundle.php
```
