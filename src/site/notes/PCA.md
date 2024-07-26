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

<details>
<summary>答案</summary> 
A. Introduce a green-blue deployment model<br>
C. Fragment the monolithic platform into microservices<br>
</details>

# Notes
增加穩定度方式：容器化部署、負載平衡

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

<details>
<summary>答案</summary>
A. Use the - -no-auto-delete flag on all persistent disks and stop the VM<br>
D. Use Google BigQuery billing export and labels to associate cost to groups Most Voted<br>
</details>

# Notes
[gcloud compute instances set-disk-auto-delete  |  Google Cloud CLI Documentation](https://cloud.google.com/sdk/gcloud/reference/compute/instances/set-disk-auto-delete#--auto-delete)
[将 Cloud Billing 数据导出到 BigQuery  |  Google Cloud](https://cloud.google.com/billing/docs/how-to/export-data-bigquery?hl=zh-cn)
[[assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg|Open: PCA-image-20240708182619467.png]]
![assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg](/img/user/assets/PCA/859b86983af5ea6e53247e66d1727c84_MD5.jpeg)
匯出
[[assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg|Open: PCA-image-20240708184058884.png]]
![assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg](/img/user/assets/PCA/e51dedaf7827d08a2e0fabafff5bde87_MD5.jpeg)

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

<details>
<summary>答案</summary>
B. NoSQL<br>
</details>

# Notes
[[assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg|Open: PCA-image-20240708173116708.png]]
![assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg](/img/user/assets/PCA/d03a3f5cd1263539dc7e7fe4e146b8f9_MD5.jpeg)

[[assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg|Open: PCA-image-20240708161421503.png]]
![assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg](/img/user/assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg)

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

<details>
<summary>答案</summary>
C. Ensure that a firewall rule exists to allow load balancer health checks to reach the instances in the instance group<br>
</details>

# Notes
[后端服务概览  |  Load Balancing  |  Google Cloud](https://cloud.google.com/load-balancing/docs/backend-service?hl=zh-cn)
防火牆與健康檢查
[[assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg|Open: PCA-image-20240708153509944.png]]
![assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg](/img/user/assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg)

[[assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg|Open: PCA-image-20240708154358114.png]]
![assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg](/img/user/assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg)

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

<details>
<summary>答案</summary>
C. Create a new service account with BigQuery access and execute your script with that user<br>
</details>

# Notes
[为 API 请求授权  |  BigQuery  |  Google Cloud](https://cloud.google.com/bigquery/docs/authorization?hl=zh-cn#client-libraries)
服務帳戶建立
[[assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg|Open: PCA-image-20240708152529305.png]]
![assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg](/img/user/assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg)

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

<details>
<summary>答案</summary>
D. Configure Stackdriver Monitoring for all Projects, and export to Google Cloud Storage<br>
</details>

# Notes
[将日志路由到支持的目的地  |  Cloud Logging  |  Google Cloud](https://cloud.google.com/logging/docs/export/configure_export_v2?hl=zh-cn)
預設保留策略：
保留最新6週監控數據

匯出設定方式：
[[assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg|Open: PCA-image-20240710163111852.png]]
![assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg](/img/user/assets/PCA/1f63295ec5b54b7abd5cf1fbbfd76bad_MD5.jpeg)


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

<details>
<summary>答案</summary>
A. Google Cloud Dedicated Interconnect<br>
</details>

# Notes
[专用互连概览  |  Cloud Interconnect  |  Google Cloud](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/dedicated-overview?hl=zh-cn)
[Cloud VPN 概览  |  Google Cloud](https://cloud.google.com/network-connectivity/docs/vpn/concepts/overview?hl=zh-cn)
[[assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg|Open: PCA-image-20240716104810403.png]]
![assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg](/img/user/assets/PCA/b3dd78be333d44a28b94e3e87da7e6da_MD5.jpeg)

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

<details>
<summary>答案</summary>
B. Enable Logging export to Google BigQuery and use ACLs and views to scope the data shared with the auditor<br>
</details>

# Notes
[负有审核相关工作职责的 IAM 角色  |  IAM 文档  |  Google Cloud](https://cloud.google.com/iam/docs/job-functions/auditing?hl=zh-cn#scenario_external_auditors)
[[assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg|Open: PCA-image-20240715165522502.png]]
![assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg](/img/user/assets/PCA/3582b68e616b266121c28960d7f48756_MD5.jpeg)
[[assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg|Open: PCA-image-20240715165532896.png]]
![assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg](/img/user/assets/PCA/bc95a640dfe71a375e4f5a2458d3f3aa_MD5.jpeg)
[[assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg|Open: PCA-image-20240715172936030.png]]
![assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg](/img/user/assets/PCA/368cc8498efbb0cd8b9938857721808f_MD5.jpeg)
[[assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg|Open: PCA-image-20240715173107356.png]]
![assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg](/img/user/assets/PCA/80d4247945b5c64b6bd627ff7ee6ac2b_MD5.jpeg)
[[assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg|Open: PCA-image-20240715173117999.png]]
![assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg](/img/user/assets/PCA/0a2b1232ce01e7ab6cbf00ddf84e28c2_MD5.jpeg)

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

<details>
<summary>答案</summary>
C. In a secret management system<br>
</details>

# Notes
[Secret Manager 概览  |  Secret Manager Documentation  |  Google Cloud](https://cloud.google.com/secret-manager/docs/overview?hl=zh-cn)
[[assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg|Open: PCA-image-20240715155416901.png]]
![assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg](/img/user/assets/PCA/becfe552b43c53369e1e483ed86cc705_MD5.jpeg)

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

<details>
<summary>答案</summary>
C. Cloud Deployment Manager is unfamiliar to the company's engineers<br>
F. Cloud Deployment Manager only supports automation of Google Cloud resources<br>
</details>

# Notes
[Google Cloud Deployment Manager 文档  |  Cloud Deployment Manager Documentation](https://cloud.google.com/deployment-manager/docs?hl=zh-cn)
[[assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg|Open: PCA-image-20240715145659726.png]]
![assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg](/img/user/assets/PCA/3cf7a2d93afe6e127a9b729d2bdf5f4c_MD5.jpeg)

[[assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg|Open: PCA-image-20240716164512964.png]]
![assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg](/img/user/assets/PCA/dfff71624b3f70bac0ad04b4cc913c31_MD5.jpeg)

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

<details>
<summary>答案</summary>
A. Point gcloud datastore create-indexes to your configuration file<br>
</details>

# Notes


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
- #### *D. 在兩個 Compute Engine 實例群組上部署應用程序，每個實例組位於單獨的項目和不同的區域。使用第一個實例組來提供流量，並使用 HTTP 負載平衡服務在災難發生時故障轉移到備用實例組。*

<details>
<summary>答案</summary>
C. Deploy the application on two Compute Engine instance groups, each in the same project but in a different region. Use the first instance group to serve traffic, and use the HTTP load balancing service to fail over to the standby instance group in case of a disaster.<br>
</details>

# Notes


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
- #### *C. 在 App Engine 彈性環境中部署您的應用程序，並使用 App Engine 防火牆規則來限制對本機資料庫的存取。*
- #### *D. 在 App Engine 靈活環境上部署您的應用程序，並使用 Cloud VPN 限制對本地資料庫的存取。*

<details>
<summary>答案</summary>
D. Deploy your application on App Engine flexible environment and use Cloud VPN to limit access to the on-premises database.<br>
</details>

# Notes


---
**Question #54**
**You are working in a highly secured environment where public Internet access from the Compute Engine VMs is not allowed. You do not yet have a VPN connection to access an on-premises file server. You need to install specific software on a Compute Engine instance. How should you install the software?**

- **A. Upload the required installation files to Cloud Storage. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gsutil.**
- **B. Upload the required installation files to Cloud Storage and use firewall rules to block all traffic except the IP address range for Cloud Storage. Download the files to the VM using gsutil.**
- **C. Upload the required installation files to Cloud Source Repositories. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gcloud.**
- **D. Upload the required installation files to Cloud Source Repositories and use firewall rules to block all traffic except the IP address range for Cloud Source Repositories. Download the files to the VM using gsutil.**

#### *您正在高度安全的環境中工作，不允許從 Compute Engine 虛擬機器存取公共互聯網。您還沒有用於存取本機檔案伺服器的 VPN 連線。您需要在 Compute Engine 實例上安裝特定軟體。您應該如何安裝該軟體？*

- #### *A. 將所需的安裝檔案上傳到雲端儲存。在具有專用 Google Access 子網路的子網路上設定虛擬機器。僅向 VM 指派內部 IP 位址。使用 gsutil 將安裝檔下載到 VM。*
- #### *B. 將所需的安裝檔案上傳到雲端存儲，並使用防火牆規則阻止除雲端儲存的 IP 位址範圍之外的所有流量。使用 gsutil 將檔案下載到 VM。*
- #### *C. 將所需的安裝檔案上傳至 Cloud Source Repositories。在具有專用 Google Access 子網路的子網路上設定虛擬機器。僅向 VM 指派內部 IP 位址。使用 gcloud 將安裝檔下載到虛擬機器。*
- #### *D. 將所需的安裝檔案上傳到雲端來源庫，並使用防火牆規則阻止除雲端來源庫 IP 位址範圍之外的所有流量。使用 gsutil 將檔案下載到 VM。*

<details>
<summary>答案</summary>
A. Upload the required installation files to Cloud Storage. Configure the VM on a subnet with a Private Google Access subnet. Assign only an internal IP address to the VM. Download the installation files to the VM using gsutil.<br>
</details>

# Notes


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

<details>
<summary>答案</summary>
A. Move your data onto a Transfer Appliance. Use a Transfer Appliance Rehydrator to decrypt the data into Cloud Storage.<br>
</details>

# Notes


---
 
> [!NOTE]- Title
> Contents

