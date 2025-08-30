# Azure VM Deployment (Übung)

Dieses Repository enthält einfache Beispiele, wie man in Microsoft Azure
virtuelle Maschinen erstellt. Die Beispiele sind aus meiner Lernphase
(Cybersecurity & SysAdmin) und sollen zeigen, wie man mit der Azure CLI arbeitet.

## Ubuntu VM (CLI)

```bash
az vm create \
  --resource-group MyResourceGroup \
  --name UbuntuTest01 \
  --image Ubuntu2204 \
  --admin-username thomas \
  --generate-ssh-keys
