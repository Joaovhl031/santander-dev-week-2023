# santander-dev-week-2023
Java RESTful API criada para a santander dev week

## Diagrama de classes

```mermaid
classDiagram
  class User {
    -nome: string
    -account: Account
    -features: Feature[]
    -card: Card
    -news: News[]
  }
  class Account {
    -accountNumber: string
    -accountAgency: string
    -accountBalance: number
    -accountLimit: number
  }
  class Feature {
    -icon: string
    -description: string
  }
  class Card {
    -Number: string
    -Limit: number
  }
  class News {
    -icon: string
    -description: string
  }

  User --> Account
  User --> Feature
  User --> Card
  User --> News

```
