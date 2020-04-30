## Team Name - Domain Name

The participants are required to use this repository as a template and create a private Github repository under their own username (Single repository per team). The following created sections in this README.md need to be duly filled, highlighting the denoted points for the solution/implementation. Please feel free to create further sub-sections in this markdown, the idea is to understand the gist of the components in a singular document.

### Project Overview
----------------------------------

Due to COVID-19, a huge number of people in our country are on the streets now with no food and shelter.



### Solution Description
So, to solve this,
A very efficient distribution system is created- to ensure smooth flow of cooked food using the application of IoT enabled machines, to the home less, also parallelly giving a livelihood to the people who are helpless in the lock down, such as app based taxi drivers, and private tempo/truck drivers/companies , caterers and Vending machine sellers/owners- providing a boost to the economy.
How is it implemented?
- Part A- Sheltering the homeless
The government must identify the homeless at night,- the same way the number estimates of homeless were made , and shift them to the Quarantine center that is to be set up in each Ward of the hotspot metro city (QCW) dedicated to the homeless. App Taxi drivers can help ferry the homeless to the QCW. They are paid by the government.
Each QCW will take biometrics of each person shifted there. A database will be set up, and data will be sent to the Central Processing Unit (CPU) (to be set up at the heart) of the city. 
(details explained in the upcoming slides)
This covers the shelter part of the solution.

Part B-
Food supply distribution:
We take the case of Southern Metro cities- BLR,Hyd, Chennai. They have a homeless population of approx. 5000 people each. Each city has 150 wards, so on average 33 people per ward. 
In our solution we keep a 400% buffer to the number of homeless people, so that the system does not crumble, in-case the numbers have changed due to CoVID 19, i.e. to accommodate 20000 homeless per city, with minimum food wastage.

Also, another aim, is to use minimum contact between people, but also keep more people employed.

A CPU is set up in the centre of the city, which acts like a mass producing factory of cooked food, and has the responsibility of dividing the food into individual meals (packets). Food shall be cooked by caterers who have been given contracts by the government.
These meals are transported to the QCW’s via private trucks, cabs, funded by the govt, and loaded onto the vending machines that have been installed in the QCW’s. Each truck covers 5 wards, and a total of 30 trucks will be required, for 3 trips, i.e Breakfast , Lunch, Dinner. The route taken by the trucks can be sorted by tree traversal algorithms- to maintain maximum efficiency- each QCW is a node.
Each vending machine can store ((4rows *6colums *5depth)=120 meals. The latest vending machines (like the ones used by Big Basket Instant) are connected to the internet (IOT) and can store bulky goods in them, and can provide an accurate count of meals stored/ left. The vending machine updates the CPU on how many meals are left in it, so that they can send the appropriate number of meals in each trip. These machines are refilled 3 times a day.


#### Architecture Diagram

*see PPT, not able to paste it here*

#### Technical Description

How the machine works:
The machines are totally user friendly. The person who needs the meal, will give his biometric, and the machine unlocks, and he can pick the food. The caretakers, at the QCW’s can assist, because no training is required to operate these machines.
Minimum man power is required, and thus the delivery of food to the care seeker is contact less. As soon as a single meal is taken out of the machine, the CPU gets the information via the internet, to prepare enough meals, to reload the machine (Minimum wastage)

A total of 1 vending machine is required per QCW, therefore 150 machines in a big metro city.



### Team Members
----------------------------------
Dhruba Das - 1928093@kiit.ac.in
Devarghya Ray- 1928092@kiit.ac.in
Sraman Mukherjee- pritidhruba123@gmail.com

