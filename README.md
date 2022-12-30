RO en attente de la fin de migration






































# ram
howto RAM

# Effacer le cache de mémoire
Je virtualise sur un PC ancien et d'un coup tout semble rammer même si je kill la VM
=> solution qui pour le moment donne un peu de satisfaction
How to clear cache (https://linuxconfig.org/clear-cache-on-linux)
$ sudo sysctl vm.drop_caches=3
