Background

Denial of service (DoS) is a method of attack against a computer or server on the network the internet by way of spending resources (resource) is a computer networking equipment so that a computer network service be disrupted. This attack aims to prevent users from getting services from the system. DoS attacks can occur in many forms. IE:

Buffer Overflow attacks, sending data that exceeds the capacity of the system, for example, the ICMP packet size is very large.
SYN, sending data the TCP SYN with a false address.
Teardrop attack, sending IP packets with a confusing offset value.
Smurf attack, sending a large ICMP packet volume with the address of another host.
Internet Control Message Protocol (ICMP) Dos Flooding



Discussion and content



Denial of Service attacks are classic "one on one", so it needs a strong host (be it from processing power or system operations) in order to flood a target host traffic thus preventing a valid client to access network services on the server being the target of the attack. DDoS attacks use a more sophisticated technique than with Denial of Service attacks are classical, i.e. by increasing the attack several times by using multiple computers at once, so it can result in a server or the entire network segment can be "completely useless" for the client.

DDoS attacks first emerged in 1999, three years after a Denial of Service attack classic appears, by using SYN DOS Flooding, resulting in multiple web servers on the Internet experienced a "downtime".

To perform a DDoS attack is thus simple, i.e. as follows:

Run the tool (usually in the form of the program (software) to small) which will automatically scan the network to find the host vulnerable (vulnerable) connected to the Internet. After the vulnerable host is found, the tool can install one type of Trojan Horse known as DDoS Trojan, which will result in the host into a zombie which can be controlled remotely by a master computer that is used by the attacker to launch attacks. Some tool (software) that is used to perform the attack this likes the TFN, TFN2K is, Trinoo, Stacheldraht, and which can be downloaded for free on the Internet.
When the attacker felt the number of hosts that have been getting enough (as a zombie) to assault, the attacker will use the master computer to signal attacks against the target network or host target. \

Almost any computer platform can be hijacked as a zombie to do attacks like this. Popular systems, such as Solaris, Linux, Microsoft Windows and several UNIX variants can be zombies, if indeed such systems or applications that run on it have a weakness exploited by attackers.





well here the authors give a little script usage of DDOS



Solutions and suggestions

The lesson of this case study is, that for a system to ensure security, it is necessary the preparation of all the components that are involved in it. In this case, the organizers just prepare the application to be used only and no other preparations of the environment that are associated with the application. In addition, for important applications, then we recommend that you created the service duplication and put in some locations. This way, if one location is experiencing a service interruption, can still run from some other location.
