# **Angry Bird**
## Autonomous Drone Delivery System

In current days, e-commerce has become one of the emerging industries that require a lot of transportation. The packages received by the end user are delivered by the delivery boy belonging to the locality of the customer. This requires manpower as well as vehicles, which may or may not be eco-friendly.


# **Proposed Solution:**


* Most economically developed countries adopt drone technology for end-user delivery. These drones are commercial and not open-source.

* Existing projects based on custom drones use either a telemetry hardware device or some proprietary software that can only be controlled using a PC.

* To overcome this problem, we have made a fully customizable and autonomous drone, which can be controlled with the help of an Android app.

* There is no need for manual instruction as the drone can detect the end delivery location of the package using a QR code attached to the package, or else delivery agencies can dispatch any packages using the Android app we made


# **Methodology:**

The main component of the drone is the flight controller, which is connected to the Raspberry Pi using a serial connection. A python script is connected with the Firebase backend service. The algorithm in the script is capable of finding the destination location from the Firebase data and controlling the flying aspects of the drone.An Android app is made using Google’s new Flutter technology, which also has the same Firebase backend service. The delivery agent can scan the QR code in the package and instruct the Python script appropriately within the app.

# **Screenshots:**

<img src="https://user-images.githubusercontent.com/90544639/215793574-db821f8d-ac63-4815-9fc7-dc920fd60d74.jpg" width=40% height=40%>

<img src="https://user-images.githubusercontent.com/90544639/215793706-fc641ba8-6a14-4052-993f-c80b31485407.jpg" width=40% height=40%>

<img src="https://user-images.githubusercontent.com/90544639/215793739-7019c1ca-2775-4a5b-991d-823a62412968.jpg" width=40% height=40%>

<img src="https://user-images.githubusercontent.com/90544639/215793767-3e3319f4-86c6-422b-b8db-2d0087b1eacc.jpg" width=40% height=40%>

<img src="https://user-images.githubusercontent.com/90544639/215793874-934f6005-9fc0-4c10-a532-b10c7de597d5.jpg" width=40% height=40%>


## **Youtube Video:**
[click here](https://www.youtube.com/watch?v=kqYaZeBHdSA) to view this video



## **Results:**

Our solution can enable delivery agencies to use drones efficiently for package delivery without the need for learning to fly a drone. Also, each employee can assign a specific drone for a particular package within the Android app, so the drone is not controlled by any computer or computer-related software. It is also eco-friendly and uses the shortest path from the source to the destination.
