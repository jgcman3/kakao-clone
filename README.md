
# kakao Desktop App Clone
 
```mermaid
---
title: Example Git diagram
---

gitgraph
    branch release
    checkout release
    commit id: "Prod Deploy"

    branch stage
    checkout stage
    commit id: "Stage Deploy"

    branch master
    checkout master
    commit id: "Dev Deploy"

    branch feature/login
    checkout feature/login
    commit id: "Feature Work"

    checkout master
    merge feature/login
    commit id: "Feature Merged"

    branch sprint/v1.2
    checkout sprint/v1.2
    commit id: "Sprint Start"

    branch sprint/v1.2--auth
    checkout sprint/v1.2-feature-auth
    commit id: "Sprint Feature"

    checkout sprint/v1.2
    merge sprint/v1.2-feature-auth
    commit id: "Sprint Feature Merged"

    checkout master
    merge sprint/v1.2
    commit id: "Spri
```
