#SSL
# Secure-network-application-using-SSL

SSL

SSL stands for Secure Sockets Layer. 
It is the standard security protocol that offers secure communication between web servers and web clients over an insecure network, such as the internet.
It maintains the privacy and integrity of the data exchanged between a web server and browsers. 
The web server is required to have an SSL certificate to establish a secure SSL connection. SSL encrypts network connection segments which are above the transport layer.

Building secure network applications with SSL and the JSSE

JSSE stands for Java Secure Socket Extension.
JSSE provides an SSL toolkit for Java applications.
In addition to the necessary classes and interfaces, JSSE provides a handy command-line debugging switch that you can use to watch the SSL protocol in action.

In JSSE, everything begins with the factory; there's a factory for SSL sockets and a factory for SSL server sockets. Since generic sockets and server sockets are already quite fundamental to Java network programming, I'll assume that you're familiar with the two and you understand their roles and differences. If you are not, I recommend picking up a good book on Java network programming.

The SSL Socket factory that are used are listed below:
SSLSocket
SSLSocketFactory
SSLServerSocket 
SSLServerSocketFactory


#Transport Layer Security (TLS) is the successor protocol to SSL

