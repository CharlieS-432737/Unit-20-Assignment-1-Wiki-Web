# <u>**Fault finding**</u>

Nearly all the machines that can be monitored will be monitored. Logs of each machine will be stored on the server and will have to ability to be viewed at any time. The machines will be monitored using an application called netdata. The logged data can be accessed through a web interface on the local network or can be linked to the cloud to allow them to be viewed anywhere. Netdata can keep track of what is happening on each machine on the network and can also send alerts and notifications via email, text or other forms. Netdata has set limits on certain logs, allowing alerts to be sent when a limit has been reached.

Other devices like switches, routers and other hardware that netdata cant be installed on, will be monitored by the ping tool that can be found on many operating systems. A script will run once a day that will ping important systems to confirm they can be reached.

If netdata or the ping script finds a fault, the appropriate IT technician will be alerted. Once alerted the IT technician will be required to log the fault into the fault database.
