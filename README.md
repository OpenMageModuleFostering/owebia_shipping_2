
# ENGLISH

## How to manually install the extension?

- Backup your store database and web directory
- Login to Magento backend
- Go to System > Tools > Compilations, if Compiler Status is Enabled, disable the compilation
- Uncompress the archive file, then copy the directory "app" in your Magento root directory
- Go to System > Cache Management. Click button Flush Magento Cache
- Logout from Magento backend and login again

## How to completely uninstall the extension ?
After having uninstalled the extension in Magento Connect Manager, some references remain in the database.  
To solve this problem, you must execute the following MySQL query:

    DELETE FROM `core_config_data` WHERE `path` LIKE 'carriers/owebiashipping_/%'

--------------------------

# FRANCAIS

## Comment installer l'extension manuellement ?

- Faites une sauvegarde de votre boutique et de votre répertoire web
- Connectez-vous au panneau d'administration de Magento
- Allez dans Système > Outils > Compilation, désactiver le compilateur s'il est activé
- Décompresser l'archive, puis copier le répertoire "app" dans le répertoire racine de votre boutique Magento
- Allez dans Système > Gestion du cache. Cliquer sur le bouton Vider le cache de Magento
- Déconnectez-vous du panneau d'administration de Magento puis connectez-vous à nouveau

## Comment désinstaller complètement l’extension ?
Après avoir désinstallé l’extension depuis Magento Connect Manager, il reste encore des références dans la base de donnée.  
Pour solutionner ce problème, il faut exécuter la requête MySQL suivante :

    DELETE FROM `core_config_data` WHERE `path` LIKE 'carriers/owebiashipping_/%'
