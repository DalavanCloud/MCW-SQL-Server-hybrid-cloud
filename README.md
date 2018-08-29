# SQL Server hybrid cloud

Fabrikam Publishing is a media and publishing company in Seattle, Washington with approximately 5000 employees. They have a successful direct-to-consumer e-commerce site built with .NET, and they use SQL Server to store customer profile and order information.

They are interested in increasing the availability of their e-commerce application and have selected using Microsoft Azure as a fail-over target. They are interested in designing a solution where their application can be deployed on-premises as well as in the cloud, so if either location has an outage their application is available.

## Target audience

-	Infrastructure Architect
-	Database Administrator

## Abstract

### Workshop

In this workshop, you will work with a media publishing company to design a hybrid cloud disaster recovery solution. You will design the solution to handle large spikes in load and harden the security to include encryption of Payment Card Industry (PCI) data. Additionally, you will implement an archival strategy to keep databases sizes in check.

At the end of this workshop, you will be better able to design a hybrid disaster recovery solution between an on-premises VMWare environment and Azure. In addition, you will design a SQL Server scale-out solution, protect database backups from local failures, archive cold data from an on-premises SQL Server, and perform end-to-end encryption on sensitive application data.

### Whiteboard design session

In this whiteboard design session, you will look at how to design an application for hybrid deployment between on-premises and Microsoft Azure. You will consider how the web tier must be made available in the event of an outage as well as how to configure SQL Server Always-on Availability Groups to deploy and failover between both locations.

At the end of this whiteboard design session, you will be better able to design a hybrid disaster recovery solution between an on-premises VMWare environment and Azure. In addition, you will design a SQL Server scale-out solution, protect database backups from local failures, archive cold data from an on-premises SQL Server, and perform end-to-end encryption on sensitive application data.
 
### Hands-on lab

At this time, there is no hands-on lab for this workshop.

## Azure services and related products
- SQL Server (On Prem)
- Azure SQL Database
- Azure Site Recovery
- Azure Traffic Manager
- Azure Storage

## Azure solutions
Data Modernization to Azure

## Related references 
- [MCW](https://github.com/Microsoft/MCW)

