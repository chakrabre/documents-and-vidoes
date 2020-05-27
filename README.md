# documents-and-vidoes
documents and videos
https://www.youtube.com/channel/UC_evcfxhjjui5hChhLE08tQ/videos

https://www.youtube.com/watch?v=GERLacyOTeg

1. Kubernetes cheat sheet: https://lnkd.in/e5huKvG
https://cheatsheet.dennyzhang.com/cheatsheet-kubernetes-a4

2. Docker cheat sheet: https://lnkd.in/euVgEym
https://www.docker.com/sites/default/files/d8/2019-09/docker-cheat-sheet.pdf?utm_source=twitter&utm_medium=social&utm_campaign=dockercheatsheet&utm_content=dockercheatsheet&utm_term=dockercheatsheet&utm_budget=&utm_content=1574461716

3. Git and GitHub cheat sheet: https://lnkd.in/eqmYz7Y
https://dev.to/zinox9/git-github-cheatsheet-22ok

4. Ansible cheat sheet: https://lnkd.in/eUcJGfW
https://sites.google.com/site/mrxpalmeiras/ansible/ansible-cheat-sheet

5. Linux command cheat sheet: https://lnkd.in/eemfYJU
https://linoxide.com/linux-command/linux-commands-cheat-sheet/

6. Open Shift cheat sheet: https://lnkd.in/euUv23d
http://www.mastertheboss.com/soa-cloud/openshift/openshift-cheatsheet

7. Helm cheat sheet: https://lnkd.in/eupFcpy
https://gist.github.com/tuannvm/4e1bcc993f683ee275ed36e67c30ac49



8. Jenkins cheat sheet: https://lnkd.in/eEdSkWX
https://miro.medium.com/max/1400/1*5tZVl-tqZwSoxH97v4u45w.png

https://www.docker.com/sites/default/files/d8/2019-09/docker-cheat-sheet.pdf?utm_source=twitter&utm_medium=social&utm_campaign=dockercheatsheet&utm_content=dockercheatsheet&utm_term=dockercheatsheet&utm_budget=&utm_content=1574461716

Kubernetes security best practices
https://www.stackrox.com/post/2020/05/kubernetes-security-101/

Nginx reverse proxy 

https://www.scaleway.com/en/docs/how-to-configure-nginx-reverse-proxy/

Ansible playbooks :

https://www.bogotobogo.com/DevOps/Ansible/Ansible-Handlers.php

Reverse Proxy :

https://dzone.com/articles/10-tips-for-10x-application-performance


Nginx Reverse Proxy :

Solution for Database Latency 1 :  Configure NGINX  Plus  as a Reverse proxy:
Proxy will sits between our clients and the internet, which acts as a intermediate layer and used within the org to monitor the web traffic post the deployments.
Web applications often run slowly because the computer is switching among different kinds of tasks: interacting with users on thousands of connections, accessing files from disk, and running application code, among others. The application server may be thrashing – running out of memory, swapping chunks of memory out to disk, and making many requests wait on a single task such as disk I/O.
Instead of upgrading your hardware, you can take an entirely different approach: adding a reverse proxy server to offload some of these tasks Using a reverse proxy server frees the application server from having to wait for users to interact with the web app and lets it concentrate on building pages for the reverse proxy server to send across the Internet.
Reverse Proxy sits between internet traffic and our on-premise servers, which act as intermediate layer often used to load balance and serve the content from cache.
 The application server, which no longer must wait for client responses, can run at speeds close to those achieved in optimized benchmarks.
Adding a reverse proxy server also adds flexibility to your web server setup. For instance, if a server of a given type is overloaded, another server of the same type can easily be added; if a server is down, it can easily be replaced.
Because of the flexibility it provides, a reverse proxy server is also a prerequisite for many other performance-boosting capabilities, such as:
•	Load balancing (see Tip #2) – A load balancer runs on a reverse proxy server to share traffic evenly across a number of application servers. With a load balancer in place, you can add application servers without changing your application at all.
•	Caching static files (see Tip #3) – Files that are requested directly, such as image files or code files, can be stored on the reverse proxy server and sent directly to the client, which serves assets more quickly and offloads the application server, allowing the application to run faster.
•	Securing your site – The reverse proxy server can be configured for high security and monitored for fast recognition and response to attacks, keeping the application servers protected.
NGINX software is specifically designed for use as a reverse proxy server, with the additional capabilities described above. NGINX uses an event-driven processing approach which is more efficient than traditional servers. NGINX Plus adds more advanced reverse proxy features, such as application health checks, specialized request routing, advanced caching, and support.
 
Solution 2. Cache Static and Dynamic Content :
Caching improves performance of your web applications by delivering content to clients faster. Caching can involve several strategies: preprocessing content for fast delivery when needed, storing content on faster devices, storing content closer to the client, or a combination.
There are two different types of caching to consider:
•	Caching of static content. Infrequently changing files, such as image files (JPEG, PNG) and code files (CSS, JavaScript), can be stored on an edge server for fast retrieval from memory or disk.
•	Caching of dynamic content. Many Web applications generate fresh HTML for each page request. By briefly caching one copy of the generated HTML for a brief period of time, you can dramatically reduce the total number of pages that have to be generated while still delivering content that’s fresh enough to meet your requirements.
If a page gets ten views per second, for instance, and you cache it for one second, 90% of requests for the page will come from the cache. If you separately cache static content, even the freshly generated versions of the page might be made up largely of cached content.
There are three main techniques for caching content generated by web applications:
•	Moving content closer to users. Keeping a copy of content closer to the user reduces its transmission time.
•	Moving content to faster machines. Content can be kept on a faster machine for faster retrieval.
•	Moving content off of overused machines. Machines sometimes operate much slower than their benchmark performance on a particular task because they are busy with other tasks. Caching on a different machine improves performance for the cached resources and also for non-cached resources, because the host machine is less overloaded.

Automating IP Whitelisting security:
What is IP whitelisting: 
IP whitelisting allows IT administrators to assign any team member a single, static outgoing IP address. This capability enables new types of cloud and on-premises configurations that are only possible with static IP addresses.
Current issue scenario: 
IT administrators are left to manually whitelist IP addresses for users, websites, and other gated resources which can take a significant amount of time.
Tool to secure this automated procedure: Perimeter 81:

Without a service like Perimeter 81 to whitelist IP addresses for you, with whitelisting, businesses can also limit access to unsecured or distracting sites that can reduce productivity and cut into profits. In fact, 50 percent of businesses take whitelisting very seriously because of these reasons.
•	Secure Remote Access
Whitelisting enables organizations to secure remote access to the network, including BYOD (Bring Your Own Device) that allow employees to utilize their own devices. With remote access security, businesses can mitigate both cloud and on-site risks that could negatively impact your company’s projects or profits.
How to Whitelist IPs with Perimeter 81
Utilizing Perimeter 81’s secure network access service, all Internet traffic is fully secured and encrypted. Using the unified management portal, IT administrators can easily block out threats, grant user access to approved resources and automatically whitelist specific IP addresses.
How it Works
Perimeter 81’s private gateway feature provides IT administrators with the power to whitelist IP addresses, thereby enabling all team members to share a single, static outgoing IP address accessible by your organization or partners. For example, remote users can always connect to the Perimeter 81 private gateway first, then have their IP address whitelisted.
With Perimeter 81, you can give each user access to the necessary resources they need from any IP address by assigning users to groups. Each user signs in via Identity Provider integration, username and password, and/or two-factor authentication and is then able to access resources according to the roles and permissions assigned to them. This keeps IT administrators from having to manually whitelist every user’s IP address.
After the whitelist is configured with users and permissions, the user list should be audited on a routine basis as employees are hired and leave companies on a regular basis. In addition, partners that access IP whitelisted resources come and go and IT administrators should have full user access visibility through IP whitelisting.
Perimeter 81 IP Whitelisting in the Cloud
Because remote users can always connect to a gateway first and then have their IP address whitelisted to a security group, cloud service platforms including AWS, Azure, Office Firewall, SalesForce, or Zendesk can all be configured to work with Perimeter 81.
Using AWS, for instance, inbound traffic from Perimeter 81 to AWS can be authorized by whitelisting the Perimeter 81 Private Network IP address to your Security Groups (AWS Virtual Firewall).
AWS Security Groups enable the control of IP traffic to your instance, including traffic that can reach instances and services both in the cloud and on-premises. To whitelist IPs, you can allow computers from only your Perimeter 81 Private Server to access your instance using SSH, or use a web server that allows all IP addresses to access your instance using HTTP or HTTPS, so that external users can browse the content on your web server only once connected to Perimeter 81.
Example: How to Whitelist IPs in AWS
Following is a walkthrough of how to use AWS Security Groups to enable the control of traffic to an AWS instance, including traffic that can reach both instances and services:

•	Step 1: Create a Private Network IP Address
First, create a Perimeter 81 Private Server and then obtain its static public IP address..
•	Step 2: Add an EC2 Security Group Rule  
Add an EC2 Security Group Rule for Inbound Traffic from Perimeter 81 to the required resources by whitelisting access to the Perimeter 81 Private Network to other instances, databases and related security groups.
o	In the navigation pane of the Amazon EC2 console, choose Security Groups.
o	For every security group you’d like to allow secured access over your Perimeter 81 Private Network, add an Inbound Rule:
	Specify the related Type (ALL TRAFFIC, SSH, HTTP/HTTPS etc..).
	Under the Source, enter the Perimeter 81 Private Network IP address including the subnet mask. For example, for IP address 129.42.24.22, enter 129.42.24.22/32 (CIDR notation).
	Click Save.
 
Add access from Perimeter 81 Private Network to your AWS Environment, Instances or databases
Whitelisting Isn’t the Full Solution
For most businesses, whitelisting IP addresses can be overwhelmingly beneficial. However, even though whitelisting can improve cybersecurity, boost productivity and benefit your bottom line, it’s important to remember that each line of security is important. Whitelisting should not replace other security measures, but instead, be used as a complementary piece of a comprehensive security solution.


