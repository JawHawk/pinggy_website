---
 title: "Sharing GitLab from localhost" 
 description: "GitLab is a web-based DevOps platform for code review, project management, and CI/CD."
 date: 2023-05-26T01:15:25+05:30 
 draft: false 
 tags: ["guide"]
 og_image: "/quickstart/images/gitlab.svg"
---

With [pinggy.io](https://pinggy.io) you can share your GitLab server from localhost with just a single command. **Replace the port 80 with the port where your server is running.**

Pinggy will give you a URL like `https://ranlkfsbjkxry.a.pinggy.link`. Use this URL to access the server.

{{< pinggytunnel box="true" tunnelstring="Paste this command to start a tunnel to GitLab server:" portstring="GitLab Port" localport="80" webdebugenabled=false keepalive=true >}}
{{< /pinggytunnel >}}

<hr>
