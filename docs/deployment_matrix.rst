#################
Deployment Matrix
#################

What goes where ?
-----------------

Very simple, the application lives only on search head:

+--------------------------------------------+---------------------+
| Splunk Instance                            | Install ?           |
| (role)                                     |                     |
+============================================+=====================+
| Standalone server                          |    X                |
+--------------------------------------------+---------------------+
| Search head (single instance or clustered) |    X                |
+--------------------------------------------+---------------------+
| Indexer (single instance or clustered)     |                     |
+--------------------------------------------+---------------------+
| Master node                                |                     |
+--------------------------------------------+---------------------+
| Deployment servers                         |                     |
+--------------------------------------------+---------------------+
| Heavy Forwarder                            |                     |
+--------------------------------------------+---------------------+
| Universal Forwarder                        |                     |
+--------------------------------------------+---------------------+
