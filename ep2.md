## Episode 2
**Networking**  
I've been doing infrastructure for over 20 years.  
One thing that has always eluded me has been IPv4 subnetting.  
I mean, I've always known what subnet mask to use and the range of IPs  
in the VLAN etc.  But since I've mostly been a Server and Storage guy  
it was never up to me to decide how many IPs a subnet needed (except for a cert test).  
So as I've moved more to the cloud, it's become more needful for me to  
understand CIDR notation and this site [Networks, Subnets, and CIDR](https://erikberg.com/notes/networks.html)  
has really helped.  For example, if you want to know how many /24 are in a /22  
you could just google that and get the answer, but if you want to know the "why",  
__2<sup>32-22</sup> divided by 2<sup>32-24</sup>__ = 2^(32-22)/2^(32-24) = 4 
