# The VISSible Project
## 1. Problem Statement
According to WHO, the world has 1.1 billion visually impaired or blind people, with Africa representing 15.3% of this figure. Low-income countries(for example those in Sub-Saharan Africa and South Asia) are more likely to be affected, having over 8 times as many blind people as in high-income nations.

### 1.1 The access-problem
The blind in low-income countries often can not afford Braille devices and are more likely to access them through learning institutions where the ratio of available devices is disproportionate to the number of students.

### 1.2 The technology problem
It is a common sentiment shared among the visually impaired that the technological industry has neglected them as advances in technologies that target them are significantly less and do not match those done that target the sighted. The high-end refreshable braille displays cost north of $15,000 but provide up to 80 characters, while displays for the sighted can go as high as 8k resolution.
  
### 1.3 The income/price problem
An average sighted individual will spend $50 for a child's tab, $100 on a phone, and $500 for a computer. Braille displays will cost an average of $3,500 - $15,000, making the average price of a braille cell to be $87. These costs negatively impact their accessibility to the blind in low-income countries. Some resort to audio input which is cheaper, but can't fully substitute braille.


## 2. Our Solution
We were interested in how we can optimise the experience of braille users through haptic feedback. This motivated the name of our project, because we are doing sensory substitution of vision with touch, hence the name: VIsual Sensory Substitution.

### 2.1 The “What”
We have developed a wearable device that is worn on the arm which can be loosely split into two parts.
  
- The braille cell which has six dots, that is worn on the wrist.
- The microcontroller and its accompanying circuitry that drives the 6 braille cell.
  
### 2.2 The “How”
Characters are sent from the client devices (phones, laptops), using the MQTT protocol to the cloud, then finally to the braille device.
  
The microcontroller on the braille device converts the characters to an encoded version more suitable for the braille cell
  
We recognize that the braille cell is significantly larger than an average one, but this is an acceptable compromise considering this is a wearable device, cheap, and portable.


## 3. Impact
When taken to market, we believe the project will be of benefit to not only the blind but also to the community and skilled-workers required to produce these devices at scale.When taken to market. The project won't only be of benefit to the blind.
  
We are open-sourcing this project as we believe it will take a concerted effort to further bring the advances that have been made in digital technologies to the blind.
  
As the size and scope of the problem and technological advances happen, collaboration-models are imperative to drive innovation and impact the community at scale.
  
We want to see this project having the impact we intend it to have; to improve the quality of life of the blind, especially those in low-income countries.

## 4. Built With
- ESP 8266
- Mosquitto MQTT Broker
- IBM Cloud Virtual Server
