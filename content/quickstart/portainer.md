---
 title: "Sharing Portainer from localhost" 
 description: "Portainer is a web-based Docker management tool with a graphical user interface."
 date: 2023-05-26T01:18:25+05:30 
 draft: false 
 tags: ["guide"]
 og_image: "/quickstart/images/portainer.svg"
---

With [pinggy.io](https://pinggy.io) you can share your Portainer server from localhost with just a single command. **Replace the port 9000 with the port where your server is running.**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to access the server.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to Portainer server:" portstring="Portainer Port" localport="9000" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
