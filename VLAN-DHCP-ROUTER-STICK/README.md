# Enterprise VLAN Segmentation Lab

## Objective

Design and implement a segmented enterprise network using:

- VLANs
- VLSM
- DHCP
- Router-on-a-Stick
- Inter-VLAN Routing

## Network Design

| Department | VLAN | Network |
|------------|------|----------|
| Sales | 10 | 192.168.10.0/25 |
| IT | 20 | 192.168.10.128/26 |
| HR | 30 | 192.168.10.192/27 |
| Management | 40 | 192.168.10.224/30 |

## Skills Demonstrated

- VLAN Configuration
- Trunking
- Router-on-a-Stick
- DHCP Configuration
- Routing Verification
- Troubleshooting

## Verification Commands

show vlan brief

show interfaces trunk

show ip interface brief

show ip route

show ip dhcp binding
