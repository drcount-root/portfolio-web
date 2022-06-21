---
title: "Java - CLI based group chat application"
description: "A Java based CLI client-server modeled group-chat application."
dateString: Dec 2021 - Dec 2021
draft: false
tags: ["Java", "Socket Programming", "Git", "GitHub", "Linux Shell"]
showToc: false
weight: 4
cover:
  image: "projects/java-groupchat/cover.png"
---

### 🔗 [GitHub](https://github.com/drcount-root/Java-GroupChat-Application)

## Description

For execution details please refer to the <a href="https://raw.githubusercontent.com/drcount-root/Java-GroupChat-Application/main/ScreenShot%20IpOp.png" target="_blank">image</a>.

Now it's time to clear some theoritical concepts.

A multicast host is specified by a class D IP address and by a standard UDP port number. Class D IP addresses are in the range 224.0.0.0 to 239.255.255.255, inclusive. The address 224.0.0.0 is reserved and should not be used. We can use IP addresses between 224.0.0.0 to 239.255.255.255.

\*NOTE: port numbers 0 through 1023 are reserved.

We need two threads in this application. One for accepting the user input (using the java.util.Scanner class) and the other for reading the messages sent from other clients. Hence I have separated the thread which does the reading work into ReadThreadclass.

For leaving the group, any of the user can type in Exit to terminate the session.

The above program is executed on a single machine. Socket programming is meant for distributed programming. The same piece of code snippet when present on different machines which have Java installed can satisfy that requirement.

Link : <a href="https://github.com/drcount-root/Java-GroupChat-Application" target="_blank"><b>Check It Out!</b></a>
