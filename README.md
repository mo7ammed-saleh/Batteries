# Batteries
**This Repository will explain my 3rd task in Electronics and Electrical power department at [SMART METHODS](https://github.com/smart-methods) summer training.**

## Task Requirements: 
  - Battery types and selecting the best one for suppling the robot, considering the longest working time and costs criteria.
  - Design battery charging circuit.

## Detailed Steps:

1. **Battery types:**

   - [*Lead Acid Battery:*](https://etqan.sa/product/battery-12v-7ah-lead-acid-rechargeable-battery/)
  
     <p align='left'><img width="30%" src="https://github.com/mo7ammed-saleh/Batteries/blob/main/Lead%20Battery%20Acid.jpg"/>
    </p>
   
      | Specification | Calculation|
      | --- | --- |
      | Volt , Capacity |  12v , 7Ah |
      | power hour | 12v*7Ah = 84 Wh|
      | price (SAR) | 98 SAR |
      | power hour/price | 60Wh/50SAR = 0.85 Wh/SAR |
      | Size | large |
      | weight | High weight |

   -  *Lithium-ion Battery:*
  
    <p align='left'><img width="30%" src="https://github.com/mo7ammed-saleh/Batteries/blob/main/Lithium%20battery.jpg"/>
    </p>
   
      | Specification | Calculation|
      | --- | --- |
      | Volt , Capacity |  3.7v , 2400mAh |
      | power hour | 3.7v*2400mAh = 8.88 Wh|
      | price (SAR) | 10 SAR |
      | power hour/price | 8.88Wh/10SAR = 0.88 Wh/SAR |
      | Size | small |
      | weight | light weight |
      
   -  *Lithium-polymer Battery:*

    <p align='left'><img width="30%" src="https://github.com/mo7ammed-saleh/Batteries/blob/main/Lithium%20polymer.png"/>
    </p>
   
      | Specification | Calculation|
      | --- | --- |
      | Volt , Capacity |  3.7v , 2000mAh |
      | power hour | 3.7v*2000mAh = 7.4 Wh|
      | price (SAR) | 35 SAR |
      | power hour/price | 8.8Wh/10SAR = 0.21 Wh/SAR |
      | Size | small |
      | weight | light weight |

- [x] Based on the above details and battery specification, the best battery to choose is the Lithium-ion battery because its provide more power and long time compare it with its price.

2. **Now, lets select how many Lithium-ion batteries we need for our application which mean what is the capacity needed for the battery:**
  - Assume the motors is 12v, 6 watt DC motor, fistly finding the current in Amp that consumed by the motor to run: 
    > I=Power/Volt= 6/12= 0.5A (Theoritical).
   
  - Secondlly,finding the power hour
    > To run 6 watt in 1 hour, 6watt*1hour= 6 Wh, and for saftey reasons multiply by 1.2 as a safety factor. So, Wh=7.2Wh.
   
  - Finally, to get the capacity of the battery convert Wh to Ah 
    > P=I*V > 7.2Wh=12v*Ah > Ah=0.6Ah. So, to run a 6watt-12Volt motor for 1 hour a 0.6 Ah lithium ion battery is needed.
