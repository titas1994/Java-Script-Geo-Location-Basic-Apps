# Java-Script-Geo-Location-Basic-Apps<br>
In this Script I will show the local time, Server Time, Public Ip address Of User and Location of the user. I also Use the the Google Map API key for testing purpose. You can see the JavaScript file under assets folder.<br>
.<br>
<b>Looking up IP Addresses API</b><br>
1.https://extreme-ip-lookup.com/json/<br>
2.http://ip-api.com/json<br>
3.https://ipinfo.io/<br>
4.https://geoip-db.com<br>
.<br>
<b>Getting local timezone of users in JavaScript.</b><br>
<b>Jstz package</b><br>
Jstz is a simple lighter package for detecting timezone.<b>It also makes use of the Intl API, so you can be confident of its results. To use the package, you can grab the CDN as follows:<br>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.6/jstz.min.js"></script><br>
.<br>
Ip Address Lookup Script<br>
<script src= "https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"> </script> <br>
<script><br>
   $.getJSON("https://api.ipify.org?format=json", function(data) { <br>
   $("#IP").html(data.ip);<br>
   })<br>
</script><br>
<!--End Here-->
