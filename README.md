# cra-monorepo-demo
Monorepo example using create-react-app and common component library structure with yarn workspaces

### Directory structure
```
.
└── monorepo/
    ├── packages/
    │   ├── app/ (create-react-app website)
    │   │   ├── src/
    │   │   └── package.json
    │   ├── website/ (create-react-app website)
    │   │   ├── src/
    │   │   └── package.json
    │   └── common/ (shared component library)
    │       └── components
    │       └── package.json
    ├── package.json
    └── yarn.lock
```


