Modifier le fichier `/etc/asterisk/users.con.`

Entrer les éléments suivants :

`[88012]`

`type=friend`

`host=dynamic`

`dtmfmode=rfc2833`

`disallow=all`

`allow=ulaw`

`fullname = Stephanie Groot`

`username = sgroot`

`secret=0000`

`phone=88012`

`vmsecret=1234`

`mailbox=88012@ff`

`callcounter=yes`

`context = Marketing`

`service=Finances`

Sauvegarder le fichier de configuration & redémarrez Asterisk pour prendre en compte les modifications `sudo systemctl restart asterisk`
