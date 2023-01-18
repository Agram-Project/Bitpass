### BTML: [10000](/BitPass_Types/10000_Resource)
- Nombre: Resources
    - _proto: Resource
    - btmlPart: 1
            
### BTML: [11000](/BitPass_Types/11000_Product)
- Nombre: Resource.Product
    - _proto: Resource
    - btmlPart: 1
        - _proto: Product
        - btmlPart: 1 

### BTML: [11100](/BitPass_Types/11100_Financial)
- Nombre: Resource.Product.Financial   
    - _proto: Resource
    - btmlPart: 1
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 

### BTML: [11110](/BitPass_Types/11110_Monetary)
- Nombre: Resource.Product.Financial.Monetary
    - _proto: Resource
    - btmlPart: 1
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 
                - _proto: Monetary
                - btmlPart: 1 

### BTML: [11111](/BitPass_Types/11111_Coin)
- Nombre: Resource.Product.Financial.Monetary.Coin
    - _proto: Resource
    - btmlPart: 1
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 
                - _proto: Monetary
                - btmlPart: 1 
                    - _proto: Coin
                    - btmlPart: 1
                    chain: testnet
                    symbol: BTC
                    decimals: 8
                    address_validation: tb1q 

### BTML: [12000](/BitPass_Types/12000_Concept)
- Nombre: Resource.Concept
    - _proto: Resource
    - btmlPart: 1
        - _proto: Concept
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""

### BTML: [12100](/BitPass_Types/12100_Certificate)
- Nombre: Resource.Concept.Certificate
    - _proto: Resource
    - btmlPart: 1
        - _proto: Concept 
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""
        - _proto: Certificate 
        - btmlPart: 1

### BTML: [12130](/BitPass_Types/12130_Ownership)
- Nombre: Resource.Concept.Certificate.Ownership
    - _proto: Resource
    - btmlPart: 1
        - _proto: Concept 
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""
        - _proto: Certificate 
        - btmlPart: 1
            - _proto: Ownership
            - btmlPart: 3

### BTML: [13000](/BitPass_Types/13000_Identity)
- Nombre: Resource.Identity
    - _proto: Resource
    - btmlPart: 1
        - _proto: Identity
        - btmlPart: 3

### BTML: [13300](/BitPass_Types/13300_Person)
- Nombre: Resource.Identity.Person
    - _proto: Resource
    - btmlPart: 1
        - _proto: Identity
        - btmlPart: 3
            - _proto: Person
            - btmlPart: 3

### BTML: [14000](/BitPass_Types/14000_Action)
- Nombre: Resource.Action
    - _proto: Resource
    - btmlPart: 1
        - _proto: Action
        - btmlPart: 4

### BTML: [50000](/BitPass_Types/50000_Index)
- Nombre: Index
    - _proto: Index
    - btmlPart: 5

### BTML: [51000](/BitPass_Types/51000_IndexProduct)
- Nombre: Index.Product
    - _proto: Resource
    - btmlPart: 5
        - _proto: Product
        - btmlPart: 1 

### BTML: [51100](/BitPass_Types/51100_IndexFinancial)
- Nombre: Index.Product.Financial   
    - _proto: Index
    - btmlPart: 5
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 

### BTML: [51110](/BitPass_Types/51110_IndexMonetary)
- Nombre: Index.Product.Financial.Monetary
    - _proto: Index
    - btmlPart: 5
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 
                - _proto: Monetary
                - btmlPart: 1 

### BTML: [51111](/BitPass_Types/51111_IndexCoin)
- Nombre: Resource.Product.Financial.Monetary.Coin
    - _proto: Index
    - btmlPart: 5
        - _proto: Product
        - btmlPart: 1 
            - _proto: Financial
            - btmlPart: 1 
                - _proto: Monetary
                - btmlPart: 1 
                    - _proto: Coin
                    - btmlPart: 1
                    chain: testnet
                    symbol: BTC
                    decimals: 8
                    address_validation: tb1q

### BTML: [52000](/BitPass_Types/52000_IndexcConcept)
- Nombre: Index.Concept
    - _proto: Index
    - btmlPart: 5
        - _proto: Concept
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""

### BTML: [52100](/BitPass_Types/52100_IndexCertificate)
- Nombre: Index.Concept.Certificate
    - _proto: Index
    - btmlPart: 5
        - _proto: Concept 
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""
        - _proto: Certificate 
        - btmlPart: 1

### BTML: [52130](/BitPass_Types/52130_IndexOwnership)
- Nombre: Index.Concept.Certificate.Ownership
    - _proto: Index
    - btmlPart: 1
        - _proto: Concept 
        - btmlPart: 2
        conceptName: "",
        conceptDescription: ""
        - _proto: Certificate 
        - btmlPart: 1
            - _proto: Ownership
            - btmlPart: 3

### BTML: [70000](/BitPass_Types/70000_Task)
- Nombre: Task
    - _proto: Task
    - btmlPart: 7
     



