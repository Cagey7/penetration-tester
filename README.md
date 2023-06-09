# Program for penetration testing
---
With this program, you can analyze ports to identify which services are running on specific ports, check whether a port is up or down, and perform brute force attacks on different services.

### Program usage
---
**Usage for check ports:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  python pentest.py [option] [host] [port]
<br />
**Options:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  -cp, --check-port &nbsp; &nbsp; &nbsp; &nbsp; Checks port
<br />
**Example:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  `python pentest.py --check-port example.com 443`
<br />
**Usage for get port service:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  python pentest.py [option] [first port] [last port]
<br />
**Options:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  -gs, --get-services &nbsp; &nbsp; &nbsp; &nbsp; Gets services by ports
<br />
**Example:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  `python pentest.py --get-services 1 100`
<br />

**Usage for brute force password:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  python pentest.py [option] [url] [username]
<br />
**Options:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  -bf, --brute-force-psswd &nbsp; &nbsp; &nbsp; &nbsp; Start brute force
<br />
**Example:**
<br />
&nbsp; &nbsp; &nbsp; &nbsp;  `python pentest.py -bf http://127.0.0.1:5000/login user`

### Program example of usages
---

![My Image](screenshots/1.png)

![My Image](screenshots/2.png)

![My Image](screenshots/3.png)