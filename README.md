# Virtualisation-Esxi-Proxmox-

Lors de ce projet, nous avons creer telecharger l'iso de:
-- proxmox
-- Esxi ( Dans Esxi, Nous avons fait 2 Esxi, Nous les avons relie a notre Vcenter grace a leurs ips, dans chaque Esxi, Nous avons mis 2 VMs(Ubuntu, Debian ou Windows)
-- Vcenter
-- Veeam (mais on peux le faire avec OpenNebula ou Restic): Dans veeam, Nous avons relie egalement chaque Esxi, et Nuus avons essaye de sauvegarder une VM(replicat ou Backup) et supprime la VVM dans l'Esxi et ensuite la recupere dans Veeam. De meme, pour un dossier qui contenait des fichiers que nous avons fait de sauvegarder(replicat ou Backup) ensuite supprimer dans Esxi et recuperer dans Veeam
