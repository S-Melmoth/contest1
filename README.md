# Kaggle classification competition -- Animal Shelter 
The task is to predict the fate of each animal described in the test set and to try to find out what are the most important features or features combinations possibly leading to each of the outcomes.

Using any data other than those provided for the competition is prohibited.

Using pre-trained models or code solving a similar task is not allowed as well.


Интересные нам колонки:

ID -- уникальный идентификатор животного, назначенный при поступлении  
Name -- кличка  
DateTime -- кажется, дата поступления  
AnimalType -- собака или кошка  
SexuponOutcome -- пол животного, с некоторыми особенностями  
AgeuponOutcome -- возраст в момент отчисления из приюта  
Breed -- что-то вроде породы  
Color -- окрас?  

Предсказать надо Outcome: Adoption, Died, Euthanasia, Return to owner, and Transfer. Думаю, тут всё понятно.  
Соответствующие номера классов: {"Adoption" : 0, "Transfer": 1, "Return_to_owner": 2, "Euthanasia": 3, "Died": 4}  
