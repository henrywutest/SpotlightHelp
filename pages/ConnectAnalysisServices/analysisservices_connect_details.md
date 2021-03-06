---
title: Connection Details for Analysis Services
last_updated: July 29, 2016
tags: [connection_details,connection_details_for_each_connection_type]
summary: "Monitor SQL Server Analysis Services by supplying the following connection details to Spotlight."
sidebar: c_analysisservices_sidebar
permalink: analysisservices_connect_details.html
folder: ConnectAnalysisServices
---



## How to enter / edit connection details

Use a Spotlight Client to enter / edit connection details.

From the Spotlight Client

1.  Click **Configure \| Connections**.
2.  Double click **Add new connection**.
3.  Fill in the connection details.

## Connection details

### Address

Specify the connect string to link to the Analysis Services server (that is, the Server name, Server Instance name, or IP address).

### Instance

The instance name of the Analysis Services server. This is filled in automatically by Spotlight as the content to follow "/" in the address.

### Connection

Select the Windows server hosting the Analysis Services server. This is required. If the Windows server host is not in the list of connections then click **Create** to add it to the list.

{% include tip.html content="Click **Create** to add a Windows server to the list. This opens [Windows server \| Connection Details][windows_connect_details]." %}


## Test the connection
On entering / modifying connection details in the Spotlight Client, click **Test** to test the connection.


{% include links.html %}
