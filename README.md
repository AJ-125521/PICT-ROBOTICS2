ROS2 stand for Robot Operating System ,it is s a open source framework design to help developer/user in development of complex robotic system. 
1)It is not a true operating system as mentioned in its name it act as a middleware where between the operating system the robot application code and function code. 
2)It is a collection of software tools libraries messages system that help us to break the robot code into manageable pieces called as node.
3)Additionally it contains wide array of debugging and stimulation tools that help designed help designed and test your robot.

Node : It is a fundamental building software building block in ros is a node. Is a process that perform some action like reading from a sensor or control motor. The structure of nodes in ROS 2 encourages object oriented programming principal.
When a code is run in ros each node runs it's own process and runtime environment node and communication with each other called as topics.
 
Topics :These are named communication channel for publishing and subscribing model.Node can subscribe to one or more topics  uand whenever a message is published to that topic all subscribing node will receive it .For example you might have a sensor node that regularly published data and driver note that uses information to avoid obstacle.

Services :Synchronous communication using request and responses where a client sends a request and the server is expected to reply with response.Request and responce are specific types with one or more field of data such a strings ,floating point, integers and extra.
