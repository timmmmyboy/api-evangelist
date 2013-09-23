---
layout: post
title: "Will REST Accommodate Our API Needs in the Future?"
url: 'http://apievangelist.com/2011/08/02/will-rest-accommodate-our-needs-in-the-future/'
image: ''
---

<img src="http://kinlane-productions.s3.amazonaws.com/netflix/netflix-many-devices-using-api.png" alt="" width="325" align="right" />After reading Adams post from last week, [Redesigning the Netflix API: No Versions, Many Endpoints][1], and lookingthrough the slides from [Daniel Jacobson's Netflix talk at OSCON][2] again, I started thinking more about the future of REST, and more specifically when it comes to delivering APIs that support a wide variety of devices.

There are a lot of things to consider when it comes each device, such as aspect ratios, touch screens, remote controls, game controllers, voice commands, memory and just a wide range of user expectations in the context of the device.

In addition to restriction imposed by the hardware, the network constraints will also vary, with some devices on broadband, others on wifi connections, and a whole new breed of 4G devices.

Jacobsens conclusion: "Most REST APIs are designed to generically accommodate the needs of a large number of clients�but they are optimized for none".

Netflix is pushing into uncharted territory with their use of cloud computing and APIs. But is their situation unique? Will other APIs need to serve that many devices?

There are a growing number of mobile devices running various operating systems, new incarnations of the tablet, e-readers, webbooks,music devices, televisions, appliances and our automobiles. Beyond that, there is the billions of sensors being develop to track food, medicine, agriculture, energy, health care, livestock, weather, traffic and anything else we can track.

Will RESTful APIs continue to deliver when it comes to the Internet of Things? The network and hardware constraints upon an API will only grow. Do we need to agree upon more standards around REST and JSON to help them specialize?

Lot's more to think about, and I'm sure Netflix and other API providers will keep pushing REST to see what it can handle, and help define whats next.

   [1]: http://blog.programmableweb.com/2011/07/28/redesigning-the-netflix-api-no-versions-many-endpoints/ (Redesigning the Netflix API No Versions, Many Endpoints)
   [2]: http://www.slideshare.net/danieljacobson/redesigning-the-netflix-api-oscon?from=ss_embed (Daniel Jacobson's NEtflix talk at OSCON)