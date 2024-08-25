---
 title: "Test Github webhooks locally" 
 description: "GitHub is a code hosting platform for software development and version 
 control."
 date: 2023-05-26T01:15:25+05:30 
 draft: false 
 tags: ["guide", "webhook"]
 og_image: "/quickstart/images/github.svg"
---

With [pinggy.io](https://pinggy.io) you can share your GitHub Webhook from localhost with just a single command. **Replace the port 80 with the port where your local development server is running and make sure it is ready to receive requests (e.g. http://localhost:80/webhooks).**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to test the webhook.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to GitHub Webhook:" portstring="GitHub Port" localport="80" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
