<h1>Analysis of network attack</h1>


<h2>Description</h2>
This project identified and analyzed a SYN Flood Attack (Denial of Service - DoS), where an attacker sends repeated SYN packets to a target server without completing the TCP three-way handshake. This results in half-open connections and overloads the server’s resources, preventing legitimate users from establishing connections. Symptoms included repeated SYN packets from a single IP, lack of ACK packets, and slow website loading times for users. The attack targeted the web server on port 443, leading to degraded performance and connection timeouts. Preventative measures include implementing SYN cookies, configuring firewalls, deploying intrusion prevention systems, and considering load balancing and redundancy to mitigate resource exhaustion.
<br />


<h2>Analysis:</h2>

<p align="center">
<br/>
<img src="https://imgur.com/sbXxDV0.png" height="80%" width="80%" 
<br />
<br/>
<img src="https://imgur.com/0F18UCz.png" height="80%" width="80%" 
<br />

<!-- Add the button at the bottom -->
<div style="text-align: center; margin-top: 20px;">
    <a href="https://github.com/AndrewGreeneCyber" target="_blank" style="text-decoration: none;">
        <button style="background-color: #007BFF; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">
            Visit Homepage
        </button>
    </a>
</div>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
