# Partition disque dur amovible rendu illisible sur un PC

Si vous êtes confronté un jour à ce problème, qui après un passage  sur un Mac (Apple), vous interdit l’accès à votre DD externe, voici la  manipulation pour rendre votre disque dur à nouveau opérationnel (voir  capture ci-dessous).

![EFI](http://webinnov.fr/blog/news/2014/2014-02-26/Mac_PC/efi.png)

 **Rendez-moi mon NTFS:** **et supprimer moi cette partition EFI que je ne saurais voir.**

**ATTENTION :** Toutes vos données sur ce disque seront perdues

1 – Ouvrir une invite de commandes (Dos) (dans fenêtre exécuter : Taper **cmd.exe**)

2 – Lancer la commande **DiskPart** (Voir image ci-dessous)
 ![DiskPart](http://webinnov.fr/blog/news/2014/2014-02-26/Mac_PC/diskpart.png)

3 – Puis « **List Disk** » pour afficher les disques dur présents sur votre PC (Voir image ci-dessus)

4 – Vos disque sont numérotés. Identifiez le disque que vous souhaitez récupérer (Pour formatage).

5 – Puis taper la commande suivante : « **select disk \**** » (***\*** représente le numéro de votre disque à formater)

6 – Enfin taper cette derniere ligne de commande : « **clean** »

**Maintenant, il ne vous reste plus qu’à reformater votre disque qui ne comporte plus qu’une seule et unique partition**

1 – Fenêtre exécuter : Taper **diskmgmt.msc**