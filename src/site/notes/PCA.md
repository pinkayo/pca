---
{"dg-publish":true,"permalink":"/PCA/","tags":["gardenEntry"]}
---

**Question #6**
**You need to reduce the number of unplanned rollbacks of erroneous production deployments in your company's web hosting platform. Improvement to the QA/  
Test processes accomplished an 80% reduction.  
Which additional two approaches can you take to further reduce the rollbacks? (Choose two.)**

- **A. Introduce a green-blue deployment model**
- **B. Replace the QA environment with canary releases**
- **C. Fragment the monolithic platform into microservices**
- **D. Reduce the platform's dependency on relational database systems**
- **E. Replace the platform's relational database systems with a NoSQL database**
#### *要進一步減少公司網頁托管平台因意外部署錯誤而導致的回滾次數，除了改進品質保證/測試流程已經達到80%的減少外，你還可以採取以下哪兩種方法（選兩項）*

- #### *A. 引入綠藍部署模型*
- #### *B. 將QA環境替換為金絲雀發佈*
- #### *C. 將單體平台分解為微服務*
- #### *D. 減少平台對關係型數據庫系統的依賴*
- #### *E. 將平台的關係型數據庫系統替換為NoSQL數據庫*

> [!NOTE]- Answer
> **A. Introduce a green-blue deployment model**
> **C. Fragment the monolithic platform into microservices**
> 
> # Notes
> 增加穩定度方式：容器化部署、負載平衡

---
**Question #7**
**To reduce costs, the Director of Engineering has required all developers to move their development infrastructure resources from on-premises virtual machines (VMs) to Google Cloud Platform. These resources go through multiple start/stop events during the day and require state to persist. You have been asked to design the process of running a development environment in Google Cloud while providing cost visibility to the finance department. 
Which two steps should you take? (Choose two.)**

- **A. Use the - -no-auto-delete flag on all persistent disks and stop the VM**
- **B. Use the - -auto-delete flag on all persistent disks and terminate the VM**
- **C. Apply VM CPU utilization label and include it in the BigQuery billing export**
- **D. Use Google BigQuery billing export and labels to associate cost to groups Most Voted**
- **E. Store all state into local SSD, snapshot the persistent disks, and terminate the VM**
- **F. Store all state in Google Cloud Storage, snapshot the persistent disks, and terminate the VM**
#### *為了降低成本，工程總監要求所有開發人員將其開發基礎設施資源從本地虛擬機器 (VM) 遷移到 Google Cloud Platform。這些資源在一天中會經歷多個啟動/停止事件，並且需要保持狀態。我們要求您設計在 Google Cloud 中運行開發環境的流程，同時向財務部門提供成本可見度。 （選兩個。）*

- #### *A. 在所有永久磁碟上使用 - -no-auto-delete 標誌並停止 VM*
- #### *B. 在所有永久磁碟上使用 --auto-delete 標誌並終止 VM*
- #### *C. 應用虛擬機器 CPU 使用率標籤並將其包含在 BigQuery 計費匯出中*
- #### *D. 使用 Google BigQuery 結算匯出和標籤將成本與投票最多的群組關聯起來*
- #### *E. 將所有狀態儲存到本機 SSD、對永久磁碟進行快照並終止 VM*
- #### *F. 將所有狀態儲存在 Google Cloud Storage 中，對永久性磁碟進行快照，並終止 VM*

> [!NOTE]- Answer
> **A. Use the - -no-auto-delete flag on all persistent disks and stop the VM**
> **D. Use Google BigQuery billing export and labels to associate cost to groups Most Voted**
> 
> # Notes
> [gcloud compute instances set-disk-auto-delete  |  Google Cloud CLI Documentation](https://cloud.google.com/sdk/gcloud/reference/compute/instances/set-disk-auto-delete#--auto-delete)
> [将 Cloud Billing 数据导出到 BigQuery  |  Google Cloud](https://cloud.google.com/billing/docs/how-to/export-data-bigquery?hl=zh-cn)
> [[assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg|Open: PCA-image-20240708182619467.png]]
> ![assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg](/img/user/assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg)
> 匯出
> [[assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg|Open: PCA-image-20240708184058884.png]]
> ![assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg](/img/user/assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg)

---
**Question #8**
**Your company wants to track whether someone is present in a meeting room reserved for a scheduled meeting. There are 1000 meeting rooms across 5 offices on 3 continents. Each room is equipped with a motion sensor that reports its status every second. The data from the motion detector includes only a sensor ID and several different discrete items of information. Analysts will use this data, together with information about account owners and office locations.  
Which database type should you use?**

- **A. Flat file**
- **B. NoSQL**
- **C. Relational**
- **D. Blobstore**
#### *您的公司希望追蹤是否有人出現在已安排的會議室中。在3大洲的5個辦事處設有1000間會議室。每個房間都配備了一個運動感測器，每秒報告一次狀態。來自運動檢測器的數據僅包括一個感測器ID和幾個不同的離散資訊項。分析師將使用這些數據，以及有關帳戶擁有者和辦公地點的資訊。 應該使用哪種資料庫類型？*

- #### *A. 平面文件*
- #### *B. 非關聯式資料庫*
- #### *C. 關聯式資料庫*
- #### *D. 二進位大物件儲存*

> [!NOTE]- Answer
> **B. NoSQL**
> 
> # Notes
> [[assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg|Open: PCA-image-20240708173116708.png]]
> ![assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg](/img/user/assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg)
> [[assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg|Open: PCA-image-20240708161421503.png]]
> ![assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg](/img/user/assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg)

---
**Question #9**
**You set up an autoscaling instance group to serve web traffic for an upcoming launch. After configuring the instance group as a backend service to an HTTP(S) load balancer, you notice that virtual machine (VM) instances are being terminated and re-launched every minute. The instances do not have a public IP address.  
You have verified the appropriate web response is coming from each instance using the curl command. You want to ensure the backend is configured correctly.  
What should you do?**

- **A. Ensure that a firewall rules exists to allow source traffic on HTTP/HTTPS to reach the load balancer.**
- **B. Assign a public IP to each instance and configure a firewall rule to allow the load balancer to reach the instance public IP.**
- **C. Ensure that a firewall rule exists to allow load balancer health checks to reach the instances in the instance group.**
- **D. Create a tag on each instance with the name of the load balancer. Configure a firewall rule with the name of the load balancer as the source and the instance tag as the destination.**
#### *您可以設置一個自動擴展實例組，以便為即將啟動的 Web 流量提供服務。將實例組配置為 HTTP（S） 負載均衡器的後端服務後，您會注意到虛擬機 （VM） 實例每分鐘都會被終止並重新啟動。實例沒有公有IP位址。 您已使用 curl 命令驗證每個實例是否發出了相應的 Web 回應。您希望確保後端配置正確。 你應該怎麼做*

- #### *A. 確保存在防火牆規則，以允許 HTTP/HTTPS 上的源流量到達負載均衡器。*
- #### *B. 為每個實例分配一個公有IP，並配置防火牆規則以允許負載均衡器訪問實例公有IP。*
- #### *C. 確保存在防火牆規則，以允許負載均衡器運行健康檢查訪問實例組中的實例*
- #### *D. 在每個實例上創建一個帶有負載均衡器名稱的標籤。配置防火牆規則，將負載均衡器的名稱作為源，將實例標籤作為目標*

> [!NOTE]- Answer
> **C. Ensure that a firewall rule exists to allow load balancer health checks to reach the instances in the instance group**
> 
> # Notes
> [后端服务概览  |  Load Balancing  |  Google Cloud](https://cloud.google.com/load-balancing/docs/backend-service?hl=zh-cn)
> 防火牆與健康檢查
> [[assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg|Open: PCA-image-20240708153509944.png]]
> ![assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg](/img/user/assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg)
> [[assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg|Open: PCA-image-20240708154358114.png]]
> ![assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg](/img/user/assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg)

---
**Question #10**
**You write a Python script to connect to Google BigQuery from a Google Compute Engine virtual machine. The script is printing errors that it cannot connect to  
BigQuery.  
What should you do to fix the script?**

- **A. Install the latest BigQuery API client library for Python**
- **B. Run your script on a new virtual machine with the BigQuery access scope enabled**
- **C. Create a new service account with BigQuery access and execute your script with that user**
- **D. Install the bq component for gcloud with the command gcloud components install bq.**
#### *您編寫了一個 Python 腳本以從 Google Compute Engine 虛擬機連接到 Google BigQuery。腳本顯示無法連接到BigQuery的錯誤 。 你應該怎麼做才能修復腳本？*

- #### *A. 安裝適用於 Python 的最新 BigQuery API 用戶端庫*
- #### *B. 啟用了 BigQuery 存取權限範圍的新虛擬機上運行腳本*
- #### *C. 建立一個具有 BigQuery 訪問許可權的新服務帳號，並使用該使用者執行腳本*
- #### *D. 使用命令 gcloud components install bq 安裝 gcloud 的 bq 元件*

> [!NOTE]- Answer
> **C. Create a new service account with BigQuery access and execute your script with that user**
> 
> # Notes
> [为 API 请求授权  |  BigQuery  |  Google Cloud](https://cloud.google.com/bigquery/docs/authorization?hl=zh-cn#client-libraries)
> 服務帳戶建立
> [[assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg|Open: PCA-image-20240708152529305.png]]
> ![assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg](/img/user/assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg)

---
**Question #26**
**Your organization requires that metrics from all applications be retained for 5 years for future analysis in possible legal proceedings.  
Which approach should you use?**

- **A. Grant the security team access to the logs in each Project**
- **B. Configure Stackdriver Monitoring for all Projects, and export to BigQuery**
- **C. Configure Stackdriver Monitoring for all Projects with the default retention policies**
- **D. Configure Stackdriver Monitoring for all Projects, and export to Google Cloud Storage**

#### *您的組織要求將所有應用程式的指標保留 5 年，以便將來在可能的法律訴訟中進行分析。您應該使用哪一種方法？*

- #### *A. 授予安全團隊存取每個項目中日誌的權限*
- #### *B. 為所有專案配置 Stackdriver Monitoring，並匯出到 BigQuery*
- #### *C. 使用預設保留策略為所有專案配置 Stackdriver Monitoring*
- #### *D. 為所有專案配置 Stackdriver Monitoring，並匯出至 Google Cloud Storage*

> [!NOTE]- Answer
> **D. Configure Stackdriver Monitoring for all Projects, and export to Google Cloud Storage**
> 
> # Notes
> [将日志路由到支持的目的地  |  Cloud Logging  |  Google Cloud](https://cloud.google.com/logging/docs/export/configure_export_v2?hl=zh-cn)
> 預設保留策略：
   保留最新6週監控數據
> 匯出設定方式：
> [[assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg|Open: PCA-image-20240710163111852.png]]
> ![assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg](/img/user/assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg)

---
**Question #27**
**Your company has decided to build a backup replica of their on-premises user authentication PostgreSQL database on Google Cloud Platform. The database is 4 TB, and large updates are frequent. Replication requires private address space communication.  
Which networking approach should you use?**

- **A. Google Cloud Dedicated Interconnect**
- **B. Google Cloud VPN connected to the data center network**
- **C. A NAT and TLS translation gateway installed on-premises**
- **D. A Google Compute Engine instance with a VPN server installed connected to the data center network**

#### *貴公司決定在 Google Cloud Platform 上建立其本機使用者身分驗證 PostgreSQL 資料庫的備份副本。資料庫4 TB更新頻繁。副本需要透過私人位址空間通訊。您應該使用哪種網路方法？*

- #### *A. Google Cloud 專用互連*
- #### *B. 連接到資料中心網路的 Google Cloud VPN*
- #### *C. 本機安裝的 NAT 和 TLS 轉換網關*
- #### *D. Google Compute Engine 實例安裝VPN 伺服器連線到資料中心網路*

> [!NOTE]- Answer
> **A. Google Cloud Dedicated Interconnect**
> 
> # Notes
> [专用互连概览  |  Cloud Interconnect  |  Google Cloud](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/dedicated-overview?hl=zh-cn)
> [Cloud VPN 概览  |  Google Cloud](https://cloud.google.com/network-connectivity/docs/vpn/concepts/overview?hl=zh-cn)
> [[assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg|Open: PCA-image-20240716104810403.png]]
> ![assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg](/img/user/assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg)

---
**Question #28**
**Auditors visit your teams every 12 months and ask to review all the Google Cloud Identity and Access Management (Cloud IAM) policy changes in the previous 12 months. You want to streamline and expedite the analysis and audit process.  
What should you do?**

- #### **A. Create custom Google Stackdriver alerts and send them to the auditor**
- #### **B. Enable Logging export to Google BigQuery and use ACLs and views to scope the data shared with the auditor**
- #### **C. Use cloud functions to transfer log entries to Google Cloud SQL and use ACLs and views to limit an auditor's view**
- #### **D. Enable Google Cloud Storage (GCS) log export to audit logs into a GCS bucket and delegate access to the bucket**

#### *審核員每 12 個月造訪一次您的團隊，並要求審核過去 12 個月內的所有 Google Cloud Identity and Access Management (Cloud IAM) 政策變更。您想要簡化並加快分析和審核流程。你該做什麼？*

- #### *A. 建立自訂 Google Stackdriver 警報並將其傳送給審核員*
- #### *B. 啟用日誌記錄匯出到 Google BigQuery 並使用 ACL 和視圖來確定與審核員共享的資料的範圍*
- #### *C. 使用雲端函數將日誌條目傳輸到 Google Cloud SQL，並使用 ACL 和檢視來限制審核員的檢視*
- #### *D. 啟用 Google Cloud Storage (GCS) 日誌匯出，以審核日誌到 GCS 儲存桶並委派對該儲存桶的存取權限*

> [!NOTE]- Answer
> **B. Enable Logging export to Google BigQuery and use ACLs and views to scope the data shared with the auditor**
> 
> # Notes
> [负有审核相关工作职责的 IAM 角色  |  IAM 文档  |  Google Cloud](https://cloud.google.com/iam/docs/job-functions/auditing?hl=zh-cn#scenario_external_auditors)
> [[assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg|Open: PCA-image-20240715165522502.png]]
> ![assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg](/img/user/assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg)
> [[assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg|Open: PCA-image-20240715165532896.png]]
> ![assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg](/img/user/assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg)
> [[assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg|Open: PCA-image-20240715172936030.png]]
> ![assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg](/img/user/assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg)
> [[assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg|Open: PCA-image-20240715173107356.png]]
> ![assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg](/img/user/assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg)
> [[assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg|Open: PCA-image-20240715173117999.png]]
> ![assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg](/img/user/assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg)

---
**Question #29**
**You are designing a large distributed application with 30 microservices. Each of your distributed microservices needs to connect to a database back-end. You want to store the credentials securely.  
Where should you store the credentials?**

- **A. In the source code**
- **B. In an environment variable**
- **C. In a secret management system**
- **D. In a config file that has restricted access through ACLs**

#### *您正在設計一個包含 30 個微服務的大型分散式應用程式。每個分散式微服務都需要連接到資料庫後端。您想要安全地儲存憑證。在原始碼中您應該在哪裡儲存憑證？*

- #### *A. 原始碼中*
- #### *B. 在環境變數中*
- #### *C. 在秘密管理系統中*
- #### *D. 在透過 ACL 限制存取的設定檔中*

> [!NOTE]- Answer
> **C. In a secret management system**
> 
> # Notes
> [Secret Manager 概览  |  Secret Manager Documentation  |  Google Cloud](https://cloud.google.com/secret-manager/docs/overview?hl=zh-cn)
> [[assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg|Open: PCA-image-20240715155416901.png]]
> ![assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg](/img/user/assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg)

---
**Question #30**
**A lead engineer wrote a custom tool that deploys virtual machines in the legacy data center. He wants to migrate the custom tool to the new cloud environment.  
You want to advocate for the adoption of Google Cloud Deployment Manager.  
What are two business risks of migrating to Cloud Deployment Manager? (Choose two.)**

- **A. Cloud Deployment Manager uses Python**
- **B. Cloud Deployment Manager APIs could be deprecated in the future**
- **C. Cloud Deployment Manager is unfamiliar to the company's engineers**
- **D. Cloud Deployment Manager requires a Google APIs service account to run**
- **E. Cloud Deployment Manager can be used to permanently delete cloud resources**
- **F. Cloud Deployment Manager only supports automation of Google Cloud resources**

#### *一位首席工程師編寫了一個自訂工具，用在傳統資料中心部署虛擬機器。他希望將自訂工具遷移到新的雲端環境。您想要倡導採用 Google Cloud Deployment Manager並遷移到 Cloud Deployment Manager 的兩個業務風險是什麼？（選兩項。）*

- #### *A. Cloud Deployment Manager 使用 Python*
- #### *B. Cloud Deployment Manager API 將來可能會被棄用*
- #### *C. 公司工程師對Cloud Deployment Manager比較陌生*
- #### *D. Cloud Deployment Manager 需要 Google API 服務帳戶才能執行*
- #### *E. Cloud Deployment Manager 可用於永久刪除雲端資源*
- #### *F. Cloud Deployment Manager 僅支援 Google Cloud 資源的自動化*

> [!NOTE]- Answer
> **C. Cloud Deployment Manager is unfamiliar to the company's engineers**
> **F. Cloud Deployment Manager only supports automation of Google Cloud resources**
> 
> # Notes
> [Google Cloud Deployment Manager 文档  |  Cloud Deployment Manager Documentation](https://cloud.google.com/deployment-manager/docs?hl=zh-cn)
> [[assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg|Open: PCA-image-20240715145659726.png]]
> ![assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg](/img/user/assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg)
> [[assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg|Open: PCA-image-20240716164512964.png]]
> ![assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg](/img/user/assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg)

---
**Question #51**
**You have found an error in your App Engine application caused by missing Cloud Datastore indexes. You have created a YAML file with the required indexes and want to deploy these new indexes to Cloud Datastore. What should you do? **

- **A. Point gcloud datastore create-indexes to your configuration file**
- **B. Upload the configuration file to App Engine's default Cloud Storage bucket, and have App Engine detect the new indexes**
- **C. In the GCP Console, use Datastore Admin to delete the current indexes and upload the new configuration file**
- **D. Create an HTTP request to the built-in python module to send the index configuration file to your application**

#### *您發現 App Engine 應用程式中存在由於缺少 Cloud Datastore 索引而導致的錯誤。您已建立包含所需索引的 YAML 文件，並希望將這些新索引部署到 Cloud Datastore。你該怎麼辦？*

- #### *A. 將 gcloud datastore create-indexes 指向您的設定檔*
- #### *B. 將設定檔上傳到 App Engine 的預設 Cloud Storage 儲存桶，並讓 App Engine 偵測新索引*
- #### *C. 在 GCP Console 中，使用 Datastore Admin 刪除目前索引並上傳新的設定檔*
- #### *D. 建立一個對內建 python 模組的 HTTP 請求，將索引設定檔傳送到您的應用程式*

> [!NOTE]- Answer
> **A. Point gcloud datastore create-indexes to your configuration file**
> 
> # Notes
> [gcloud datastore indexes create  |  Google Cloud CLI Documentation](https://cloud.google.com/sdk/gcloud/reference/datastore/indexes/create)
> [价格  |  Datastore  |  Google Cloud](https://cloud.google.com/datastore/pricing?hl=zh-cn)
> [[assets/PCA/41fb6ea1875fcbb14e80466be184ce36_MD5.jpeg|Open: PCA-image-20240729165841757.png]]
> ![assets/PCA/41fb6ea1875fcbb14e80466be184ce36_MD5.jpeg](/img/user/assets/PCA/41fb6ea1875fcbb14e80466be184ce36_MD5.jpeg)
> [[assets/PCA/5dc07bc0740926396ee1fd6d913d6c67_MD5.jpeg|Open: PCA-image-20240729170836462.png]]
> ![assets/PCA/5dc07bc0740926396ee1fd6d913d6c67_MD5.jpeg](/img/user/assets/PCA/5dc07bc0740926396ee1fd6d913d6c67_MD5.jpeg)

---
**Question #52**
**You have an application that will run on Compute Engine. You need to design an architecture that takes into account a disaster recovery plan that requires your application to fail over to another region in case of a regional outage. What should you do?**

- **A. Deploy the application on two Compute Engine instances in the same project but in a different region. Use the first instance to serve traffic, and use the HTTP load balancing service to fail over to the standby instance in case of a disaster.**
- **B. Deploy the application on a Compute Engine instance. Use the instance to serve traffic, and use the HTTP load balancing service to fail over to an instance on your premises in case of a disaster.**
- **C. Deploy the application on two Compute Engine instance groups, each in the same project but in a different region. Use the first instance group to serve traffic, and use the HTTP load balancing service to fail over to the standby instance group in case of a disaster.**
- **D. Deploy the application on two Compute Engine instance groups, each in a separate project and a different region. Use the first instance group to serve traffic, and use the HTTP load balancing service to fail over to the standby instance group in case of a disaster.**

#### *您有一個將在 Compute Engine 上運行的應用程式。您需要設計一個考慮到災難復原計劃的架構，該計劃要求您的應用程式在發生區域中斷時故障轉移到另一個區域。你該怎麼辦？*

- #### *A. 將應用程式部署在同一專案但位於不同區域的兩個 Compute Engine 執行個體上。使用第一個執行個體來提供流量，並使用 HTTP 負載平衡服務在發生災難時故障轉移到備用實例。*
- #### *B. 在 Compute Engine 執行個體上部署應用程式。使用執行個體提供流量服務，並使用 HTTP 負載平衡服務在發生災難時故障轉移到您本地的執行個體。*
- #### *C. 在兩個 Compute Engine 實例群組上部署應用程序，每個實例群組位於相同專案但位於不同區域。使用第一個實例組來提供流量，並使用 HTTP 負載平衡服務在災難發生時故障轉移到備用實例組。*
- #### *D. 在兩個 Compute Engine 實例群組上部署應用程序，每個實例組位於單獨的專案和不同的區域。使用第一個實例組來提供流量，並使用 HTTP 負載平衡服務在災難發生時故障轉移到備用實例組。*

> [!NOTE]- Answer
> **C. Deploy the application on two Compute Engine instance groups, each in the same project but in a different region. Use the first instance group to serve traffic, and use the HTTP load balancing service to fail over to the standby instance group in case of a disaster.**
> 
> # Notes
> [为外部直通式网络负载均衡器配置故障切换  |  Load Balancing  |  Google Cloud](https://cloud.google.com/load-balancing/docs/network/networklb-setting-up-failover?hl=zh-cn)
> [[assets/PCA/8dff30ac8ff1221a4ae4044cfb53c06b_MD5.jpeg|Open: PCA-image-20240730104933859.png]]
> ![assets/PCA/8dff30ac8ff1221a4ae4044cfb53c06b_MD5.jpeg](/img/user/assets/PCA/8dff30ac8ff1221a4ae4044cfb53c06b_MD5.jpeg)

---
**Question #53**
**You are deploying an application on App Engine that needs to integrate with an on-premises database. For security purposes, your on-premises database must not be accessible through the public internet. What should you do?**

- **A. Deploy your application on App Engine standard environment and use App Engine firewall rules to limit access to the open on-premises database.**
- **B. Deploy your application on App Engine standard environment and use Cloud VPN to limit access to the on-premises database.**
- **C. Deploy your application on App Engine flexible environment and use App Engine firewall rules to limit access to the on-premises database.**
- **D. Deploy your application on App Engine flexible environment and use Cloud VPN to limit access to the on-premises database.**

#### *您正在 App Engine 上部署需要與本機資料庫整合的應用程式。出於安全目的，您的本地資料庫不得透過公共網路存取。你該怎麼辦？*

- #### *A. 在 App Engine 標準環境中部署您的應用程序，並使用 App Engine 防火牆規則來限制對開放本地資料庫的存取。*
- #### *B. 在 App Engine 標準環境上部署您的應用程序，並使用 Cloud VPN 限制對本機資料庫的存取。*
- #### *C. 在 App Engine 柔性環境中部署您的應用程序，並使用 App Engine 防火牆規則來限制對本機資料庫的存取。*
- #### *D. 在 App Engine 柔性環境上部署您的應用程序，並使用 Cloud VPN 限制對本地資料庫的存取。*

> [!NOTE]- Answer
> **D. Deploy your application on App Engine flexible environment and use Cloud VPN to limit access to the on-premises database.**
> 
> # Notes
> [App Engine 应用平台 | Google Cloud](https://cloud.google.com/appengine?hl=zh-cn#all-features)
> [[assets/PCA/bd9c1d9e51bba8f35113fbda1a06c74d_MD5.jpeg|Open: PCA-image-20240801163822509.png]]
> ![assets/PCA/bd9c1d9e51bba8f35113fbda1a06c74d_MD5.jpeg](/img/user/assets/PCA/bd9c1d9e51bba8f35113fbda1a06c74d_MD5.jpeg)
> [[assets/PCA/a0c898d302accafebac2fab55f83bb96_MD5.jpeg|Open: PCA-image-20240801163208071.png]]
> ![assets/PCA/a0c898d302accafebac2fab55f83bb96_MD5.jpeg](/img/user/assets/PCA/a0c898d302accafebac2fab55f83bb96_MD5.jpeg)
> [[assets/PCA/d2cf6b734b565d96ccf68054fc065182_MD5.jpeg|Open: PCA-image-20240801163449491.png]]
> ![assets/PCA/d2cf6b734b565d96ccf68054fc065182_MD5.jpeg](/img/user/assets/PCA/d2cf6b734b565d96ccf68054fc065182_MD5.jpeg)

---
**Question #54**
**You are working in a highly secured environment where public Internet access from the Compute Engine VMs is not allowed. You do not yet have a VPN connection to access an on-premises file server. You need to install specific software on a Compute Engine instance. How should you install the software?**

- **A. Upload the required installation files to Cloud Storage. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gsutil.**
- **B. Upload the required installation files to Cloud Storage and use firewall rules to block all traffic except the IP address range for Cloud Storage. Download the files to the VM using gsutil.**
- **C. Upload the required installation files to Cloud Source Repositories. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gcloud.**
- **D. Upload the required installation files to Cloud Source Repositories and use firewall rules to block all traffic except the IP address range for Cloud Source Repositories. Download the files to the VM using gsutil.**

#### *您正在高度安全的環境中工作，不允許從 Compute Engine 虛擬機器存取公共互聯網。您還沒有用於存取本機檔案伺服器的 VPN 連線。您需要在 Compute Engine 實例上安裝特定軟體。您應該如何安裝該軟體？*

- #### *A. 將所需的安裝檔案上傳到Cloud Storage。將虛擬機器設定在具有私人 Google 存取功能的子網路上。僅指定內部 IP 位址給虛擬機器。使用 gsutil 將安裝檔下載到 VM。*
- #### *B. 將所需的安裝檔案上傳到Cloud Storage，並使用防火牆規則阻止除雲端儲存的 IP 位址範圍之外的所有流量。使用 gsutil 將檔案下載到 VM。*
- #### *C. 將所需的安裝檔案上傳至 Cloud Source Repositories，在具有專用 Google Access 子網路的子網路上設定虛擬機器。僅向 VM 指派內部 IP 位址。使用 gcloud 將安裝檔下載到虛擬機器。*
- #### *D. 將所需的安裝檔案上傳到Cloud Source Repositories，並使用防火牆規則阻止除雲端來源庫 IP 位址範圍之外的所有流量。使用 gsutil 將檔案下載到 VM。*

> [!NOTE]- Answer
> **A. Upload the required installation files to Cloud Storage. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gsutil.**
> 
> # Notes
> [cp - Copy files and objects  |  Cloud Storage  |  Google Cloud](https://cloud.google.com/storage/docs/gsutil/commands/cp)
> [[assets/PCA/4e6650a33b72eacc42a71ca673aae5b1_MD5.jpeg|Open: PCA-image-20240731143111513.png]]
> ![assets/PCA/4e6650a33b72eacc42a71ca673aae5b1_MD5.jpeg](/img/user/assets/PCA/4e6650a33b72eacc42a71ca673aae5b1_MD5.jpeg)
> [New gcloud storage CLI for your data transfers | Google Cloud Blog](https://cloud.google.com/blog/products/storage-data-transfer/new-gcloud-storage-cli-for-your-data-transfers)
> gcloud storage效能較gsutil快，建議使用下面指令執行
> [[assets/PCA/9b779d062525135241747fd92f47b5e5_MD5.jpeg|Open: PCA-image-20240731172748404.png]]
> ![assets/PCA/9b779d062525135241747fd92f47b5e5_MD5.jpeg](/img/user/assets/PCA/9b779d062525135241747fd92f47b5e5_MD5.jpeg)

---
**Question #55**
**Your company is moving 75 TB of data into Google Cloud. You want to use Cloud Storage and follow Google-recommended practices. What should you do?**

- **A. Move your data onto a Transfer Appliance. Use a Transfer Appliance Rehydrator to decrypt the data into Cloud Storage.**
- **B. Move your data onto a Transfer Appliance. Use Cloud Dataprep to decrypt the data into Cloud Storage.**
- **C. Install gsutil on each server that contains data. Use resumable transfers to upload the data into Cloud Storage.**
- **D. Install gsutil on each server containing data. Use streaming transfers to upload the data into Cloud Storage.**

#### *貴公司正在將 75 TB 的資料遷移到 Google Cloud。您想要使用 Cloud Storage 並遵循 Google 推薦的做法。你該做什麼？*

- #### *A. 將您的資料移至傳輸設備上。使用 Transfer Appliance ReHydrator 將資料解密到 Cloud Storage 中。*
- #### *B. 將您的資料移至傳輸設備上。使用 Cloud Dataprep 將資料解密到 Cloud Storage。*
- #### *C. 在包含資料的每台伺服器上安裝 gsutil。使用可恢復傳輸將資料上傳至 Cloud Storage。*
- #### *D. 在每台包含資料的伺服器上安裝 gsutil。使用串流傳輸將資料上傳到雲端儲存。*

> [!NOTE]- Answer
> **A. Move your data onto a Transfer Appliance. Use a Transfer Appliance Rehydrator to decrypt the data into Cloud Storage.**
> 
> # Notes
> [概览  |  Transfer Appliance  |  Google Cloud](https://cloud.google.com/transfer-appliance/docs/4.0/overview?hl=zh-cn)
> [[assets/PCA/300a51853f7e60efe88d02248f955d48_MD5.jpeg|Open: PCA-image-20240731144018052.png]]
> ![assets/PCA/300a51853f7e60efe88d02248f955d48_MD5.jpeg](/img/user/assets/PCA/300a51853f7e60efe88d02248f955d48_MD5.jpeg)
> [Introducing Google Cloud’s Transfer Appliance - YouTube](https://youtu.be/4g2ntSRU2pI)

---
**Question #: 71**
**Your company is running a stateless application on a Compute Engine instance. The application is used heavily during regular business hours and lightly outside of business hours. Users are reporting that the application is slow during peak hours. You need to optimize the application's performance. What should you do?**

- **A. Create a snapshot of the existing disk. Create an instance template from the snapshot. Create an autoscaled managed instance group from the instance template.**
- **B. Create a snapshot of the existing disk. Create a custom image from the snapshot. Create an autoscaled managed instance group from the custom image.**
- **C. Create a custom image from the existing disk. Create an instance template from the custom image. Create an autoscaled managed instance group from the instance template.**
- **D. Create an instance template from the existing disk. Create a custom image from the instance template. Create an autoscaled managed instance group from the custom image.**

#### *您的公司在 Compute Engine 實例上運行一個無狀態應用程式。該應用程式在正常工作時間使用頻繁，而在非工作時間使用較少。使用者報告說，該應用程式在高峰時段運行緩慢。您需要優化應用程式的性能。您應該做些什麼？*

- #### *A. 建立現有磁碟的快照。從快照建立實例模板。從實例範本建立自動擴充的託管實例群組。*
- #### *B. 建立現有磁碟的快照。從快照建立自訂圖像。從自訂映像建立自動縮放的託管實例群組。*
- #### *C. 從現有磁碟建立自訂映像。從自訂鏡像建立實例模板。從實例範本建立自動擴充的託管實例群組。*
- #### *D. 從現有磁碟建立實例範本。從實例模板建立自訂圖像。從自訂映像建立自動縮放的託管實例群組。*

> [!NOTE]- Answer
> **C. Create a custom image from the existing disk. Create an instance template from the custom image. Create an autoscaled managed instance group from the instance template.**
> 
> # Notes
> 磁碟 -> 快照、映像檔
> 快照 -> 磁碟、VM
> 映像檔 -> VM
> [[assets/PCA/ad18802364b8c9164841756a8fe7ea32_MD5.jpeg|Open: PCA-image-20240801184824931.png]]
> ![assets/PCA/ad18802364b8c9164841756a8fe7ea32_MD5.jpeg](/img/user/assets/PCA/ad18802364b8c9164841756a8fe7ea32_MD5.jpeg)

---
**Question #: 72**
**Your web application has several VM instances running within a VPC. You want to restrict communications between instances to only the paths and ports you authorize, but you don't want to rely on static IP addresses or subnets because the app can autoscale. How should you restrict communications?**

- **A. Use separate VPCs to restrict traffic**
- **B. Use firewall rules based on network tags attached to the compute instances**
- **C. Use Cloud DNS and only allow connections from authorized hostnames**
- **D. Use service accounts and configure the web application to authorize particular service accounts to have access**

#### *您的網頁應用程式在 VPC 中運行着多個虛擬機器實例。您希望限制實例之間的通訊，只允許您授權的路徑和端口，但您不想依賴靜態 IP 地址或子網絡，因為應用程式可以自動縮放。您應該如何限制通訊？*

- #### *A. 使用單獨的VPC來限制流量*
- #### *B. 使用基於附加到計算實例的網路標籤的防火牆規則*
- #### *C. 使用 Cloud DNS 並僅允許來自授權主機名稱的連接*
- #### *D. 使用服務帳戶並設定 Web 應用程式以授權特定服務帳戶具有存取權限*

> [!NOTE]- Answer
> **B. Use firewall rules based on network tags attached to the compute instances**
> 
> # Notes

---
**Question #: 73**
**You are using Cloud SQL as the database backend for a large CRM deployment. You want to scale as usage increases and ensure that you don't run out of storage, maintain 75% CPU usage cores, and keep replication lag below 60 seconds. What are the correct steps to meet your requirements?**

- **A. 1. Enable automatic storage increase for the instance. 2. Create a Stackdriver alert when CPU usage exceeds 75%, and change the instance type to reduce CPU usage. 3. Create a Stackdriver alert for replication lag, and shard the database to reduce replication time.**
- **B. 1. Enable automatic storage increase for the instance. 2. Change the instance type to a 32-core machine type to keep CPU usage below 75%. 3. Create a Stackdriver alert for replication lag, and deploy memcache to reduce load on the master.**
- **C. 1. Create a Stackdriver alert when storage exceeds 75%, and increase the available storage on the instance to create more space. 2. Deploy memcached to reduce CPU load. 3. Change the instance type to a 32-core machine type to reduce replication lag.**
- **D. 1. Create a Stackdriver alert when storage exceeds 75%, and increase the available storage on the instance to create more space. 2. Deploy memcached to reduce CPU load. 3. Create a Stackdriver alert for replication lag, and change the instance type to a 32-core machine type to reduce replication lag.**

#### *您正在使用 Cloud SQL 作為大型 CRM 部署的資料庫後端。您希望隨著使用量的增加而擴展，並確保您不會耗盡儲存空間、維持 75% 的 CPU 使用率核心，並將複製延遲保持在 60 秒以下。滿足您需求的正確步驟是什麼？*

- #### *A. 1. 開啟實例儲存體自動增加功能。 2. 當CPU使用率超過75%時建立Stackdriver警報，並變更實例類型以降低CPU使用率。 3. 針對複製延遲建立 Stackdriver 警報，並對資料庫進行分片以減少複製時間。*
- #### *B. 1. 啟用實例自動儲存增加。 2. 將實例類型變更為32核心機器類型，使CPU佔用率保持在75%以下。 3. 針對複製延遲建立 Stackdriver 警報，並部署 memcache 以減少主伺服器上的負載。*
- #### *C. 1. 當儲存超過 75% 時建立 Stackdriver 警報，並增加實例上的可用儲存以建立更多空間。 2.部署memcached以減少CPU負載。 3. 將實例類型變更為32核心機器類型以減少複製延遲。*
- #### *D. 1. 當儲存超過 75% 時建立 Stackdriver 警報，並增加實例上的可用儲存以建立更多空間。 2.部署memcached以減少CPU負載。 3. 針對複製延遲建立 Stackdriver 警報，並將實例類型變更為 32 核心機器類型以減少複製延遲。*

> [!NOTE]- Answer
> **A. 1. Enable automatic storage increase for the instance. 2. Create a Stackdriver alert when CPU usage exceeds 75%, and change the instance type to reduce CPU usage. 3. Create a Stackdriver alert for replication lag, and shard the database to reduce replication time.**
> 
> # Notes
> CRM 部署是指規劃、實施和整合客戶關係管理 (CRM) 系統到企業營運的過程。它不僅僅是軟體，還涵蓋一系列的步驟，旨在確保 CRM 系統能有效地滿足企業的特定需求，並幫助其達成業務目標。

---
**Question #: 74**
**You are tasked with building an online analytical processing (OLAP) marketing analytics and reporting tool. This requires a relational database that can operate on hundreds of terabytes of data. What is the Google-recommended tool for such applications?**

- **A. Cloud Spanner, because it is globally distributed**
- **B. Cloud SQL, because it is a fully managed relational database**
- **C. Cloud Firestore, because it offers real-time synchronization across devices**
- **D. BigQuery, because it is designed for large-scale processing of tabular data**

#### **你的任務是構建一個線上分析處理 (OLAP) 行銷分析和報告工具。這需要一個能夠處理數百 TB 資料的關聯式資料庫。Google 推薦用於此類應用程式的工具是什麼？**

- #### *A. Cloud Spanner，因為它是全球分佈的*
- #### *B. Cloud SQL，因為它是完全託管的關聯式資料庫*
- #### *C. Cloud Firestore，因為它提供跨裝置即時同步*
- #### *D. BigQuery，因為它是為大規模處理表格資料而設計的*

> [!NOTE]- Answer
> **D. BigQuery, because it is designed for large-scale processing of tabular data**
> 
> # Notes
> [BigQuery 概览  |  Google Cloud](https://cloud.google.com/files/BigQueryTechnicalWP.pdf)
> [[assets/PCA/b03369543203471d7201a9b6b66af7f1_MD5.jpeg|Open: PCA-image-20240802175833487.png]]
![assets/PCA/b03369543203471d7201a9b6b66af7f1_MD5.jpeg](/img/user/assets/PCA/b03369543203471d7201a9b6b66af7f1_MD5.jpeg)

---
**Question #: 75**
**You have deployed an application to Google Kubernetes Engine (GKE), and are using the Cloud SQL proxy container to make the Cloud SQL database available to the services running on Kubernetes. You are notified that the application is reporting database connection issues. Your company policies require a post- mortem. What should you do?**

- **A. Use gcloud sql instances restart.**
- **B. Validate that the Service Account used by the Cloud SQL proxy container still has the Cloud Build Editor role.**
- **C. In the GCP Console, navigate to Stackdriver Logging. Consult logs for (GKE) and Cloud SQL.**
- **D. In the GCP Console, navigate to Cloud SQL. Restore the latest backup. Use kubectl to restart all pods.**

#### *您已將應用程式部署到 Google Kubernetes Engine (GKE)，並正在使用 Cloud SQL 代理容器，以便 Kubernetes 上運行的服務能夠訪問 Cloud SQL 資料庫。您收到警報，指出應用程式遇到資料庫連線問題。貴公司要求在此類情況下進行事後分析。您應該採取哪些步驟？*

- #### *A. 使用 gcloud sql 實例重新啟動。*
- #### *B. 驗證 Cloud SQL 代理程式容器所使用的服務帳號仍具有 Cloud Build Editor 角色。*
- #### *C. 在 GCP Console 中，導覽至 Stackdriver Logging。查看 (GKE) 和 Cloud SQL 的日誌。*
- #### *D. 在 GCP Console 中，導覽至 Cloud SQL。恢復最新的備份。使用 kubectl 重新啟動所有 pod。*

> [!NOTE]- Answer
> **C. In the GCP Console, navigate to Stackdriver Logging. Consult logs for (GKE) and Cloud SQL.**
> 
> # Notes
> [[assets/PCA/bb02c82d9afd0da5f2242a7e48ea7506_MD5.jpeg|Open: PCA-image-20240802181339830.png]]
> ![assets/PCA/bb02c82d9afd0da5f2242a7e48ea7506_MD5.jpeg](/img/user/assets/PCA/bb02c82d9afd0da5f2242a7e48ea7506_MD5.jpeg)

---
**Question #: 91**
**All Compute Engine instances in your VPC should be able to connect to an Active Directory server on specific ports. Any other traffic emerging from your instances is not allowed. You want to enforce this using VPC firewall rules.  How should you configure the firewall rules?**

- **A. Create an egress rule with priority 1000 to deny all traffic for all instances. Create another egress rule with priority 100 to allow the Active Directory traffic for all instances.**
- **B. Create an egress rule with priority 100 to deny all traffic for all instances. Create another egress rule with priority 1000 to allow the Active Directory traffic for all instances.**
- **C. Create an egress rule with priority 1000 to allow the Active Directory traffic. Rely on the implied deny egress rule with priority 100 to block all traffic for all instances.**
- **D. Create an egress rule with priority 100 to allow the Active Directory traffic. Rely on the implied deny egress rule with priority 1000 to block all traffic for all instances.**

#### *您的 VPC 中的所有 Compute Engine 執行個體都應該能夠連接到特定端口上的 Active Directory 伺服器。 來自您執行個體的任何其他流量都不允許。 您希望使用 VPC 防火牆規則來強制執行此操作。  您應該如何設定防火牆規則？*

- ##### *A. 建立一個優先順序為 1000 的出口規則，以拒絕所有執行個體的所有流量。 建立另一個優先順序為 100 的出口規則，以允許所有執行個體的 Active Directory 流量。  *
- #### *B. 建立一個優先順序為 100 的出口規則，以拒絕所有執行個體的所有流量。 建立另一個優先順序為 1000 的出口規則，以允許所有執行個體的 Active Directory 流量。*  
- #### *C. 建立一個優先順序為 1000 的出口規則，以允許 Active Directory 流量。 依靠優先順序為 100 的隱含拒絕出口規則來阻止所有執行個體的所有流量。*
- #### *D. 建立一個優先順序為 100 的出口規則，以允許 Active Directory 流量。 依靠優先順序為 1000 的隱含拒絕出口規則來阻止所有執行個體的所有流量。*

> [!NOTE]- Answer
> **A. Create an egress rule with priority 1000 to deny all traffic for all instances. Create another egress rule with priority 100 to allow the Active Directory traffic for all instances.**
> 
> # Notes
>  Cloud VPC 防火牆中，規則的優先順序決定了規則的應用順序。==數字越小，優先順序越高==

---
**Question #: 92**
**Your customer runs a web service used by e-commerce sites to offer product recommendations to users. The company has begun experimenting with a machine learning model on Google Cloud Platform to improve the quality of results.  What should the customer do to improve their model's results over time?  **

- **A. Export Cloud Machine Learning Engine performance metrics from Stackdriver to BigQuery, to be used to analyze the efficiency of the model.**
- **B. Build a roadmap to move the machine learning model training from Cloud GPUs to Cloud TPUs, which offer better results.**
- **C. Monitor Compute Engine announcements for availability of newer CPU architectures, and deploy the model to them as soon as they are available for additional performance.**
- **D. Save a history of recommendations and results of the recommendations in BigQuery, to be used as training data.**

#### *您的客戶運行一個網路服務，供電子商務網站用於向使用者提供產品推薦。 該公司已開始在 Google Cloud Platform 上試驗機器學習模型，以提高結果的質量。客戶應該怎麼做才能隨著時間的推移改善模型的結果？*

- #### *A. 將 Cloud Machine Learning Engine 性能指標從 Stackdriver 導出到 BigQuery，用於分析模型的效率。*  
- #### *B. 制定路線圖，將機器學習模型訓練從 Cloud GPU 轉移到 Cloud TPU，這將提供更好的結果。*
- #### *C. 監控 Compute Engine 公告中是否有更新的 CPU 架構，並在它們可用後立即將模型部署到它們以提高性能。* 
- #### *D. 將推薦歷史和推薦結果保存在 BigQuery 中，用於作為訓練數據*

> [!NOTE]- Answer
> **D. Save a history of recommendations and results of the recommendations in BigQuery, to be used as training data.**
> 
> # Notes
> [价格  |  Cloud TPU  |  Google Cloud](https://cloud.google.com/tpu/pricing?hl=zh-cn#estimate-cost)
> 分析模型的效率、Cloud TPU、更新CPU 架構 這些都是提高速度和優化性能，而不是模型結果質量
> Cloud TPU（Tensor Processing Unit）是 Google 專為機器學習工作負載設計的客製化機器學習加速器
> [[assets/PCA/1d946d376626b6952258a3a3df36ef2c_MD5.jpeg|Open: PCA-image-20240805151338306.png]]
> ![assets/PCA/1d946d376626b6952258a3a3df36ef2c_MD5.jpeg](/img/user/assets/PCA/1d946d376626b6952258a3a3df36ef2c_MD5.jpeg)

---
**Question #: 93**
**A development team at your company has created a dockerized HTTPS web application. You need to deploy the application on Google Kubernetes Engine (GKE) and make sure that the application scales automatically.  How should you deploy to GKE?  **

- **A. Use the Horizontal Pod Autoscaler and enable cluster autoscaling. Use an Ingress resource to load-balance the HTTPS traffic.**
- **B. Use the Horizontal Pod Autoscaler and enable cluster autoscaling on the Kubernetes cluster. Use a Service resource of type LoadBalancer to load-balance the HTTPS traffic.**
- **C. Enable autoscaling on the Compute Engine instance group. Use an Ingress resource to load-balance the HTTPS traffic.**
- **D. Enable autoscaling on the Compute Engine instance group. Use a Service resource of type LoadBalancer to load-balance the HTTPS traffic.**

#### *您公司的開發團隊創建了一個 Docker 化的 HTTPS 網路應用程式。 您需要將應用程式部署在 Google Kubernetes Engine (GKE) 上，並確保應用程式自動擴展。 您應該如何部署到 GKE？*

- #### *A. 使用 Horizontal Pod Autoscaler 並啟用叢集自動擴展。 使用 Ingress 資源來負載平衡 HTTPS 流量。*  
- #### *B. 使用 Horizontal Pod Autoscaler 並在 Kubernetes 叢集上啟用叢集自動擴展。 使用類型為 LoadBalancer 的 Service 資源來負載平衡 HTTPS 流量。*
- #### *C. 在 Compute Engine 執行個體群組上啟用自動擴展。 使用 Ingress 資源來負載平衡 HTTPS 流量*。  
- #### *D. 在 Compute Engine 執行個體群組上啟用自動擴展。 使用類型為 LoadBalancer 的 Service 資源來負載平衡 HTTPS 流量。*

> [!NOTE]- Answer
> **A. Use the Horizontal Pod Autoscaler and enable cluster autoscaling. Use an Ingress resource to load-balance the HTTPS traffic.**
> 
> # Notes
> [自动扩缩集群  |  Google Kubernetes Engine (GKE)  |  Google Cloud](https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-autoscaler?hl=zh-cn)
> [使用 Ingress 设置外部应用负载均衡器  |  Kubernetes Engine  |  Google Cloud](https://cloud.google.com/kubernetes-engine/docs/tutorials/http-balancer?hl=zh-cn)
> 使用 LoadBalancer 類型的 Service 資源會為每個服務創建一個外部負載平衡器，這可能會增加成本和複雜性。 Ingress 資源更適合用於管理多個服務的 HTTPS 流量。因為 Compute Engine 執行個體群組的自動擴展，這不適用於 GKE

---
**Question #: 94**
**You need to design a solution for global load balancing based on the URL path being requested. You need to ensure operations reliability and end-to-end in- transit encryption based on Google best practices.  What should you do?**

- **A. Create a cross-region load balancer with URL Maps.**
- **B. Create an HTTPS load balancer with URL Maps.**
- **C. Create appropriate instance groups and instances. Configure SSL proxy load balancing.**
- **D. Create a global forwarding rule. Configure SSL proxy load balancing.**

#### *您需要根據所請求的 URL 路徑設計全球負載平衡的解決方案。您需要根據 Google 最佳實務確保操作可靠性和端到端傳輸中加密。  您應該怎麼做？*

- #### *A. 使用 URL 映射創建跨區域負載平衡器。*
- #### *B. 使用 URL 映射創建 HTTPS 負載平衡器。*
- #### *C. 創建適當的執行個體群組和執行個體。 配置 SSL 代理負載平衡。*
- #### *D. 創建全球轉發規則。 配置 SSL 代理負載平衡。*

> [!NOTE]- Answer
> **B. Create an HTTPS load balancer with URL Maps.**
> 
> # Notes
> [使用网址映射  |  Load Balancing  |  Google Cloud](https://cloud.google.com/load-balancing/docs/https/url-map)
> [[assets/PCA/84bf15f700abf04436a99064c877f8e3_MD5.jpeg|Open: PCA-image-20240805161505237.png]]
![assets/PCA/84bf15f700abf04436a99064c877f8e3_MD5.jpeg](/img/user/assets/PCA/84bf15f700abf04436a99064c877f8e3_MD5.jpeg)

---
**Question #: 95**
**You have an application that makes HTTP requests to Cloud Storage. Occasionally the requests fail with HTTP status codes of 5xx and 429.  How should you handle these types of errors?**  

- **A. Use gRPC instead of HTTP for better performance.**
- **B. Implement retry logic using a truncated exponential backoff strategy.**
- **C. Make sure the Cloud Storage bucket is multi-regional for geo-redundancy.**
- **D. Monitor https://status.cloud.google.com/feed.atom and only make requests if Cloud Storage is not reporting an incident.**

#### *您有一個應用程式會向 Cloud Storage 發出 HTTP 請求。 有時請求會失敗，並顯示 5xx 和 429 的 HTTP 狀態碼。  您應該如何處理這些類型的錯誤？*

- #### *A. 使用 gRPC 代替 HTTP 以獲得更好的性能。*  
- #### *B. 使用截斷的指數退避策略實現重試邏輯。*  
- #### *C. 確保 Cloud Storage 儲存貯體是多區域的，以實現地理冗餘。*  
- #### *D. 監控 [https://status.cloud.google.com/feed.atom，並且僅在](https://status.cloud.google.com/feed.atom%EF%BC%8C%E4%B8%A6%E4%B8%94%E5%83%85%E5%9C%A8) Cloud Storage 未報告事件時才發出請求。*

> [!NOTE]- Answer
> **B. Implement retry logic using a truncated exponential backoff strategy.**
> 
> # Notes
> [HTTP status and error codes for JSON  |  Cloud Storage  |  Google Cloud](https://cloud.google.com/storage/docs/json_api/v1/status-codes)
> [Retry — google-api-core documentation](https://googleapis.dev/python/google-api-core/latest/retry.html)
> 5xx 錯誤：表示伺服器端錯誤，通常是暫時的。
> 429 錯誤：表示請求過多，通常是由於請求速率過高造成的。
> 
> 截斷的指數退避策略：一種標準的重試機制，可以有效地處理這些類型的錯誤
> - 指數退避：每次重試之間的延遲時間會呈指數增長，避免過度請求伺服器。
> - 截斷：設定最大重試次數和最大延遲時間，避免無限期重試。

---