# AWS-Cloudwatch-Agent-Template
## 前言
預設Cloudwatch Agent所丟出的Ｍemory與Disk指標，都會包含ami與instance type，以致於規格調整後會Alarm會抓不到資料。另外，Windows與Linux預設指標名稱的不同，會增加ES撈取時的難度。    

因此，在此處提供Ｗindows與Linux的CloudWatch Agent Template。    

namespace是CWAgent， 才會顯示在EC2內的Monitoring。    
