# ***Angry Bird***
## _Autonomous Drone Delivery System_

___

###  _In current days, e-commerce has become one of the emerging industries that require a lot of transportation. The packages received by the end user are delivered by the delivery boy belonging to the locality of the customer. This requires manpower as well as vehicles, which may or may not be eco-friendly._

---




# **Proposed Solution:**


* Most economically developed countries adopt drone technology for end-user delivery. These drones are commercial and not open-source.

* Existing projects based on custom drones use either a telemetry hardware device or some proprietary software that can only be controlled using a PC.

* To overcome this problem, we have made a fully customizable and autonomous drone, which can be controlled with the help of an Android app.

* There is no need for manual instruction as the drone can detect the end delivery location of the package using a QR code attached to the package, or else delivery agencies can dispatch any packages using the Android app we made
---

# **Methodology:**
### The main component of the drone is the flight controller, which is connected to the Raspberry Pi using a serial connection. A python script is connected with the Firebase backend service. The algorithm in the script is capable of finding the destination location from the Firebase data and controlling the flying aspects of the drone.An Android app is made using Google’s new Flutter technology, which also has the same Firebase backend service. The delivery agent can scan the QR code in the package and instruct the Python script appropriately within the app.

---


![Image](https://user-images.githubusercontent.com/112747138/215802611-d3aa7dca-0d8b-499c-95fb-ecaca71d4b86.jpg)

---

![Image1](https://user-images.githubusercontent.com/112747138/215802756-5600083b-c887-43b3-a450-754a3fbc8160.jpg)

---
![Image2](https://user-images.githubusercontent.com/112747138/215802846-38f2b82e-1c5c-4f90-b4d4-b3ce8e0e92a5.jpg)

---
![Image3](https://user-images.githubusercontent.com/112747138/215802919-d0b447ed-2aba-4726-baad-19c84dacd6b8.jpg)

---
![Image4](https://user-images.githubusercontent.com/112747138/215802994-5877ae7d-774d-4ecd-a1bd-65182180f4f2.jpg)

---
## [Youtube Video Link](https://www.youtube.com/watch?v=kqYaZeBHdSA)


---

## **Results:**

### Our solution can enable delivery agencies to use drones efficiently for package delivery without the need for learning to fly a drone. Also, each employee can assign a specific drone for a particular package within the Android app, so the drone is not controlled by any computer or computer-related software. It is also eco-friendly and uses the shortest path from the source to the destination.
