## This approach ensures that users have access only to the resources necessary for their job functions, promoting efficiency and security. The second recommendation is to implement continuous monitoring, which will hold each group accountable for their actions. We will track user activity throughout the day, utilizing both manual and automated methods. An automated system will detect significant activities within the infrastructure and trigger notifications to upper management for immediate investigation, ensuring we uphold the principle of least privilege. The third recommendation involves establishing a separation of duties within departments to enhance accountability and oversight. By assigning distinct roles—such as one user responsible for printing checks, another for signing them, and a third for mailing them—we ensure that no single individual has unchecked control over critical tasks. This approach fosters a system of checks and balances, enhancing the integrity of our processes. The accompanying diagrams illustrate how the organization will assign roles within the Accounting, IT, and Marketing Resource Groups under the role-based access control framework.

![Architecture Diagram](https://i.imgur.com/hjAPnVQ.png)

![Architecture Diagram](https://i.imgur.com/ZwA32ji.png)

![Architecture Diagram](https://i.imgur.com/aKp49Lq.png)

![Architecture Diagram](https://i.imgur.com/0jfJs0F.png)

![Architecture Diagram](https://i.imgur.com/Sw5frJH.png)

![Architecture Diagram](https://i.imgur.com/pMNF3cc.png)

## The first best practice for Azure Key Vaults is to implement role assignments based on the principle of least privilege, ensuring that users only have access to the resources necessary for their tasks. Each department—such as Accounting, IT, and Marketing—should have its own dedicated Key Vault, preventing unauthorized access across departments. This practice is essential to maintain confidentiality, as it ensures that an IT user cannot view sensitive data intended solely for accounting personnel.

## The second best practice is to regularly update Key Vaults. Using the same key for an extended period can expose the organization to potential attacks, as external threats may exploit vulnerabilities. Additionally, it mitigates risks from internal users who might discover keys and manipulate or steal sensitive documents. Safeguarding all data, regardless of its state, is paramount.

## To enhance security, my first recommendation is to implement disk encryption for each Key Vault to protect the organization’s data both at rest and in transit. Additionally, utilizing SSL/TLS protocols for data exchange across the infrastructure will ensure that we are adhering to best practices by securely storing and transferring information, reducing the risk of malicious activity.

## Finally, I recommend that users connect through a VPN and only access websites that begin with HTTPS. This will further secure our data and protect against potential threats.


![Architecture Diagram](https://i.imgur.com/wSXhyGB.png)

![Architecture Diagram](https://i.imgur.com/Vx1QpQt.png)

![Architecture Diagram](https://i.imgur.com/6TUmYV7.png)

<p> As illustrated in the accompanying images, we have established a new backup policy that aligns with industry guidelines and best practices. This policy schedules daily backups at 7 p.m. Eastern Standard Time, providing an instant restore and recovery snapshot that is retained for three days. Additionally, we will maintain daily backup points for 45 days before permanent deletion. The IT department is committed to testing and updating these backups on a quarterly basis to ensure we uphold our responsibility to both our employees and the organization. In the event of an incident involving data modification or theft, we will have swift access to recover the necessary information. </p>
