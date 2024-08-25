---
 title: "Sharing WAMP from localhost" 
 description: "WAMP (Windows, Apache, MySQL, PHP) is a software stack used for web development on Windows operating systems."
 date: 2023-05-26T01:17:02+05:30 
 draft: false 
 tags: ["guide"]
 og_image: "/quickstart/images/wamp.svg"
---

With [pinggy.io](https://pinggy.io) you can share your WAMP server from localhost with just a single command. **Replace the port 80 with the port where your server is running.**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to access the server.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to WAMP server:" portstring="WAMP Port" localport="80" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
