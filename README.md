Deploy a Serverless project basic example
======
---
  * In AWS > IAM console > New user > retrieve key + secret
    * give relevant username
    * select access type 'programmatic access'
    * select 'attach existing policy directly' (admin access policy was used for this example)
  * In cli > sls config credentials --provider aws --key [KEY HERE] --secret [SECRET HERE]
  * sls create --template aws-nodejs
  * update handler and .yaml file accordingly with service name
  * add desired code/behavior to handler.js
  * invoke functions locally w/  
    ` sls invoke local -f handleHtp -d '{"name":"Lyons"}' `
  * sls deploy  
---

U: DocMakerUser
Access key ID : AKIAILIZ24SCMXA26NTQ
Secret access key : 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

---
