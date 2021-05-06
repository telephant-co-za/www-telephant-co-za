# Telephant Static Landing Page

This static website is built using a template that was purchased. Images were sourced on [undraw.co](https://undraw.co/).  The Telephant logo was designed by a freelance graphic designer.

Any github push to this repository will start a Code Build Pipeline that will upload the files to an AWS S3 bucket. A subdomain (www) is mapped to the S3 bucket and the bucket is configured for static web hosting.

Over time, this web page will represent the entire business's needs. For example, "About Us," "Contact Us," and "Legal Terms and Conditions." At that point, some kind of CMS solution will be implemented, it is not intended to be a part of Single Page App which will be hosted on a seperate subdomain (app). This bucket will also house other relevant static pages. For instance, /legal

The live website can be found at: [Telephant Landing Page](https://www.telephant.co.za).