.. include:: /substitutions.rsti

Using Public IP Addresses on an Interface
=========================================

:doc:`/nat/outbound-nat` to use a routable/public IP address subnet on the LAN.

Navigate to **Firewall > NAT**, **Outbound** tab and select **Manual Outbound
NAT**. Click **Save**, then remove the automatically generated NAT rule(s)
referencing the public IP address subnets. Click **Apply Changes** and then
for good measure, :doc:`/firewall/reset-states`.
