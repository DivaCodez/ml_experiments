# PARTIE 1.
### Connecter avec base de donnée: 
```
    conn = sqlite3.connect(":memory:") #Ouvre le tunnel vers la base de données. (OPEN)
    cursor = conn.cursor() #Le robot/intermédiaire qui exécute le travail.
```

### Manipuler data (CREATE/UPDATE/INSERT INTO/SELECT)
```
    cursor.execute() #L'action d'envoyer un ordre SQL.
    cursor.executemany() en Python permet d'exécuter une seule commande SQL plusieurs fois 
    conn.commit() #L'action de sauvegarder pour de bon les ordres exécutés par le curseur.(SAVE)
```

### Requests Manipultation
Execute a SQL *query(request)* and return the result as a pandas DataFrame. ```pd.read_sql_query(sql, conn)```  

  > Lire la request (SELECT) --> Repondre avec du data --> Returner la reponse en dataframe type

