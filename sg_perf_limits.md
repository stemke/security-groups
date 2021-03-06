---



copyright:
  years: 2017
lastupdated: "2017-08-10"


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Performance limitations for security groups (Beta)

Some performance limitations exist for security groups and their associated rules. 
{:shortdesc}

| Resource                                                  | Limit                                               |
| --------------------------------------------------------- | --------------------------------------------------- |
| Security groups per network interface                     | 5                                                   |
| Security groups per account                               | 100                                                 |
| Rules per security group                                  | 40                                                  |
| Remote rules per security group                           | 5                                                   |
| Network interfaces per security group                     | 40                                                  | 
{: caption="Table 3. Performance limitations for specific resources" caption-side="top"} 

**Note:** A remote rule is one that specifies a security group as the source or destination.
