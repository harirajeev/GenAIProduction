Load Balancer is a critical topic that is essential to know.

A Loadbalancer is a simple technology to distribute the incoming load so that you do not stress one server and improves overall application scalability.

Loadbalancer helps an application architecture improve its performance, scalability, and availability. Apart from load distribution, load balancers offer many other features like service discovery, health checking, logging, security, etc.

Load balancers are available as hardware Or software, and now, with the advent of the cloud, cloud load balancers, also known as load balancers as a service.

Various cloud providers like AWS, GCP, Azure etc offer load balancers as a service.

Loadbalancer employs various algorithms to distribute the load. One needs to adopt the right ones that suit their requirements and needs.

𝗦𝗼𝗺𝗲 𝗼𝗳 𝘁𝗵𝗲 𝘄𝗲𝗹𝗹-𝗸𝗻𝗼𝘄𝗻 𝗹𝗼𝗮𝗱 𝗯𝗮𝗹𝗮𝗻𝗰𝗲𝗿 𝗮𝗹𝗴𝗼𝗿𝗶𝘁𝗵𝗺𝘀 𝗮𝗿𝗲 :

𝗥𝗼𝘂𝗻𝗱𝗥𝗼𝗯𝗶𝗻: Load is sequentially distributed to each server as it arrives from the end clients

𝗪𝗲𝗶𝗴𝗵𝘁𝗲𝗱: Each server is assigned a weight, and requests are sent to servers based on the weights. The higher the weight, the higher the number of requests.

𝗟𝗲𝗮𝘀𝘁 𝗖𝗼𝗻𝗻𝗲𝗰𝘁𝗶𝗼𝗻𝘀: Depending on the number of connections each server has, requests are forwarded to servers with fewer connections. It follows the order of Less to More.

𝗥𝗲𝘀𝗽𝗼𝗻𝘀𝗲 𝘁𝗶𝗺𝗲: More requests are forwarded to the servers with the best response times. It looks into active connections and server response time when it has to decide which server it has to send the request to.

𝗜𝗣 𝗛𝗮𝘀𝗵: When a request is received from a client, hashing is performed on the client IP, which is converted to a number; the number is mapped to the server, and based on the server mapping, requests are forwarded

𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲 𝗕𝗮𝘀𝗲𝗱: Depending on the availability of free resources ( CPU, Memory), requests are forwarded to servers with more free resources.

![image](https://github.com/user-attachments/assets/956da5cf-2e84-4935-9381-0f697c398dfd)
