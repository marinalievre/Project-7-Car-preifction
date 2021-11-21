# Project-7-Car-preifction

В ходе выполнения проектной работой применены следующие методы:
transfer learning и fine-tuning 
настройка LR
настройка параметров регуляризации полносвязного слоя нейронной сети
применен способ заполнения пропусков c помощью ImageDataAugmentor с использованием библиотеки аугментации изображений albumentations
подобраны переменные (размер картинки, батч, количество эпох)
добавлена батч-нормализация в архитектуре “головы” модели
Использована архитектура сетей - Xception, InceptionV3, EfficientNetB5

Итоги:

Fine-tuning Xception         
0% разморозки acc = 59.25%      
50% разморозки acc = 91.88%        
75% разморозки acc = 93.99%        
100% разморозки acc = 93.99%       
увеличение размера картинки acc 96.82%         
          
Fine-tuning InceptionV3     
0% разморозки acc = 61.31%      
50% разморозки acc = 90.55%        
75% разморозки acc = 93.86%        
100% разморозки acc = 93.69%       
увеличение размера картинки acc = 94.68%               

Fine-tuning **EfficientNetB5**       
0% разморозки acc = 73,55%      
50% разморозки acc = 93.69%        
75% разморозки acc = 94.72%        
100% разморозки acc = 95.02%       
увеличение размера картинки acc = 97.25%         
