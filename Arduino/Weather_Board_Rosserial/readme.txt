Weather_Board_rosserial.ino publishes ROS topic that contanins the weather board data. 
Note that you need rosserial to subscribe to this topic.

Publisher Name: 
wb_publisher

Data Format: 
We are using the CSV data format which is described as below:
[SHT15 Temperature], [SHT15 Humidity], [SHT15 Dewpoint], [BMP085 Presure], [BMP085 Temperature], [TEMT6000 Light]

* Rain and wind readings are omitted since we do not have the weather meters.
