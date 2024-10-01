# Aphluentia++: Supporting Technology Mediated Communication for Aphasia   
## Full Project Available [Here](https://github.com/Aphluentia)  

To setup the project, refer to the Documentation in present below:  

## Documentation & Setup Procedures  
- Diagrams and other documentation such as Setup Procedures  
- [Main](https://github.com/Aphluentia/Documentation)   

## Notebook   
- Summary of weekly work for the pre-dissertation course   
- [Notebook](https://github.com/Aphluentia/Noteblock)  

## Framework Componenents:  


### Database      
- Repository of the DatabaseAPI   
- Serves as the interface for seamless interaction with MongoDB. Manages entities such as therapists, patients, applications, and modules. Controllers handle various data operations.  
- [Main](https://github.com/Aphluentia/Database)   


### KafkaCluster     
- Repository of the Kafka Cluster as a Task Queue    
- Contains the Kafka Cluster that connects to the OperationsAPI and Operations Manager   
- [Main](https://github.com/Aphluentia/KafkaCluster)   

### OperationsAPI     
- Repository of the OperationsAPI     
- Creates requests sent to the system for data modification. Interfaces with OperationsManager to orchestrate various operations and validate incoming data.        
- [Main](https://github.com/Aphluentia/OperationsAPI)   


### OperationsManager      
- Repository of the OperationsManager       
- Intermediary between the application and Kafka broker. Orchestrates operations, validates data, and ensures secure data processing. Implements multithreading for efficient operation processing.         
- [Main](https://github.com/Aphluentia/OperationsManager)   

### SecurityManager      
- Repository of the SecurityManager       
- Ensures security and efficient session management by working with a Redis database. Responsible for token generation, validation, and handling module snapshots for data integrity.     
- [Main](https://github.com/Aphluentia/SecurityManager)   

### SystemGateway       
- Repository of the SystemGatewayAPI         
- Acts as the gateway for the system, interfacing with DatabaseAPI, OperationsAPI, and SecurityManager. Ensures controlled access to the system's functionalities for optimal performance.    
- [Main](https://github.com/Aphluentia/SystemGateway)   



## PlatformModule:     
- Proof-of-Concept Application Frontend  
- [Main](https://github.com/Aphluentia/PlatformModule)   







