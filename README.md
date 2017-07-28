### The Challenge
 
The city of Corellia is one of the largest and most populous cities in our fictional world. Its strategic location in the globe has made it an important trade and culture center. With growing economy and tourism, the city has seen unprecedented growth resulting in an increased number of vehicles people use for personal transportation. 
 
As an emerging smart city, the council of Correlia wants to help people save precise time on searching parking lots to park their vehicles. Congestion resulting due to increasing traffic and a frenetic search for a parking space during peak business hours has been giving some bad publicity lately. A recent study indicated that traffic conditions can be hugely improved, if users could be guided about available parking spaces in the city so that people are wasting time searching for parking areas and congesting the roads in the process.
 
The council has a history of being innovative and has a profound belief that modern day technologies can provide a holistic solution to this problem.
 
### High Level Solution Blueprints and Approach
The city council has also taken a novel approach by choosing to do this as a community project. They are currently looking for enthusiastic and interested engineers from Rubicon Red to solve this problem.  A very high level blueprint of the overall solution is explained here. 
 
As the first step, proximity sensors will help detect vehicle occupancy and stream the live data to an IoT cloud server. The sensor transmits the vehicle’s geolocation, the time it arrived at the parking space and the time when the vehicle leaves the parking space. The parking management system monitors the parking space with the help of live streaming from the cloud based sever.
 
Members of the public can then use a mobile app that communicates with the parking management system to know the availability of parking spaces when they are nearby a parking area. This would drastically reduce the time for searching a parking space. The solution would also let users  buy tickets for their parking from within the app, thus providing a real hassle-free parking experience for them. It would also result in preventing accidents as the users need not focus on finding a parking space rather than focusing on the road. On the other side it would help the city traffic planning council to monitor the occupancy and payment yielding in reduction of nonpayment users benefiting revenue generation for the city.

The smart park solution has the following components:

* Data Sensing and Generation:  Very low cost sensors are available today that  can be configured with a geo-fence based on the geo-location of every parking space. The parking availability/occupancy state for a particular parking space will be detected by sensor based on proximity of a vehicle around the geo-fence of a sensor. Data thus collected, can be streamed live for real time processing of events. The sensor metadata along with the parking space availability status can accurately provide the occupancy instead of traditional methods that are purely based on booking in and out times.
* Event Processing and Integration:  The data generated through the sensors is streamed to an IoT gateway through to an IoT server that can perform real time aggregation and pattern matching. The data can also be sent to a central hub that can drive reporting, real time data analysis leading to generating business events of interest.
* Parking Monitoring & Management: The parking monitoring and management system provides a series of APIs that can be invoked from the upstream event processing and integration layer to update any systems of record. It will typically be comprised of:
Parking Monitoring System to monitor all the demarcated on-street parking space states by means of data it has from the data server. The total number of parking spaces, the total number of available parking spaces, and the total number of occupied parking spaces can be monitored. 
Parking Management System can process data request from end user applications help them search, reserve and book parking spaces. The parking management system has an inventory of all parking sites in the city. In addition, it has a dynamic pricing engine that determines parking rates based on duration, availability and day of the week.
Parking Exception Management system can detect unsolicited parkings in the city and notify local parking authority who can then take an appropriate action (create a parking ticket, request the vehicle be towed, etc).
* User Experience: Any technology solution that involves member of the generic public's involvement or usage must be accompanied by a working mobile application.  A mobile application will provide users an ability to search, request, amend and pay for a parking.
 
The smart park system should be designed in such a way that it is includes covered, open and street side parking. In order to do this, the council has partnered with LightSaber Inc. to install a series of low power proximity sensors at all the parking spots across the city. In addition there are pressure and image sensors at major road intersections to read traffic situation at different times of the day. The technical solution will be explained in more details but before that, the high level solution would involve:
* A cloud based IoT infrastructure for parking sites which can automatically provide information about vacant and occupied parking spots. 
* A rich set of APIs that allows car park management, parking management, user management, notifications and payments.
* A Mobile and Web application allowing users to search, reserve and pay for a parking spot.
* Predictive and descriptive Reporting including reports that can provide real time parking spot availability, 
 
The Corellia city council has evaluated and chose the Oracle Cloud Services stack to build this unique solution and are looking to implement this solution using APICS, IoTCS, ABCS, MCS, PCS, ACCS, ICS, SCC and BICS. Their key qualifications for the overall system design are:
* The solution should demonstrate best practices of integrating the various cloud services so that the overall solution is robust, agile, scalable and sustainable.
* All APIs must support some sort of authentication.
* The solution should be built using an API first approach (a sample swagger based API definition is provided here for reference).
* The solution should demonstrate principles, practices, of creating a collaborative environment that improves software delivery and increases business value (DevOps).
