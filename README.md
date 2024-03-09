## Project 3: Distributed File System Implementation

### Overview

Project 3 involves designing and implementing a distributed file system (DFS) using F# and Akka.NET. The DFS aims to provide a fault-tolerant, scalable, and efficient file storage and retrieval system across a network of distributed nodes.

### Key Features

- **Fault Tolerance**: Implements fault tolerance mechanisms to ensure system resilience and reliability.
- **Scalability**: Designed to scale seamlessly with the addition of new nodes to the network.
- **File Replication**: Utilizes file replication strategies to enhance data availability and durability.
- **Consistency**: Maintains data consistency across distributed nodes through synchronization protocols.
- **File Operations**: Supports basic file operations such as upload, download, delete, and listing files.

### Setup and Usage

Follow the setup instructions provided in the project directory to compile and run the distributed file system. Use the provided commands to interact with the system and perform file operations.
### Setup Instructions
```
1. Clone the repository to your local machine.
2. Ensure you have the latest version of the .NET SDK and Akka.NET installed.
3. Navigate to the project directory.
4. Compile the project using the `dotnet build` command.
5. Run the DFS using the `dotnet run` command.
```
### Usage

Once the DFS is running, clients can interact with the system using the provided APIs or command-line interface. Sample commands include:
```
- `upload <file>`: Uploads a file to the DFS.
- `download <file>`: Downloads a file from the DFS.
- `delete <file>`: Deletes a file from the DFS.
- `list`: Lists all files stored in the DFS.

```
## License

This project is licensed under the MIT License - see the License file for details.

## Acknowledgments

- Dr. Jonathan for providing guidance and support throughout the course.
- The team members for their contributions to each project.
