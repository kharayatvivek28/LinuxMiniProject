# Linux Administration Lab Mini Project

### HTTP Web Server

<hr>
<b>About Project<b><br>
This project involves setting up a basic HTTP web server on a Linux virtual machine (VM) using Python’s built-in HTTP server module. The objective is to create a functional web server that can host static web files like HTML, CSS, and JavaScript, making them accessible both locally and externally. This type of server is ideal for lightweight web applications, testing environments, and educational projects.<br>

<b>Key Components<b><br>

1. Linux Virtual Machine (VM): The VM serves as the host for the HTTP server and web files. Using a VM ensures that the server environment is isolated, providing a controlled testing space.<br>
2. Python HTTP Server:<br>
   1. Python’s http.server is a lightweight web server that simplifies the process of serving web pages without needing a complex server setup.<br>
   2. By binding to 0.0.0.0, the server listens on all available network interfaces, making it accessible to any device within the same network.<br>
3. Firewall Configuration:<br>
   1. Firewalld is used to manage the firewall settings, allowing traffic through port 8000.<br>
   2. The firewall rules ensure that the web server can be reached by external devices, adding a layer of control over which ports are open to incoming connections.<br>
4. Web Files:<br>
   1. The project hosts a simple collection of static web files, including HTML, CSS, and JavaScript.<br>
   2. These files are stored in a directory on the VM and are served directly to clients when they access the server.<br>
