# Hadoop HDFS Cluster Deployment & Administration

A comprehensive implementation of Hadoop Distributed File System (HDFS) using Docker containerization, featuring cluster deployment strategies, Namenode/Datanode configuration, command-line administration, and web-based monitoring interfaces.

## 🎯 Project Overview

This project explores distributed file system architecture through hands-on deployment and administration of Hadoop HDFS clusters. Implemented using Docker containers for isolated and reproducible environments, demonstrating practical knowledge of distributed storage systems, cluster computing, and data management at scale.

## 🛠️ Technology Stack

- **Apache Hadoop** - Distributed file system and processing framework
- **HDFS** - Hadoop Distributed File System for scalable storage
- **Docker** - Container platform for cluster deployment
- **Nginx** - Web server for log generation and testing
- **Python** - Scripting for data manipulation
- **Linux CLI** - System administration and file operations

## 📋 Implementation Components

### Cluster Deployment Analysis

Conducted comparative evaluation of Hadoop deployment strategies:

| Strategy | Scalability | Complexity | Use Case |
|----------|-------------|------------|----------|
| **Standalone Mode** | Single machine | Low | Development & testing |
| **Pseudo-Distributed** | Single machine simulation | Medium | Cluster simulation |
| **Fully Distributed** | Multi-node cluster | High | Production environments |
| **Cloud-Based** | Elastic scaling | Medium | Variable workloads |
| **Hybrid** | Mixed on-prem/cloud | High | Enterprise with compliance needs |

### Docker-Based Hadoop Deployment

**Container Architecture:**
- Deployed Harisekhon Hadoop Docker image
- Created separate Namenode and Datanode containers
- Configured inter-container networking
- Isolated environments for testing and development

**Key Operations:**
- Docker image selection and deployment
- Container orchestration and management
- Network configuration for cluster communication
- Port mapping for web interface access

### HDFS Architecture Configuration

**Namenode Management:**
- Located and analyzed fsimage (filesystem metadata snapshot)
- Examined edit logs for transaction tracking
- Understood metadata persistence mechanisms
- Configured Namenode for cluster coordination

**Datanode Operations:**
- Identified block storage locations on Datanodes
- Verified data replication across nodes
- Analyzed block distribution patterns
- Monitored Datanode health and capacity

### Command-Line Administration

**HDFS CLI Operations:**
- File system navigation and inspection
- Directory creation and management
- File upload and retrieval operations
- Metadata extraction and analysis
- Replication factor configuration
- Block size verification

**System Monitoring:**
- Cluster health checks
- Storage capacity analysis
- Node status verification
- Performance metrics extraction

### Web Interface Monitoring

**Administrative Dashboard:**
- Namenode web UI for cluster overview
- Datanode status and capacity visualization
- File system browsing through web interface
- Real-time cluster metrics monitoring
- Startup progress tracking
- Resource utilization graphs

**Key Metrics Tracked:**
- DFS storage capacity and usage
- Live/dead Datanode counts
- Block replication status
- Heap memory utilization
- Configuration parameters

### Real-World Data Processing

**Nginx Log Management:**
- Generated web server access logs
- Uploaded log files to HDFS
- Appended data to existing HDFS files
- Verified file replication and integrity
- Demonstrated practical HDFS usage patterns

**Python Integration:**
- Scripted data manipulation workflows
- Automated file operations
- Command-line integration for efficiency

## 💡 Technical Insights

### Distributed Storage Concepts

**HDFS Architecture:**
- Master-slave architecture with Namenode and Datanodes
- Block-based storage with configurable sizes
- Data replication for fault tolerance
- Rack awareness for optimized data placement

**Metadata Management:**
- Fsimage stores complete filesystem state
- Edit logs record all transactions
- Checkpoint process merges fsimage and edits
- In-memory metadata for fast operations

### Cluster Computing Principles

**Benefits Demonstrated:**
- Horizontal scalability through adding nodes
- Fault tolerance via data replication
- High availability with minimal downtime
- Cost-effective storage for large datasets

**Real-World Applications:**
- Log aggregation and analysis
- Data lake implementations
- Backup and archival systems
- Analytics data storage

## 🚀 Skills Demonstrated

- **Distributed Systems**: HDFS architecture and cluster deployment
- **Containerization**: Docker-based infrastructure management
- **System Administration**: Linux command-line proficiency
- **Storage Architecture**: Understanding of distributed file systems
- **Monitoring & Operations**: Web UI and CLI-based cluster management
- **Problem Solving**: Debugging deployment and configuration issues
- **Data Engineering**: Log processing and HDFS operations

## 📊 Technical Achievements

**Successfully Implemented:**
- Multi-container Hadoop cluster deployment
- Namenode and Datanode configuration
- HDFS command-line operations
- Web-based cluster monitoring
- Log file ingestion into HDFS
- Data replication verification
- File system health checks

**Configuration Insights:**
- Fsimage and edit log locations identified
- Block storage mechanisms understood
- Replication factors configured
- Cluster capacity analyzed

## 🏗️ Architecture Understanding

**Data Flow:**
1. Client submits file to Namenode
2. Namenode determines block placement
3. Client writes blocks directly to Datanodes
4. Datanodes replicate blocks to other nodes
5. Namenode tracks all metadata

**Components:**
- **Namenode**: Metadata management and coordination
- **Datanodes**: Actual data storage
- **Secondary Namenode**: Checkpoint process management
- **Client**: Interface for HDFS operations

## 📄 Technical Documentation

For complete deployment steps, configuration details, comparative analysis, screenshots, and troubleshooting notes, see the [full project documentation](hadoop-hdfs-deployment.pdf).

## 🎓 Background

Developed this project to gain practical experience with distributed file systems and cluster computing architectures. Explored various deployment strategies and hands-on administration of HDFS, understanding the foundations of technologies used by organizations like Yahoo, Facebook, and LinkedIn for petabyte-scale data storage.

## 🔗 Connect

**Meriem Lmoubariki**
- GitHub: [@myriamlmiii](https://github.com/myriamlmiii)

---

*Demonstrating proficiency in distributed file systems, cluster administration, and containerized infrastructure deployment.*
