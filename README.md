# bitbucketpiplines
Standaard script om via FTP jou repo uit te rollen naar een FTP omgeving.

# Hoe gebruik ik dit script
Plaats het bitbucket.yml bestand in de root van je bitbucket project.  
In bitbucket kun je deployment variabele aangeven.  
Voeg hier FTP_USERNAME en FTP_PASSWORD aan toe. 
Met natuurlijk als waarde jou FTP username en wachtwoord.  
Nadat je vervolgens je project commit, zal bitbuckets pipelines wanneer reeds ingesteld. 
Automatisch jou project via FTP naar de gewenste locatie uitrollen.

# LET OP
Vergeet natuurlijk niet de FTP url en het pad naar de root folder te wijzigen in het bitbucket.yml bestand.

