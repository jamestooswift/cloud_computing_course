# Checkpoint 7 – Continue Your Linux Investigation

## Linux Server Investigation

For this activity, I launched an **Ubuntu Linux Playground using KillerCoda**. I used Linux commands to check the operating system, CPU, memory, and disk space of the server.

### 1. Operating System

I used the following command:

```bash
cat /etc/os-release
```

The server is running **Ubuntu 24.04.4 LTS (Noble Numbat)**.

![Linux Operating System](screenshots/linux-os.png)

### 2. CPU Information

I used:

```bash
lscpu
```

The server uses an **Intel Xeon E312xx processor** with an **x86_64 architecture**. The playground has **1 CPU**.

![Linux CPU Information](screenshots/linux-cpu.png)

### 3. Memory

I used:

```bash
free -h
```

The server has **1.9 GiB of total memory**. At the time I checked it, about **1.5 GiB was available**.

![Linux Memory Information](screenshots/linux-memory.png)

### 4. Disk Space

I used:

```bash
df -h
```

The main disk has about **19 GB of total space**, with approximately **5.4 GB used** and **13 GB available**.

![Linux Disk Space](screenshots/linux-disk.png)

---

## Cloud Migration

If this Linux server were migrated to the cloud, I could use virtual machine services from AWS, Microsoft Azure, or Google Cloud.

| **Cloud Provider**  | **Service**            | **Purpose**                               |
| ------------------- | ---------------------- | ----------------------------------------- |
| **AWS**             | Amazon EC2             | Run the Linux server as a virtual machine |
| **Microsoft Azure** | Azure Virtual Machines | Run the Linux server in Azure             |
| **Google Cloud**    | Compute Engine         | Run the Linux server in Google Cloud      |

### AWS – Amazon EC2

I could use **Amazon EC2** to host this Linux server as a virtual machine. I could choose an instance with enough CPU, memory, and storage for the server.

### Microsoft Azure – Azure Virtual Machines

I could use **Azure Virtual Machines** to run the Linux server in Microsoft's cloud. Azure supports Linux operating systems and allows me to choose the resources needed by the server.

### Google Cloud – Compute Engine

I could use **Google Compute Engine** to host the Linux server. It provides virtual machines where I can run Linux and choose the CPU, memory, and storage resources.

## Conclusion

From this activity, I learned how to use basic Linux commands to check the information of a server. I also learned that a Linux server can be moved to different cloud platforms using virtual machine services such as **Amazon EC2, Azure Virtual Machines, and Google Compute Engine**.
