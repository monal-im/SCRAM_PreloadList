# SCRAM Preload List

To increase XMPP security on first connection, this repository contains an XML file listing all servers supporting SASL SCRAM / EXTERNAL or something better.

This is similar to the HSTS preload list for HTTP.

**Be aware that inclusion in the preload list cannot easily be undone. Servers can be removed, but it takes months for a change to reach users with a Monal update and we cannot make guarantees about other Clients. Don't request inclusion unless you're sure that you can support SCRAM on your server in the long term.**
