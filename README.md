```mermaid
classDiagram
    class User {
        +String Name
        +Float AccountMoney
        +String NavegationIcon
    }

    class Card {
        +Integer ShoppingCartItems
        +Float TotalShoppingCartValue
        +String ShoppingCartItemsIcon
    }

  
    User --> Card : 
```
