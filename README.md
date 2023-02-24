# DATA_TEST
context.properties : fichier de context Talend 
def_env_var : script shell pour définir les variables d'environnement (connexions vault à créer) 
devops.json : fichier crédentials service account datalake pour les connexion BigQuery (laisssé vide e attendant la mise en place de vault) 
mongon_ping : shell pour pinger le serveur mongo de démo 
mongo_test : connexion à mongo via mongosh
run_file : lancement du job Job_test_mongo_0.1
run_poc_env_var : lancement du job Job_poc_var_env_0.1
