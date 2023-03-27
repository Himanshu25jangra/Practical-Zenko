# "ZENKO" Project Analysis

**Introduction**-

Zenko, Scality’s multi-cloud controller, provides an open-source, platform-agnostic gateway to facilitate data replication and management for storage managers handling extreme data volumes over multiple clouds. Zenko provides a single integration point from which cloud data can be managed in several protocol spaces. Zenko offers these capabilities using the logic and much of the syntax of Amazon Web Services’ Simple Storage Service protocol (AWS S3) through its Cloud Server module.

**Project Summary-**
|||
|-|-|
|**Website**|https://www.zenko.io
|**Organization/Foundation Name**|Scality
|**License**|Apache License 2.0
|**Open/ Proprietary**|Open
|**Source Path**|https://github.com/scality/Zenko



**Project Details-**

**Key**  **Features**:

> -   Store all data unmodified so that it can be accessed and acted on in the cloud directly.
> -   One-to-Many cross region replication.
> -   Multiple storage backend (RING sproxyd, RING S3 Connector. Amazon S3)
> -   Enable data mobility so that data can be easily placed in the most efficient location.
> -   Provide a single endpoint through which data can be stored, retrieved and searched across any location.


**Zenko Basic Architecture-**
    

![](https://camo.githubusercontent.com/45127d2eb71071d4cc712e142d4661b4d6bd2cac44a568ddc49ec6018e9d6f77/68747470733a2f2f7a656e6b6f2e72656164746865646f63732e696f2f656e2f6c61746573742f5f696d616765732f5a656e6b6f5f68692d6c6576656c2e737667)
Figure: Zenko Architecture
 
 **Description:-**
 Zenko Cloud architecture uses multiple backed like ring, AWS S3,Azure. API    calls are used to take request from users so that user can access ,edit or delete data from any private or public cloud used by it. With single platform user can control all his cloud servers.
 Now Zenko is used by many organization like connectUs , CommunicateWork etc.

