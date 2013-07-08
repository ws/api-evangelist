---
layout: default
title: 'Twitter Rolls Twitter com Back to a Server Side Architecture'
url: 'http://apievangelist.com2012/05/29/twitter-rolls-twitter.com-back-to-a-server-side-architecture/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/Twitter-Home.png'
---



     <img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/twitter/Twitter-Home.png"  width="250" align="right" />
</p>
<p>
     Twitter just <a href="http://engineering.twitter.com/2012/05/improving-performance-on-twittercom.html">rolled back their architectural approach for Twitter.com</a> back to a server side implementation.
</p>
<p>
     If you remember back in September of 2010, <a href="/admin/blog/twitter+eats+own+dogfood+api+evangelist">Twitter rebuilt Twitter.com to use a web application architecture</a> that pushed all of the UI rendering and logic to Javascript running in the browser and consumed the Twitter API directly.
</p>
<p>
     Now they are "taking back control" of their front-end performance by moving the rendering back to the server. They don't say whether they don't use the APIs at all, but I am working under the assumption that they abandoned them.
</p>
<p>
     Twitter felt the API driven web application architecture broke new ground, offered a number of advantages, but it lacked support for various optimization techniques available only on the server.
</p>
<p>
     I was excited to see Twitter go with the API driven approach, along other sites, like <a title="FCC Website" href="http://blog.programmableweb.com/2011/04/06/everything-should-be-an-api-says-fcc/">the FCC</a>.  I hate to see them abandon it.
</p>
<p>
     <strong>What does this say about an API oriented architecture?</strong>
</p>
<p>
     Are we not ready? Are there are not enough tools for optimization, or the talent to deliver the performance necessary for Internet at scale via API driven architecture?  Or maybe there are other business reasons for stopping eating their own dog food and going back to a server side architecture?
</p>
