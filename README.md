# Java-fluid-level-monitoring-Web-app
![image](https://user-images.githubusercontent.com/72305802/222513490-aa1f47f0-c2c4-44fc-a792-0555e424895c.png)

Java servlet web app for fluid level monitoring.
App assumes the tank with fluid has two input valves and one output valve. Each valve has a flow value in [l/min], that can be specified.
Based on stream flow values app recalculates fluid height in tank in [m]. Assuming the tank is a cylindrical one, with radius specified.
App stores historic fluid level records in database using JDBC.
