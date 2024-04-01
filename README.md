# Internet Of Things

IOT est un domaine en pleine évolution , ce projet met en lumière l'étât de mes recherches sur ce sujet.

A cette date trois développements m'ont semblé intéressant du point de vue de la possibilité de créer une APP Android permettant  d'interfacer des controleurs tels:
+ RaspberryPi
+ Arduino
+ ESP8266
+ ESP32 Puisque 8266 est maintenant dépassé. 

Un bon tutoriel d'introduction pour l'ESP8266 est sur Instructable https://www.instructables.com/class/Internet-of-Things-Class/ 
Des essais fonctionnels ont été effectués avec Bkluetooth Serial et une application Android , voir le détail ici: https://github.com/dubser/BluetoothSerial

 # appinventor
 Développé par MIT pour les besoins des enseigants et trop largement utilisé par des développeurs étrangers a ce milieu ont amené les supporteurs  de MIT a former Thunkable pour monétiser le support du produit.   
 Après avoir survolé thunkable & blynk il m'apparaît que pour mes besoins qui en sont d'apprentissage de l'architecture des IOT monitorés et controlés par une tablette Android seront mieux servis en investissant dans l'apprentissage de AI2. Cependant,la communication entre l'aplication et l'ESP ou l'arduino est plus complexe.   
 A première vue AI2 peut utiliser Redis qui possède des librairies sur Esp32 et aussi en Python sur RaspburryPi et pourrais donc servir de support de communication entre Android et les devices Iot.  
 Aussi Redis AI2 peut utiliser Firebase dont le serveur est maintenu par Google.   

https://opensourceforu.com/2016/10/web-database-using-app-inventor-2/   


Aussi un bel exemple d'UIO basé sur AI2 qui interface directement un ESP32 est documenté ici:

https://groups.google.com/forum/#!searchin/mitappinventortest/connectivity$20web%7Csort:date/mitappinventortest/QtuQ1Iivpc4/6WAdXvlpCwAJ   

Des essais fonctionnels ont été effectués avec Bkluetooth Serial et une application Android , voir le détail ici: https://github.com/dubser/BluetoothSerial


  

# thunkable
Fork monétisable de appinventor créé pour permettre le support de appinventor hors du contexte de l'enseignement. 
L'IDE web classique est actuellemet en migration vers le xIDE et tous les blocs de l'environnement classique ne sont pas migrés 
et le développement semble assez lent.   
Les versions X et classiques sont incompatibles ce qui force les développeurs a réécrire leurs app pour y effectuer des mofif. Ca provoque une forte grogne.

# blynk
Est un autre IDE web , fork de appinventor , qui semble largement utilisé pour créer des APP Osx mais aussi Android .  A été utilisé amplement sparkfun.

https://www.sparkfun.com/products/13794?_ga=2.86239835.210348357.1559227692-1176360202.1552756028
https://learn.sparkfun.com/tutorials/esp8266-thing-development-board-hookup-guide?_ga=2.195095535.210348357.1559227692-1176360202.1552756028
https://learn.sparkfun.com/tutorials/esp8266-thing-development-board-hookup-guide/example-sketch-blink-with-blynk

Actuellement blynk avec l'introduction de la notion de ENERGY limite les app(s) a de petites démos. Toute application d'envergure force a débourser des $. De plus Blynk ne m'apparait pas permettre une exportation gratuite de fichier .apk.
