# VUT-Postman
VUT - ACI Postman collection

Configuration Steps :
Fabric Access Policy
  1. Add VLAN to VLAN Pools
  2. Create Interface Policy Group (use existing Domains and AEP)
  3. Create Interface Selector (use existing Interface Profile and Switch Profile)
Policy Model
  1. Create Tenant
  2. Create VRF
  3. Create Filter
  4. Create Contract and Subject
  5. Create BDs (Subnets)
  6. Create Application Profile
  7. Create EPG 
    1. Apply domain to EPG
    2. Apply static ports to EPG
    3. Apply contract to EPG
  8. Create L3Out (with Logical Interface Profile)
    1. Add static routes
    2. Add L3OutEPG
    3. Apply contract to L3OutEPG
    4. Associate BDs to L3Out
