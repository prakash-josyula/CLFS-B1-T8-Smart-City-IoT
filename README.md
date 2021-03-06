# CLFS-B1-T8-Smart-City-IoT

Smart Cities bring Internet of Things to life with seamless connectivity that improves overall quality of life, promotes econimic growth, increases sustainability and managing of resources. It is more than just a vision. A "Smart City" is an urban area that incorporates information and communication technologies into its systems. Sensors gather data to inform authorities and residents, reducing waste and making resource consumption more efficeint.

This is a capstone project done as part of Careerlabs Finishing School.

The project focuses on 4 main areas that must be in a city:
1. Traffic Control System
2. Automatic Parking System
3. Smart Home
4. Enviromental Monitoring

## Automatic Parking System
This part is about automating the tasks like billing, displaying number of parking lots available and capturing the number plates of the cars entering the area.

Components used in this part of the project are:
1. IR Sesnors x 4
2. Raspberry Pi
3. RFID Reader and Tag
4. LCD Display

### Phase 1:
The Objective of Phase 1 is to create a fare calculation system. 2 IR Sensors are used to detect two parking lots. When a vehicle enters a lot the IR Sesnor value becomes '1' and the entry time of the vehicle will be logged. When a vehicle leaves the lot the IR Sensor value becomes '0' and the exit time of the is calculated. Based on the number of hours parked the parking fee for that vehicle parked in that lot will be calculated.
* For the Fare Calculation Python Script [click here](https://github.com/prakash-josyula/CLFS-B1-T8-Smart-City-IoT/blob/e16a3966d3bf54dadce12e002332a589959934dc/Fare_Calculation.py)
