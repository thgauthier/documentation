**Activation ou désactivation automatique**

`sudo systemctl disable apache2`

`sudo systemctl enable apache2`

**Start / Stop / Reload**

`sudo systemctl stop apache2` Pour arrêter apache2

`sudo systemctl start apache2` Pour lancer apache2

`sudo systemctl restart apache2` Pour relancer apache2

`sudo systemctl reload apache2` Pour recharger la configuration d'apache2

**Information**

`sudo apache2ctl -v` Pour voir la version d'Apache utilisée

`sudo apache2ctl -t` Pour tester l'ensemble de la configuration d'Apache

`sudo apache2ctl -S` Pour lister les hôtes virtuels chargés et leurs configurations

`sudo apache2ctl -t -D DUMP_VHOSTS` Pour tester la configuration des hôtes virtuels

`sudo apache2ctl -M` Pour voir les modules d'Apache chargés

**Activation / désactivation site**

`sudo a2ensite` [configuration d'un site à activer]

`sudo a2dissite` [configuration d'un site à désactiver]

**Activation / désactivation service**

`sudo a2enconf` [configuration d'un service à activer]

`sudo a2disconf` [configuration d'un service à désactiver]

**Activation / désactivation module**

`sudo a2enmod` [configuration d'un module à activer]

`sudo a2dismod` [configuration d'un module à désactiver]
