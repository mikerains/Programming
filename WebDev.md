started Sep 4, 2017

# SSL certificates
## The Basics
Certificates have 3 major service variances
*  Warranty: Anywhere between $10,000 and $1 million
*  Are wildcardable, so will work on any first-level subdomains
* Validate only the domain name or also validate Business Name

## Low-cost providers
*   https://www.thoughtco.com/cheap-ssl-certificates-and-recommendations-3469539
*   https://www.namecheap.com/security/ssl-certificates/domain-validation.aspx?utm_source=SAS&utm_medium=Affiliate&utm_campaign=314743&affnetwork=sas
*   https://www.networksolutions.com/timeout.html

## Https Free By Leveraging Cloudflare CDN
https://css-tricks.com/switching-site-https-shoes*   tring-budget/

## M7 Computers
* Using this one for Development: https://www.namecheap.com/security/ssl-certificates/comodo/positivessl.aspx

## Obtaining a certificate for Azure
* https://azure.microsoft.com/en-us/blog/obtaining-a-certificate-for-use-with-windows-azure-web-sites-waws/
* https://www.digicert.com/csr-creation-ssl-installation-windows-azure-website.htm
* https://stackoverflow.com/questions/35409127/how-to-create-a-csr-file-for-azure-web-app
* https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-custom-ssl
* https://www.digicert.com/csr-creation-ssl-installation-windows-azure-website.htm

### Certificate Request (CSR)
* Input File Parameters: https://technet.microsoft.com/en-us/library/dn296456(v=ws.11).aspx
* https://technet.microsoft.com/en-us/library/dn296456.aspx


# W3C - Navigation Timing
How to measure time to retrieve pages by using the javascript 'performance' object
* https://www.w3.org/TR/navigation-timing/#processing-model
````
<html>
<head>
<script type="text/javascript">
function onLoad() {
  var now = new Date().getTime();
  var page_load_time = now - performance.timing.navigationStart;
  alert("User-perceived page loading time: " + page_load_time);
}

</script>
</head>
<body onload="onLoad()">
<!- Main page body goes from here. -->
</body>
</html>
````
