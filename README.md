# Problem Statement
# Plugging Devices into Power Outlets

You are developing an application that helps users manage and control various electronic devices by plugging them into power outlets. Each device has different plug types, voltage, and amperage requirements. To ensure compatibility and safety, you need to create adapters for different devices to allow them to be plugged into standard power outlets.
•Adaptee Objects:
o	Laptop - Represents a laptop device that needs to be plugged into a power source. It has the charge() method.
o	Refrigerator - Represents a refrigerator device that requires a power source. It has the startCooling() method.
o	SmartphoneCharger - Represents a smartphone charger that needs to be plugged in for charging. It has the chargePhone() method.
        
•Target Object:
o	PowerOutlet - Represents a standard power outlet with a common interface for plugging in devices. It defines the plugIn() method as the target method.
        
•Adapter Objects:
o	LaptopAdapter - An adapter for plugging a laptop into a standard power outlet. It adapts the Laptop to the PowerOutlet interface, translating plugIn() to charge().
o	RefrigeratorAdapter - An adapter for plugging a refrigerator into a standard power outlet. It adapts the Refrigerator to the PowerOutlet interface, translating plugIn() to startCooling().
o	SmartphoneAdapter - An adapter for plugging a smartphone charger into a standard power outlet. It adapts the SmartphoneCharger to the PowerOutlet interface, translating plugIn() to chargePhone().

# UML Class Diagram
![Blank diagram](https://github.com/lloydestrada/adapterPattern/assets/142376663/7b092e0b-2bdc-43a9-9f6a-2e592c2b08c0)
