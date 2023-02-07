# Socket
 connection with people in order of chatting
在构造这个软件的最初,我的目的是想要仿照腾讯的QQ 微信,制造一个实时的,能够交流的用户与用户之间的软件.目前来看,他的功能还算可以,虽然可能有些简陋,但是整体的目的性还是比较明确的.第一次学习并且运用socket也让我觉得很新奇.

client 和 sever 是交互的对象,服务器和用户相互交互,用户使用服务器给予的一条单独的线程.而服务器则可以支持多个客户端同时连入.心跳包的机制保证了一定程度上的稳定,解决了掉线问题
我在这里没有给出具体的前端,因为我认为我对于前端的熟练度并不足,并且,我相信搭建前端可以是一件较为有仪式感的任务.

At the beginning of the construction of this software, connection with people in order of chat, my purpose was to imitate Tencent's QQ WeChat to create a real-time, user-to-user software that can communicate with each other. At present, its function is still OK, although it may be a little crude, but the overall purpose is still relatively clear. The first time I learned and used socket also made me feel very strange

Client and sever are interactive objects. The server and user interact with each other. The user uses a single thread given by the server. The server can support multiple clients to connect at the same time. The heartbeat packet mechanism ensures a certain degree of stability and solves the problem of offline. I don't give a specific front-end here, because I don't think I have enough proficiency in the front-end, and, I believe that building the front end can be a more ceremonial task
