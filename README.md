# esx_gcphone
[FR] GcPhone en ESX avec appelle et VDK_CALL !! Vous êtes obligé de mettre ces prises de service dans vos tenues de tout les jobs qui seront dans votre gcphone!! : "(Important de le mettre dans la tenue civil) TriggerServerEvent("player:serviceOff", "NOMDEVOTREJOB")" ET "(Dans vos tenue de service) TriggerServerEvent("player:serviceOn", "NOMDEVOTREJOB"). Vous pouvez aussi rajoutez ou modifier des appelles dans votre gcphone en allant dans : gcphone/html/static/config/config.json et ne pas oubliez d'allez dans : gcphone/client/client.lua et ligne 518. Dans le vdk_call, si vous rajoutez une appelle dans le gcphone, vous devrez aller dans : vdk_call/call.lua et ligne 62 et aussi vdk_call/call_server.lua et ligne 6 à 37.

 **IMPORTANT** :

 "INSERT INTO items VALUES ('109', 'phone', 'telephone', '-1', '0', '1');"

 "INSERT INTO shops (id, name, item, price) VALUES 
 (98, 'TwentyFourSeven', 'phone', 175), 
 (99, 'RobsLiquor', 'phone', 175), 
 (100,   'LTDgasoline', 'phone', 175);"

**Installation** :

 1- Mettez votre vdk_call et gcphone dans le dossier ressource
 2- Dans votre server.cfg, vous mettez :
 start vdk_call
 start gcphone
 3- Mettez votre sql et la requête sql
 4- Enjoy!
 
 **Screenshot** :
 
https://cdn.discordapp.com/attachments/398255059063930882/460122149659738113/chat.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121588612988928/urgence.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121550004289558/supprime.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121521982144522/phone.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121472342687785/parametre.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121429871165440/home.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121399143563280/historique.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121340700000296/bank.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121315450290178/appel.PNG

Je remercie fortement Gannon pour le partage du nouveau Gcphone et grâce à mon ancien gcphone j'ai réussi à le transférer en ESX facilement!
