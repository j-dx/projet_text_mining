# projet_text_mining

Notre bot permet de communiquer avec un agent conversationnel sur le sujet des voyages. Nous avons en effet scrappé les FAQ des sites Tui et Exotismes, dont les liens sont : https://www.tui.fr/faq/ et https://www.exotismes.fr/voyages/t/FAQ.html réspectivement. Ces sites proposent des voyages comprenant des vols et des hôtels.

Afin de commencer à échanger avec le bot, il faut télécharger l’ensemble du dossier Github “projet_text_mining”. Le sous répertoire “aide_creation” n’est pas indispensable au bon fonctionnement, il montre les démarches que nous avons suivies pour mettre en place le bot. 

Le bot débute en lançant le fichier python “code_final” . Il sera peut-être nécessaire de télécharger le modèle spacy “fr_core_news_sm” à l’aide de la commande “!python -m spacy download fr_core_news_sm”.

Après réception de la demande, le bot prétraite la question et détermine si elle appartient ou non à la thématique du voyage. Si la demande n’est pas en lien avec le thème, il génère une réponse aléatoire originale. Sinon, il effectue un nouveau prétraitement sur la question initiale et cherche la question ou la réponse la plus similaire à la demande et renvoie la réponse adaptée. 
