# 📌 Projet NFS - Infrastructure Réseau Sécurisée sous VMware

## 📄 Information Personnelle
- **Nom de l'étudiant 1** : LE Huyen Trang  
  **Numéro d'étudiant** : 20245468  
- **Nom de l'étudiant 2** : BOUROU Imene  
  **Numéro d'étudiant** : 20244967  

## 📢 Introduction
Ce projet a pour objectif d’acquérir des compétences pratiques en :
- ✅ **Mise en place d'une infrastructure réseau sécurisée sous VMware**
- ✅ **Configuration et gestion du protocole NFS pour le partage de fichiers**
- ✅ **Isolation du trafic réseau entre différentes machines clientes**
- ✅ **Mise en œuvre de la redondance réseau pour assurer la disponibilité du serveur de fichiers**

## 🛠 Technologies & Outils Utilisés
- **VMware** : Virtualisation des machines
- **Cumulus Linux** : OS pour la gestion des commutateurs
- **Linux** : OS pour les machines clientes et le serveur NFS
- **Netplan** : Configuration réseau simplifiée
- **NFS (Network File System)** : Partage de fichiers en réseau
- **iptables** : Gestion des règles de filtrage réseau

## 📂 Structure du Répertoire
```
📁 Projet_NFS
│-- 📄 rapport.pdf  # Rapport détaillé du projet
│-- 📊 slides.pdf   # Présentation du projet
│-- 📁 result       # Résultats et captures
│   ├── capture.pcap  # Captures Wireshark
│   ├── screenshot1.png  # Capture d'écran
│   ├── screenshot2.png  # Capture d'écran
│-- 📁 pratique    # Résultats des machines virtuelles
│   ├── 📁 machines_linux  # Fichiers des machines sous Linux
│   │   ├── machine1   # Fichiers de la machine virtuelle 1
│   │   ├── machine2   # Fichiers de la machine virtuelle 2
│   │   ├── serveur_nfs  # Fichiers du serveur NFS
│   ├── 📁 switches  # Fichiers des switches sous Cumulus Linux
│   │   ├── switch1 # Fichiers de la machine switch 1
│   │   ├── switch2 # Fichiers de la machine switch 2
│   │   ├── switch3 # Fichiers de la machine switch 3
```

## 🔗 Liens Utiles & Sources
- [📚 Théorie de NFS](https://www.geeksforgeeks.org/network-file-system-nfs/) - GeeksforGeeks
- [📖 Installation de NFS dans Linux Ubuntu](https://ubuntu.com/server/docs/service-nfs) - Ubuntu Server documentation
- [🏗 Architecture de NFS](https://www.quobyte.com/network-file-system/) - Quobyte
- [💬 Communication dans le protocole NFS](https://www.ninjaone.com/blog/network-file-system-nfs/) - NinjaOne
- [ansible playbooks](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html) -Ansible

## 📌 Instructions d'Installation
1. **Cloner le dépôt** :
   ```bash
   git clone -b main https://github.com/TrangHuyenLe/nfs.git
   cd nfs
   ```
2. **Configurer l’environnement** (machines, commutateurs, serveur NFS)
3. **Suivre la documentation** pour la mise en place détaillée
4. **Tester le bon fonctionnement** selon les scénarios prévus

## 📧 Contact
Si vous avez des questions, n'hésitez pas à nous contacter via email ou Discord.

