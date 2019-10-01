One of the painpoints with having a large number of members in a non-profit organization is to find the best possible ways to engage 
and interact with your members in meaningful ways.  To this end, at roughly 300+ members, we needed to find a way to send text
messages to our members in a cost effective way.  To do this, we decided to go with Twilio, and leveraged their API.

Our member data lived in a tool called "Wild Apricot".  We needed to send text messages to our membership which changed hourly
using this live data via an API call to Twilio.  Luckily, there were some examples of this, albeit none were very clear on how
to "stitch" these tools together in a meaningful way.  

This script will show how we approached this problem and created a UI on top of our Wordpress website to administer this.  
