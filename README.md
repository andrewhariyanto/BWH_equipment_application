# BWH_equipment_application
Eleven-person team working to apply Agile Scrum development methodologies and software design patterns in Java to create a medical equipment tracking and workflow application that included a hospital dashboard, floor map editor, and multiple integrated service request modules for Brigham &amp; Women’s Hospital. The software system that the team created served to inform hospital representatives about potential features, user interfaces, or design approaches that they might consider implementing.

To use:
1. Extract files, but keep all contents in the same folder
2. Double click on iteration 4 jar file. If this does not work, open terminal and set current working directory to the directory containing the files. Then type "java -jar Iteration4.jar" to run application.
3. The default username and password is "admin" for both.

Features:
1. Interactable map of hospital
   a). Move around the location pins to change locations of each room
   b). Zoom and pan functionality
   c). Pathfinding to each room
   d). Drag and drop equipment and service requests in each room
   e). View additional details for locations, service requests, and equipment
2. Service Requests
   a). Service requests are requests that staff and patients can make for certain needs and wants
   b). Each service request created will be stored in the database and can be seen in the service request listings with their assigned staff and status
3. Dashboard
   a). Visual representation of which equipment are clean and dirty
   b). Will update when changes are made to the service requests
   c). Automatically sends dirty equipment to cleaning rooms when reaching a cap
4. Employees list
   a). List of employees logged into the system
5. CCTV System
   a). Can be used to integrate CCTV's into application
   b). Detects any camera connected to device
6. Game
   a). When employees have free time, they can play a simple brick breaker game
7. Switch Server
   a). The application can switch database from local to client server database
   b). A client server must be online in order for this to work
8. Simulator
   a). Simulates how day-to-day equipment workflow will look like
