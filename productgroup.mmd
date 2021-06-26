sequenceDiagram
    participant Initiator
    participant Approver
    participant ProductGroupAPI
    participant ProductSoR
    participant ProductSoE
    participant EnterpriseEventHub
    Initiator->>ProductGroupAPI: A.1 CreateProductGroup(ProductGroupDetails)
    ProductGroupAPI->>ProductGroupAPI: A.2.1 ValidateProductGroupDetails(ProductGroupDetails)
    ProductGroupAPI->>ProductSoR: A.2.2 CreateProductGroup(ProductGroupDetails)
    ProductSoR->>ProductSoR: A.3.1 SetProductGroupState("WaitingForApproval")
    ProductSoR-->>ProductGroupAPI: A.3.2 Return ProductGroup entity
    ProductGroupAPI-->>Initiator: A.4 Return ProductGroup entity
    Approver->>ProductGroupAPI: A.5 ApproveProductGroup(ProductGroupEntity)
    ProductGroupAPI->>ProductSoR: A.6 ApproveProductGroup(ProductGroupEntity)
    ProductSoR->>ProductSoR: A.7.1 SetProductGroupState("Approved")
    ProductSoR-->>ProductGroupAPI: A.7.2 Return ProductGroup entity
    ProductGroupAPI-->>Approver: A.8 Return ProductGroup entity
    ProductSoR->>ProductSoE: A.9 Publish ProductGroup entity
    ProductSoR->>EnterpriseEventHub: A.10 Publish ProductGroup entity
