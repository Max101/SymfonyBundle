Symfony Bundle 2.0
===

Example structuring: (more coming soon)

```
├── Access
│   ├── Console
│   │   └── CreatePostCommand.php
│   └── HTTP
│       ├── Admin
│       │   ├── AdminController.php
│       │   ├── Views
│       │   │   └── admin.html.twig
│       │   └── routing.yml
│       ├── AdminAPI
│       │   ├── AdminAPIController.php
│       │   └── routing.yml
│       └── Post
│           ├── PostController.php
│           ├── Views
│           │   └── post.html.twig
│           └── routing.yml
├── DependecyInjection
│   ├── Configuration.php
│   └── SymfonyExtension.php
├── Domain
│   ├── Config
│   ├── Entity
│   │   └── Post.php
│   ├── Manager
│   │   └── PostManager.php
│   ├── Repository
│   │   └── PostRepository.php
│   └── Service
│       └── Query
│           └── FetchPostsService.php
├── README.md
└── SymfonyBundle.php
```
