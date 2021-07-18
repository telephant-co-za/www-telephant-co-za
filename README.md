# Telephant Static Landing Page

### Acknowledgements
* This static website was created with the help of a template that was purchased. 
* [Undraw.co](https://undraw.co/) was used to generate the images. 
* For a fee, a freelance graphic designer created the Telephant logo.

### CI/CD Process
* Any github push to this repository triggers a Code Build Pipeline, which uploads the files to an AWS S3 bucket.
* The S3 bucket is configured for static web hosting and has a subdomain (www) linked to it.

### Purpose
This static landing page will be hosted separately from the app and will not be a part of the Single Page App, which will be hosted on a separate subdomain (app). Other relevant static pages, such as the Terms and Conditions page, will be linked from this page.  This configuration enables for a redirect by Route 53 back to this landing page in the event that the app servers go down and are unavailable.

### Available
The live website can be found at: [https://www.telephant.co.za](https://www.telephant.co.za).
