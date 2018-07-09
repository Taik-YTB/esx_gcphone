# esx_gcphone
[FR] GcPhone en ESX avec appelle et VDK_CALL !! Vous mettez ceci dans vos tenue de vos jobs ESX comme exemple (Vous mettez sa quand vous avez la jobs dans les appelles urgences du gcphone) : "(Important de le mettre dans la tenue civil) TriggerServerEvent("player:serviceOff", "police")" ET "(Dans vos tenue de service) TriggerServerEvent("player:serviceOn", "police"). Vous pouvez aussi en rajoutez ou en modifier les jobs qui sont dans le gcphone en allant dans le config.json et dans main.lua, tout en bas du main.lua, il y aura, exemple : Vous avez appellé la Police

 **IMPORTANT**

 "INSERT INTO items VALUES ('109', 'phone', 'telephone', '-1', '0', '1');"

 "INSERT INTO shops (id, name, item, price) VALUES 
 (98, 'TwentyFourSeven', 'phone', 175), 
 (99, 'RobsLiquor', 'phone', 175), 
 (100,   'LTDgasoline', 'phone', 175);"

**Installation**
 1- Mettez votre vdk_call et gcphone dans le dossier ressource
 2- Dans votre server.cfg, vous mettez :
 start vdk_call
 start gcphone
 3- Mettez votre sql et la requête sql
 4- Enjoy!
 
 **Screenshot**
https://cdn.discordapp.com/attachments/398255059063930882/460122149659738113/chat.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121588612988928/urgence.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121550004289558/supprime.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121521982144522/phone.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121472342687785/parametre.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121429871165440/home.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121399143563280/historique.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121340700000296/bank.PNG https://cdn.discordapp.com/attachments/398255059063930882/460121315450290178/appel.PNG

Je remercie fortement Ganon pour le partage du nouveau Gcphone et grâce à mon ancien gcphone j'ai réussi à le transférer en ESX facilement!
