# Purdue Crystal Ball

## What it does
Our website reads and displays a new fortune every time you refresh the page. In addition to the fortunes being displayed on our webpage, there’s a number displayed at the bottom of the page that the user can text to receive fortunes via messages. 

## How we built it
Our final project consists of two parts: the webpage and the communication API. The webpage was created using HTML, CSS, and JavaScript. We used HTML and CSS to design the website layout and handle all the displays. Then, we used JavaScript to create a function that randomly generates fortunes from a predetermined set we created. In addition to the code for the webpage, we also registered a domain name through domain.com and used a virtual cloud server provided by Google Cloud Server (GCP). To incorporate our code into the virtual cloud server, we created a compute engine virtual machine so we could connect our domain to GCP's Cloud DNS service. The communication API was created using Twilio Studio. Fortunes are randomly sent to the user via text through the implementation of JavaScript on Twilio. 

## Challenges we ran into
We had to overcome a couple of challenges when completing this project. One challenge was working with the communication API, Twilio. Since this was our first time using Twilio Studio, we had to watch YouTube videos and research about it to understand how to use it as well as being able to create the features that we wanted.

One challenge for the website was getting the genie lamp image to appear on our website. We couldn't figure out whether it was because of an incorrect file path or something was wrong with our website. When we looked at Stack Overflow and other websites to troubleshoot this issue, they really emphasized having the correct file path in the HTML tag. This resulted in various ways to change the file path so it would work. However, despite our efforts, the image still was not showing up. After scouring the internet, we found a person saying to use an external service to host our image. This was exactly what we needed. We were able to get the direct link to our image from this site and it allowed the image to finally show up on our website!

Lastly, we had lots of trouble setting up the domain and importing our code into the domain's webpage. We didn't know how to set up the DNS server, acquire the IP address, or import our pre-written HTML file into the server. Thankfully, Anuhya from MLH gave us lots of resources and advice for all the challenges above. Eventually, we were able to troubleshoot our way through the problems we encountered with the help of Stack Overflow and the articles Anuhya provided. 
 
## Accomplishments that we're proud of
We are proud that we have successfully completed this project. We had gone through many ideas and didn't know if this was feasible for a hackathon because we didn't have much experience with Javascript or APIs. Additionally, we are glad that we have learned more about HTML, CSS, Javascript, virtual machines, and the whole process of setting up a website. We are also proud of resolving the genie lamp issue as we have tried many solutions and almost gave up. So, we are glad that we persevere through all our challenges and eventually resolved them.

## What we learned
As mentioned before, we used Twilio's API service. None of us had ever used Twilio previously or an API, so it was a good learning experience. It was surprising how easy Twilio made it to make things like a chatbot or an appointment reminder. We ended up using Twilio's Function tool to make our text fortune service, which was a good learning experience. Another thing we learned was more about HTML and CSS. All of us had some experience, but it was nice to get a refresher, created a website from scratch, and learn some cool tricks through research online. We have also learned how to register a domain, set up a virtual machine and DNS servers, acquire our IP address, and import our code using Node.js. This was especially hard as none of us had prior experience in building a website from scratch and setting up a DNS server. 

## What's next for Purdue Crystal Ball 
If possible, we plan to add more fortunes and implement more design choices to make the website look nice on all devices. We would also work on adding unverified numbers for the fortune text service so other users can enjoy it too.

## Resources
https://www.twilio.com/docs/runtime/functions
https://stories.mlh.io/launch-your-first-website-with-domain-com-and-google-cloud-platform-b0d72c448b6f

IP address: 35.222.203.10
