# **Angry Bird**

## Autonomous Drone Delivery System

In current days, e-commerce has become one of the emerging industries that require a lot of transportation. The packages received by the end user are delivered by the delivery boy belonging to the locality of the customer. This requires manpower as well as vehicles, which may or may not be eco-friendly


## **Proposed Solution:**


* Most economically developed countries adopt drone technology for end-user delivery. These drones are commercial and not open-source.

* Existing projects based on custom drones use either a telemetry hardware device or some proprietary software that can only be controlled using a PC.

* To overcome this problem, we have made a fully customizable and autonomous drone, which can be controlled with the help of an Android app.

* There is no need for manual instruction as the drone can detect the end delivery location of the package using a QR code attached to the package, or else delivery agencies can dispatch any packages using the Android app we made


## **Methodology:**
The main component of the drone is the flight controller, which is connected to the Raspberry Pi using a serial connection. A python script is connected with the Firebase backend service. The algorithm in the script is capable of finding the destination location from the Firebase data and controlling the flying aspects of the drone.An Android app is made using Google’s new Flutter technology, which also has the same Firebase backend service. The delivery agent can scan the QR code in the package and instruct the Python script appropriately within the app.


## **Screenshots:**
<img src="https://user-images.githubusercontent.com/90544639/215802466-59f37835-5e69-48e2-8ae9-c49c704b072c.jpg" height="40%" width = "40%">
<img src="https://user-images.githubusercontent.com/90544639/215802476-2c8a6e17-b06b-416a-b407-bb16e0ab4005.jpg" height="40%" width = "40%">
<img src="https://user-images.githubusercontent.com/90544639/215802491-ac1cf72b-317a-4b38-a0a3-22a8b4714636.jpg" height="40%" width = "40%">
<img src="https://user-images.githubusercontent.com/90544639/215802507-1f4f67a7-4c61-4225-9ee4-6f0ffed674ec.jpg" height="40%" width = "40%">
<img src="https://user-images.githubusercontent.com/90544639/215802525-f769a078-e896-4807-9f6f-d2484ea396e7.jpg" height="40%" width = "40%">





## **Youtube:**

[click here](https://youtube.com/watch?v=kqYaZeBHdSA&feature=share) to view the implementation video.


## **Results:**

Our solution can enable delivery agencies to use drones efficiently for package delivery without the need for learning to fly a drone. Also, each employee can assign a specific drone for a particular package within the Android app, so the drone is not controlled by any computer or computer-related software. It is also eco-friendly and uses the shortest path from the source to the destination.
