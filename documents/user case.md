erDiagram
    Entity ||--o{ cert : issue
    cert ||--|{ Person : ownedby
    cert }|..|{ WhomInterested : shareTo
    BlockChain }|--|{ cert : verify