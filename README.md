neutron-desgnate-fip-plugin
===========================

# Description
Create a domain and fip records automatically for multi-tenancy via designate. This means whenever a floating ip(fip) is created via neutron, a DNS domain for the tenent that fip is getting created is checked and created if doesn't exist. A DNS record is create to the assosated fip in the tenant dns domain.

