#Stworzenie sekretu dla PiHole w docker
```
echo sample_password_change_me | docker secret create piHolePassword -
```

#Uruchomienie kontenera
```
docker-compose up -d
```

#Volumes
Żeby docker poprawnie się uruchomił należy utworzyć 2 lokalizacje:
- /media/Intranet-of-Things/Volumes/PiHole/etc-pihole/
- /media/Intranet-of-Things/Volumes/PiHole/etc-dnsmasq.d/
