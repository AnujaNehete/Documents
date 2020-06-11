---
description: This page provides information and references for Kerberos
---

# Kerberos

Kerberos provides network authentication in Hadoop cluster. 

Steps for hadoop ls on Kerberized Hadoop cluster

Kinit \(ask password\) -&gt; sends request to AS and returns TGT

hadoop fs -ls / \(hadoop client\)

The hadoop client uses TGT and ask TGS for service ticket for namenode





Kerberos consists of 

{% tabs %}
{% tab title="KDC" %}
KDC stands for Key Distribution center

It consists of 3 components

* **Database** : Stores principals and other data
* **Authentication Server** : Authenticates user and issues TGT\(ticket granting ticket\)
* **Ticket Granting Server :** Issues service tickets. Before accessing any service in Hadoop you have to get service ticket from TGS
{% endtab %}

{% tab title="Steps to configure Kerberos" %}
[https://www.youtube.com/watch?v=-pBh7fgV6w4](https://www.youtube.com/watch?v=-pBh7fgV6w4)
{% endtab %}
{% endtabs %}





Kerberos authentication : [https://www.youtube.com/watch?v=T8a2QgmWyVU](https://www.youtube.com/watch?v=T8a2QgmWyVU)



