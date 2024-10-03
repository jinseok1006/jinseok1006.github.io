---
title: Summary of Web Service Design
date: 2024-09-19
---

The process of accessing a webpage by entering a domain into the web browser's address bar proceeds as follows:

1. **Domain Input**: The user types the domain name (e.g., www.example.com) into the address bar of the web browser. This domain is designed to be human-readable.

2. **DNS Request**: The browser sends a request to the DNS (Domain Name System) to find the IP address of the corresponding domain. DNS matches the domain with its associated IP address and responds.

3. **IP Address Return**: The DNS server returns the IP address (e.g., 192.0.2.1) that corresponds to the domain. This IP address is the actual location of the web server.

4. **Request Sent to Server**: The browser uses the received IP address to send an HTTP/HTTPS request to that web server. The request travels through the TCP/IP protocol, typically using port 80 (HTTP) or 443 (HTTPS).

5. **Web Server Response**: The web server that receives the request processes the necessary resources (HTML, images, CSS, etc.) and sends a response back to the web browser.

6. **Web Page Rendering**: The browser interprets the received HTML, CSS, and JavaScript files to render the webpage on the screen.

7. **User Views the Page**: The user can now see the requested webpage in the web browser.

In this process, IP addresses, DNS, and HTTP/HTTPS protocols play significant roles.
