# SOHO-Network-
A small office home office network based on packet tracer
Scenario
XYZ company is a fast-growing company in Eastern Australia with more than 2 million customers globally. The company deals with selling and buying of food items, which are basically operated from the headquarters. The company is intending to open a branch near the local village Bonalbo. Thus, the company requires young IT graduates to design the network for the branch. The network is intended to operate separately from the HQ network. Being a small network, the company has the following requirements during implementation;

•	One router and one switch to be used (all CISCO products).
•	3 departments (Admin/IT, Finance/HR and Customer service/Reception).
•	Each department is required to be in different VIANS.
•	Each department is required to have a wireless network for the users.
•	Host devices in the network are required to obtain IPv4 address automatically.
•	Devices in all the departments are required to communicate with each other.
Assume the ISP gave out a base network of 192.168.1.0, you as the young network engineer who has been hired, design and implement a network considering the above requirements.

Accomplishments
1.	Created the network topology with required physical cabling.
2.	Subnetted to requirements. (used /26 so 3 subnetworks with equal number of usable IP addresses)
3.	Created and configured the Vlans.
4.	Configured DHCP IP assignment.
5.	Tested connectivity – Working well.
Reflection
•	The task tests the Router on Stick approach to Vlan configuration.
•	Typically involves using the sub-interfaces – thus a single physical interface offering multiple logical sub-interfaces for different Vlans.
•	Major issue when ensuing connectivity is to remember to change the NIC cards on the laptops for wireless connectivity.
	Switch off laptop first.
	Remove the pre-installed NIC card from NIC slot (by default not a wireless NIC)
	Select wireless NIC (In this case the WPC300N) and drag to NIC slot on laptop.
	Switch on the laptop.

