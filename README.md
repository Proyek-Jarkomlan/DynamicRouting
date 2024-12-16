# 📄 **Dynamic Routing**

## **Configuration**

![Dynamic Routing Configuration](https://github.com/Proyek-Jarkomlan/DynamicRouting/blob/main/assets/Dynamic%20Routing.jpg?raw=true)

## **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/Proyek-Jarkomlan/DynamicRouting.git
2. Navigate directory to the project:
   ```bash
   cd DynamicRouting
3. Run the project with this command:
   ```bash
   sudo python3 dynamic-routing.py -c frr-config
3. Run the project with this command:
   ```bash
   sudo python3 static-routing-2rtr.py -c frr-config
4. Run this command to test the project:
   ```bash
   h1 traceroute -I h2
5. If a down link is performed on r1 to r2, traceroute should still be able to run:
   ```bash
   link r1 r2 down
   h1 traceroute -I h2
   
