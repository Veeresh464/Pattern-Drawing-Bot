# 6.1 3D MODELING
### Drawing unit(1805 and 1833)
![Screenshot_20230120_053725](https://user-images.githubusercontent.com/120156473/213676024-47009c69-80c6-4cd4-9f75-5ac42ddf4eec.png)
### Indication unit(1824)

![Screenshot (12)](https://user-images.githubusercontent.com/120176356/215838720-b12d385d-62ed-4685-8dcb-481798c38096.png)



### Display unit (1840)
![nippu assembly](https://user-images.githubusercontent.com/120027181/215669584-beb8eab2-2b41-40bb-814c-61094485eed6.png)




# 6.2 CIRCUIT DIAGRAM
### Drawing unit(1833 and 1805)
<img width="780" alt="circuit1" src="https://user-images.githubusercontent.com/120027181/223006165-ef2e0a68-2c98-4fef-87b6-c1e1df91e9e5.png">
### Indication unit(1824)
![Screenshot (7)](https://user-images.githubusercontent.com/120176356/215689968-fbaf10f3-69f7-41c8-990b-088a65529be0.png)


### Display unit(1840)
![Screenshot (15) nippu](https://user-images.githubusercontent.com/120027181/215666319-2bdf75dd-9b0a-4f98-9ed0-d16e50256a89.png)



# 6.3 FLOW CHART
### Drawing unit(1833 and 1805)
![Screenshot_20230120_055619](https://user-images.githubusercontent.com/120156473/213679094-e1277573-e8ae-4340-825f-98b462f4bb3e.png)
### Indication unit(1824)
![Screenshot (9)](https://user-images.githubusercontent.com/120176356/215689384-e9681ca1-e255-447e-9a89-166cb166ffec.png)

### Display unit (1840)
![nippu flowchart](https://user-images.githubusercontent.com/120027181/215666695-b0fd656d-42df-49e0-87d7-939d7940ff28.jpeg)


# 6.4 BILLS OF MATERIALS (BOM)
### Drawing unit(1833 and 1805)
![Screenshot_20230120_055336](https://user-images.githubusercontent.com/120156473/213678618-8d777746-b0ff-44ba-a57a-a6e9e07dcce7.png)
![Screenshot_20230124_082626](https://user-images.githubusercontent.com/120156473/214307227-398d850a-263c-428c-9d4e-9d83ddab0d79.png)

### Indication unit(1824)
![Screenshot (8)](https://user-images.githubusercontent.com/120176356/215689688-3ef1ad2b-dc92-424a-8fb7-f610eb71f2e3.png)

### Display unit (1840)
![Screenshot (4)](https://user-images.githubusercontent.com/120151838/215671332-fe946197-f3b1-496f-8833-ef207f8adc05.png)
# 6.5 MECHANISM AND RESOURCE SPECIFICATIONS
![Screenshot 2023-03-18 111545](https://user-images.githubusercontent.com/120156473/226114798-4d57b0c3-b65c-4af1-9797-f88c1213330c.png)
# MOTOR SIZING 
Torque = force * perpendicular distance.

force = mass * acceleration due to gravity.

Mass = volume * density of the material.

In our project we are using a DC Motor.

Mass of the material on DC = volume of the material on DC * density of the material used.

Mass of the material on DC= (23.079 x 10^-6) * 1200 kg/m3

Mass of the material on DC= 27694.8 x 10^-6 = 0.0276948kg

Torque in (kg-cm) = 0.0276948 * 7

Torque in (kg-cm) = 0.2 kg-cm.

Therefore multiplying by safety factor 0.2 * 1.5

Torque in (kg-cm) = 0.3 kg-cm.

<img width="382" alt="dc motor specifiactions" src="https://user-images.githubusercontent.com/120027181/215746571-f11e4b6a-5b15-4a92-b414-d62a8a376662.png">

Hence from the source table ,**RPM that is selected by calculation is 1000rpm.**

**But we are selecting 30RPM DC Motor because of the requirement of the low rotation per minute speed.**


<img width="533" alt="servo spec" src="https://user-images.githubusercontent.com/120027181/215754785-d7ea6fdc-c363-4cda-b742-c53b06774bdf.png">

As the stall torque of the machinism is 0.4 kg-cm and stall current 0f 650 mA.

from the above source table = **We are selecting the servo motor of Tower Pro SG-90.**


force = 0.0276948kg * 9.8

force = 0.2714 N

Torque = 0.2714 * 7 * 10^-2 * 1.5 * 0.9 

Torque = 0.0256 Nm .

Power = (2*pi*N*T)/60.

Power=0.08 Watt.

# BATTERY SIZING

|MOTORS USED|QUANTITY|LOAD CURRENT|
|-----------|---------|------------|
|DC GEARED MOTOR| 01 | 300mA |
|DC GEARED MOTOR| 01 | 300mA |
|SERVO MOTOR| 01 | 650mA |

Total current  = current for dc motor + current for stepper motor + current for servo motor

               = 300mA + 300mA + 650mA

 TOTAL CURRENT = 1250mA

After multiplying saftey factor = Total current*1.2

Therefore Total current = 1500mA

Total current= 1.50 A.

**Therefore we will be using  dc adaptor of  12 V 2 A.**

# INTEGRATION

### 6.51 3D MODEL
![Screenshot_20230124_080317](https://user-images.githubusercontent.com/120156473/214307924-cb6e3e7a-9080-4518-a16e-713a401e1d2e.png)
### 6.52 CIRCUIT DIAGRAM
<img width="780" alt="circuit1" src="https://user-images.githubusercontent.com/120027181/223006165-ef2e0a68-2c98-4fef-87b6-c1e1df91e9e5.png">



### 6.53 FLOW CHART
![Screenshot_20230124_082112](https://user-images.githubusercontent.com/120156473/214307839-972b58ba-632f-4620-8994-2a29a79728ac.png)
### 6.54 BILL OF MATERIAL
![Screenshot_20230124_081211](https://user-images.githubusercontent.com/120156473/214308066-0ae83daa-376a-4fd6-b606-81596e203bda.png)
