## Task 7.1 — Explain Network Concepts

| Concept | Explain it in your own words | Example |
|---|---|---|
| LAN | A network covering a small area, such as a home, lab or office. | A home Wi-Fi network connecting multiple devices. |
| MAN | A network covering a city or large campus area. | A network connecting different buildings of a university campus. |
| WAN | A network covering large geographical areas. | The Internet. |
| DNS | Translates a domain name into an IP address. | Translating `google.com` into its server's IP address. |
| Router | Connects networks and forwards data between them. | A home router connecting devices to the Internet. |
| Protocol | A set of rules devices follow to communicate. | HTTP and HTTPS. |
| Packet switching | Data is divided into packets that travel across a network. | Sending data across the Internet in smaller packets. |
| Client-server | A client requests a service and a server provides it. | A browser requesting a webpage from a web server. |

## Task 7.2 — Observe Network Information

### Objective
Check whether the computer can reach a public example website and use a DNS lookup tool to find the network address associated with the example domain.

### 1. Connectivity Test

**Command used:**
`ping -c 4 example.com`

**What does a connectivity test help you check?**

A connectivity test helps check whether the computer can communicate with another device or server over a network. It shows whether packets are successfully reaching the destination and provides information about response time and packet loss.

### 2. DNS Lookup

**Command used:**
`nslookup example.com`

**What information does a DNS lookup display?**

A DNS lookup displays information about the domain name being searched and the IP address associated with it. It can also show which DNS server handled the request.

### 3. Role of DNS

**What role does DNS play when you enter a website name in a browser?**

DNS translates the human-readable website name into an IP address. This allows the browser to locate the correct server and establish communication with it.

### Observation

The connectivity test was used to check communication with `example.com`, while the DNS lookup was used to find the IP address associated with the domain.

## Task 7.3 — What Happens When You Open a Website?

### Objective
Explain the steps involved in opening a website and how different parts of a computer network communicate to display a webpage.

### Steps

1. **User enters a website address:** The user enters a website name or URL into the browser. The browser acts as the client and prepares to request the webpage.

2. **DNS lookup:** The browser uses DNS to translate the website's domain name into an IP address so that the server can be located.

3. **Connection to the server:** The computer uses its network connection to communicate with the server. The router forwards data between networks so that it can reach its destination.

4. **Request is sent:** The browser sends a request to the web server using a communication protocol such as HTTP or HTTPS.

5. **Server processes the request:** The server receives the request, processes it and prepares the requested webpage or resource.

6. **Server sends a response:** The server sends the requested data back to the client through the network in packets.

7. **Browser displays the webpage:** The browser receives and processes the response, loads the required resources and displays the webpage to the user.

### My Understanding

Opening a website involves communication between a client and a server. DNS helps locate the server using its domain name, while the router forwards data across networks. Protocols define how the client and server communicate, and packet switching allows data to travel in smaller units. The browser processes the server's response and displays the webpage.
