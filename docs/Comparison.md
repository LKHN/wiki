---
title: "EL8 Distro Comparison"
---

| Benchmarking against RHEL                  | AlmaLinux                | Oracle Linux                                   | Rocky Linux                                 | CentOS Stream     | CentOS Linux      |
| -------------------------------------------|--------------------------|------------------------------------------------|-------------------------------------------- |-------------------|-------------------|
|Production Version                          | Since March 2021         | Since 2006                                     | Since June 2021                          | Since 2019        | Since 2004        |
|Strives 1:1 binary RHEL binary compatibility| Yes                      | Almost\*<br/>(some divergance in glibc, openssl and other components)                      | Yes                                         | Compatible within the limits of the [ACG][acg] | Yes               |
|Regular updates delay                       | About 1 business day     | About 1 business day                           | About 1 business day                        | Upstream of RHEL  | About 1 business day |
|Last minor version release delay            | 8 days                   | 8 days                                         | 34 days                                     | N/A               | 16 days           |
|Errata                                      | Yes                      | Yes                                            | Yes                                         | No                | No                |
|Lifecycle                                   | 10 Years                 | 10 Years                                       | 10 Years                                    | 5-6 Years         | EOL on 2021-12-31 |
|Commercial support                          | 3rd party                | Oracle, 3rd parties                            | 3rd Party                                   | 3rd party         | 3rd party         |
|Livepatching service                        | KernelCare               | Oracle Ksplice, KernelCare Available           | KernelCare Available                      | Not available     | KernelCare, Kpatch |
|FIPS compliance                             | Planned Q1, 2022         | Yes                                            | Planned                                     | Not available     | Not available        |
|ARM support                                 | Yes                      | Yes                                            | Yes                                        | Yes               | Yes               |
|PowerPC support                             | Planned Q3, 2021         | Yes                                            | Planned                                     | Yes               | Yes               |
|SecureBoot                                  | Yes                      | Yes                                            | Planned                                     | Yes               | Yes               |
|Owned By:                                   | AlmaLinux OS Foundation  | Oracle Inc                                     | Rocky Enterprise Software Foundation        | Red Hat Inc       | Red Hat Inc       |
|Owned by org type:                          | Non-Profit 501(c)6       | For Profit C-Corp                              | For Profit, Public Benefit Corp             | For Profit C-Corp | For Profit C-Corp |

[acg]: https://access.redhat.com/articles/rhel8-abi-compatibility
