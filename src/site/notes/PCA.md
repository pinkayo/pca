---
{"dg-publish":true,"permalink":"/PCA/","tags":["gardenEntry"]}
---

**Question #6
**You need to reduce the number of unplanned rollbacks of erroneous production deployments in your company's web hosting platform. Improvement to the QA/  
Test processes accomplished an 80% reduction.  
Which additional two approaches can you take to further reduce the rollbacks? (Choose two.)**
*要進一步減少公司網頁托管平台因意外部署錯誤而導致的回滾次數，除了改進品質保證/測試流程已經達到80%的減少外，你還可以採取以下哪兩種方法（選兩項）*

- **A. Introduce a green-blue deployment model
- *引入綠藍部署模型*
- 
- **B. Replace the QA environment with canary releases 
- *將QA環境替換為金絲雀發佈*
- 
- **C. Fragment the monolithic platform into microservices 
- *將單體平台分解為微服務*
- 
- **D. Reduce the platform's dependency on relational database systems 
- *減少平台對關係型數據庫系統的依賴*
- 
- **E. Replace the platform's relational database systems with a NoSQL database 
- *將平台的關係型數據庫系統替換為NoSQL數據庫*


---
**Question #7
**To reduce costs, the Director of Engineering has required all developers to move their development infrastructure resources from on-premises virtual machines  
(VMs) to Google Cloud Platform. These resources go through multiple start/stop events during the day and require state to persist. You have been asked to design the process of running a development environment in Google Cloud while providing cost visibility to the finance department.  
Which two steps should you take? (Choose two.)**
*為了降低成本，工程總監要求所有開發人員將其開發基礎設施資源從本地虛擬機器 (VM) 遷移到 Google Cloud Platform。這些資源在一天中會經歷多個啟動/停止事件，並且需要保持狀態。我們要求您設計在 Google Cloud 中運行開發環境的流程，同時向財務部門提供成本可見度。 （選兩個。）*

- **A. Use the - -no-auto-delete flag on all persistent disks and stop the VM Most Voted
- *在所有永久磁碟上使用 - -no-auto-delete 標誌並停止 VM*
- 
- **B. Use the - -auto-delete flag on all persistent disks and terminate the VM
- *在所有永久磁碟上使用 --auto-delete 標誌並終止 VM*
- 
- **C. Apply VM CPU utilization label and include it in the BigQuery billing export
- *應用虛擬機器 CPU 使用率標籤並將其包含在 BigQuery 計費匯出中*
- 
- **D. Use Google BigQuery billing export and labels to associate cost to groups Most Voted
- *使用 Google BigQuery 結算匯出和標籤將成本與投票最多的群組關聯起來*
- 
- **E. Store all state into local SSD, snapshot the persistent disks, and terminate the VM
- *將所有狀態儲存到本機 SSD、對永久磁碟進行快照並終止 VM*
- 
- **F. Store all state in Google Cloud Storage, snapshot the persistent disks, and terminate the VM
- *將所有狀態儲存在 Google Cloud Storage 中，對永久性磁碟進行快照，並終止 VM*


---
**Question #8
**Your company wants to track whether someone is present in a meeting room reserved for a scheduled meeting. There are 1000 meeting rooms across 5 offices on 3 continents. Each room is equipped with a motion sensor that reports its status every second. The data from the motion detector includes only a sensor ID and several different discrete items of information. Analysts will use this data, together with information about account owners and office locations.  
Which database type should you use?**
*您的公司希望追蹤是否有人出現在已安排的會議室中。在3大洲的5個辦事處設有1000間會議室。每個房間都配備了一個運動感測器，每秒報告一次狀態。來自運動檢測器的數據僅包括一個感測器ID和幾個不同的離散資訊項。分析師將使用這些數據，以及有關帳戶擁有者和辦公地點的資訊。 應該使用哪種資料庫類型？

- **A. Flat file
- *平面文件*
- 
- **B. NoSQL
- *非關聯式資料庫*
- 
- **C. Relational
- *關聯式資料庫*
- 
- **D. Blobstore
- *二進位大物件儲存*

PS.
[[assets/PCA/016d1bf99ebec9b21cbae152ab221998_MD5.jpeg|Open: PCA-image-20240708161418136.png]]
![assets/PCA/016d1bf99ebec9b21cbae152ab221998_MD5.jpeg](/img/user/assets/PCA/016d1bf99ebec9b21cbae152ab221998_MD5.jpeg)

[[assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg|Open: PCA-image-20240708161421503.png]]
![assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg](/img/user/assets/PCA/ba052f1a4de9282928dfb69f8565671d_MD5.jpeg)



---
**Question #9
**You set up an autoscaling instance group to serve web traffic for an upcoming launch. After configuring the instance group as a backend service to an HTTP(S) load balancer, you notice that virtual machine (VM) instances are being terminated and re-launched every minute. The instances do not have a public IP address.  
You have verified the appropriate web response is coming from each instance using the curl command. You want to ensure the backend is configured correctly.  
What should you do?
*您可以設置一個自動擴展實例組，以便為即將啟動的 Web 流量提供服務。將實例組配置為 HTTP（S） 負載均衡器的後端服務後，您會注意到虛擬機 （VM） 實例每分鐘都會被終止並重新啟動。實例沒有公有IP位址。 您已使用 curl 命令驗證每個實例是否發出了相應的 Web 回應。您希望確保後端配置正確。 你應該怎麼做？*

- **A. Ensure that a firewall rules exists to allow source traffic on HTTP/HTTPS to reach the load balancer.
- *確保存在防火牆規則，以允許 HTTP/HTTPS 上的源流量到達負載均衡器。*
- 
- **B. Assign a public IP to each instance and configure a firewall rule to allow the load balancer to reach the instance public IP.
- *為每個實例分配一個公有IP，並配置防火牆規則以允許負載均衡器訪問實例公有IP。*
- 
- **C. Ensure that a firewall rule exists to allow load balancer health checks to reach the instances in the instance group.
- *確保存在防火牆規則，以允許負載均衡器運行健康檢查訪問實例組中的實例*
- 
- **D. Create a tag on each instance with the name of the load balancer. Configure a firewall rule with the name of the load balancer as the source and the instance tag as the destination.
- *在每個實例上創建一個帶有負載均衡器名稱的標籤。配置防火牆規則，將負載均衡器的名稱作為源，將實例標籤作為目標*

PS.
[后端服务概览  |  Load Balancing  |  Google Cloud](https://cloud.google.com/load-balancing/docs/backend-service?hl=zh-cn)
防火牆與健康檢查
[[assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg|Open: PCA-image-20240708153509944.png]]
![assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg](/img/user/assets/PCA/d27dcffbcc12470c7f88480fdd709824_MD5.jpeg)

[[assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg|Open: PCA-image-20240708154358114.png]]
![assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg](/img/user/assets/PCA/07fa66875f3dfaf0730678ca400162d8_MD5.jpeg)





---
**Question #10
**You write a Python script to connect to Google BigQuery from a Google Compute Engine virtual machine. The script is printing errors that it cannot connect to  
BigQuery.  
What should you do to fix the script?
*您編寫了一個 Python 腳本以從 Google Compute Engine 虛擬機連接到 Google BigQuery。腳本顯示無法連接到BigQuery的錯誤 。 你應該怎麼做才能修復腳本？*

- **A. Install the latest BigQuery API client library for Python
- *安裝適用於 Python 的最新 BigQuery API 用戶端庫*
- 
- **B. Run your script on a new virtual machine with the BigQuery access scope enabled
- *啟用了 BigQuery 存取權限範圍的新虛擬機上運行腳本*
- 
- **C. Create a new service account with BigQuery access and execute your script with that user
- *建立一個具有 BigQuery 訪問許可權的新服務帳號，並使用該使用者執行腳本*
- 
- **D. Install the bq component for gcloud with the command gcloud components install bq.
- *使用命令 gcloud components install bq 安裝 gcloud 的 bq 元件

PS.
[为 API 请求授权  |  BigQuery  |  Google Cloud](https://cloud.google.com/bigquery/docs/authorization?hl=zh-cn#client-libraries)
服務帳戶建立
[[assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg|Open: PCA-image-20240708152529305.png]]
![assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg](/img/user/assets/PCA/d7db03f1d216b322ad058f7629267b58_MD5.jpeg)

