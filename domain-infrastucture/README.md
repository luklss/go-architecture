```
├── domain
│   ├── entities
│   │   ├── protocol.go
│   │   └── user.go
│   └── usecases
│       ├── admin-interactor.go
│       ├── admin-iteractor-impl.go
│       ├── dispatcher-interactor-impl.go
│       ├── dispatcher-interactor.go
│       ├── protocol-repo.go
│       ├── user-interactor-impl.go
│       ├── user-interactor.go
│       └── user-repo.go
└── infrastucture
    ├── graphql
    │   ├── admin-resolver.go
    │   ├── dispatcher-resolver.go
    │   └── user-resolver.go
    ├── repositories
    │   ├── protocol-repo-impl.go
    │   └── user-repo-impl.go
    └── rest-api
        └── v1
            ├── admin-controller.go
            ├── dispatcher-controller.go
            └── user-controller.go
```
