## This will give the users access for what they need to get their job done and nothing else. The second recommendation the organization will implement is continuous monitoring. This will ensure each group is being held accountable for their actions. We can continue to monitor each profile throughout the day whether its manually or automated. We will have an automated system detected activity throughout the infrastructure that will signal a notification to upper management to investigate what the issue might be and to take immediate action. This will help monitor the access for the principle of least privilege to know if it’s working or not. The third recommendation would be to implement the separation of duties role to further enhance a user’s role. Individuals will be assigned a separation of duties role within the department to break it into subgroups that will be responsible to complete certain part of tasks. The accounting department will have one user printing the checks, the second user will sign the checks, and the third user will mail the checks out. This ensures there’s always a second opinion for every job to ensure we are completing it properly. The pictures below represent how the organization will assign each role for the role-based access controls. This will include the Accounting Resource Group, IT Resource Group, and Marketing Resource Group.

![Architecture Diagram](https://i.imgur.com/hjAPnVQ.png)

![Architecture Diagram](https://i.imgur.com/ZwA32ji.png)

![Architecture Diagram](https://i.imgur.com/aKp49Lq.png)

![Architecture Diagram](https://i.imgur.com/0jfJs0F.png)

![Architecture Diagram](https://i.imgur.com/Sw5frJH.png)

![Architecture Diagram](https://i.imgur.com/pMNF3cc.png)

## The 1st best practices for the Azure Key Vaults are to assign the roles for the principle of least privileges so users would only have access to what they need to complete their work. The account resource group, IT resource group, and marketing resource should have their own key vault assigned to them. This ensures that no other department could gain access to another department’s accounts. This would follow the best practices because we wouldn’t want a user from IT to gain access to view data that only an accounting user would see. The 2nd best practice is to update the key vaults because if you are using the same key for years, it may induce an attack from an outsider that could figure out the vulnerabilities. This would also protect the organization from being attacked from a user who is employed by the company. A user could find out the key and secretly modify or steal documents. We need to ensure all data is safe regardless of the state it's in.
The first recommendation for how we can encrypt each key vault for both data at rest and data in transit is to apply a disk encryption to help safeguard the organizations data. 
My second recommendation is to use SSL/TLS protocols to exchange data across the infrastructure to ensure we are following best practices by storing and transferring data safely. This would help the organization know that the data doesn’t include any malicious activities. 
Another recommendation we could do to be safe is by having our users connect onto a VPN and only use website addresses that start with HTTPS.


![Architecture Diagram](https://i.imgur.com/wSXhyGB.png)

![Architecture Diagram](https://i.imgur.com/Vx1QpQt.png)

![Architecture Diagram](https://i.imgur.com/6TUmYV7.png)

As shown in the pictures, we created a new backup policy that meets the guidelines and best practices to have a backup scheduled daily at 7p.m. Eastern Standard Time. This will serve an instant restore and recovery snapshot for 3 days, as well as maintaining a retention of daily backup points taken every day at 7p.m. for 45 days before it is permanently deleted. The IT department will ensure to test and update the backups quarterly so we’re maintaining our due diligence for the people and our organization. If there are any incidents and data has been modified or stolen, we will have quick access to recover the information.
