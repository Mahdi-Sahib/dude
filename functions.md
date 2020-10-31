
- ping rtt\
Name:```ping_rtt```\
Description:```Returns the round-trip time of a ping request to the FirstAddres of a device```\
Code:```round(array_element(ping(device_property("FirstAddress")),0))```
<hr>


- packet loss\
Name: packet_loss_test\
Description: number of replied pings from 10 ping requests (0-10)\
Code:```if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 ) +
if( array_element(ping(device_property("FirstAddress")) , 0)<0 , 0 , 1 )``` 
<hr>
