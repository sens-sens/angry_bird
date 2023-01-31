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
The main component of the drone is the flight controller, which is connected to the Raspberry Pi using a serial connection. A python script is connected with the Firebase backend service. The algorithm in the script is capable of finding the destination location from the Firebase data and controlling the flying aspects of the drone.An Android app is made using Google’s new Flutter technology, which also has the same Firebase backend service. The delivery agent can scan the QR code in the package and instruct the Python script appropriately within the app.

---

## ![Image Link](https://github.com/saravanan2k03/angry_bird/blob/main/Image.jpg)

---
## ![Image Link](https://github.com/saravanan2k03/angry_bird/blob/main/Image1.jpg)

---
## ![Image Link](https://github.com/saravanan2k03/angry_bird/blob/main/Image2.jpg)
---
## ![Image Link](https://github.com/saravanan2k03/angry_bird/blob/main/Image3.jpg)
---
## ![Image Link](https://github.com/saravanan2k03/angry_bird/blob/main/Image4.jpg)
---
## [Youtube Video Link](https://www.youtube.com/watch?v=kqYaZeBHdSA)


---

## **Results:**

Our solution can enable delivery agencies to use drones efficiently for package delivery without the need for learning to fly a drone. Also, each employee can assign a specific drone for a particular package within the Android app, so the drone is not controlled by any computer or computer-related software. It is also eco-friendly and uses the shortest path from the source to the destination.
