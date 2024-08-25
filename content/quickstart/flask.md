---
 title: "Sharing Flask from localhost" 
 description: "Flask is a lightweight micro web framework written in Python." 
 date: 2023-05-26T01:15:25+05:30 
 draft: false 
 tags: ["guide"]
 og_image: "/quickstart/images/flask.svg"
---

With [pinggy.io](https://pinggy.io) you can share your Flask server from localhost with just a single command. **Replace the port 5000 with the port where your server is running.**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to access the Flask server.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to Flask server:" portstring="Flask Port" localport="5000" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
