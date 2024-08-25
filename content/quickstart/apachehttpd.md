---
 title: "Sharing Apache HTTP from localhost" 
 description: "Apache HTTP Server is a free and open-source cross-platform web server software."
 date: 2023-05-26T01:15:25+05:30 
 draft: false 
 tags: ["guide"]
 og_image: "/quickstart/images/apache.svg"
---

With [pinggy.io](https://pinggy.io) you can share your Apache HTTP server from localhost with just a single command. **Replace the port 80 with the port where your server is running.**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to access the server.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to Apache HTTP server:" portstring="Apache server Port" localport="80" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
