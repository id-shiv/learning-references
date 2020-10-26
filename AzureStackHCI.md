# Azure Stack HCI

## Azure Stack HCI Vs Storage Spaces Direct (with Windows Server OS)

- Is a purpose built OS for HCI and more frequently maintained and released with newer features.
- Stretch Clusters:
  - Is supported with Azure Stack HCI OS (from 4 nodes to 16 nodes in a different location).
  - Combine nodes in different geographical location to form a cluster.
  - Nodes in different room (e.g. for a fire disasters recovery) to nodes in different continents.
  - Replication could be with synchronous mode (for shorter distance) and asynchronous mode (between longer distance).
- Integrate Azure Stack HCI and manage remotely with,
  - Azure Portal (in cloud) or,
  - Windows Admin Center (on-premise).
- Fast repair.

## Azure Stack HCI as a service

- OS is licensed per core.
- Register with Azure for subscription billing.
- with this all of Azure Stack HCI are stacked as Azure Resources (even on-premise).
- Azure IaaS instance in Azure cloud requires VPN + Azure vNet to be configured to be managed locally from Edge (i.e. WAC).
  - Solution: Windows Admin Center integrated into Azure Portal.