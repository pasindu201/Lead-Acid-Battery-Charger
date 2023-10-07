# Multistage Lead-Acid-Battery-Charger
## introduction

Lead acid batteries, among the earliest rechargeable battery technologies, derive their strength from the incorporation of elements such as antimony, calcium, tin, selenium, and the fundamental constituents of lead and acid. These batteries predominantly fall into two categories: starter batteries and recycle batteries. Charging these lead-acid batteries necessitates the use of diverse methodologies, including constant current chargers (CC), constant voltage chargers (CV), and the advanced multistage chargers.

Our project undertakes the development of a sophisticated multistage charger, engineered to seamlessly transition into constant voltage mode upon reaching a predefined battery voltage threshold. This innovative charger amalgamates the attributes of both CC and CV charging techniques to optimize battery longevity and performance.

Furthermore, our charger harnesses the precision of Pulse Width Modulation (PWM) to govern the charging process. It expertly converts a 230V power source into a stable 15V DC output, chosen deliberately to expedite the charging reaction without compromising safety. This synergy of elements and techniques culminates in a 12V lead acid battery charger, purpose-built to deliver a maximum current of 1A, all the while adhering to the CC-CV charging approach rooted in the PWM technique.

## Methodology
### Constant Current Stage
In the initial phase of charging the charger applies a fixed voltage to the battery terminals. However, the current delivered to the battery is controlled using PWM. The charger's control circuit monitors the battery's state of charge and adjusts the duty cycle of the PWM signal to maintain a constant current level. For example, if a charger is designed to deliver 1A of current to the battery, the PWM duty cycle will be adjusted to keep the current at this specified level.

### Constant Voltage Stage:





