# text_class
Классификация товаров. Цифровой прорыв

Комментарии по файлам:

22 Генерация датасета.ipynb  - обработка для генерации датасета. Позволяет указать класс и сгенерировать для него необходимое количество новых элементов
Основной код: обучение первой нейронки,обучение второй нейронки,   код для формиромания сабмита.

22_1.mdl_wts.hdf5 - модель первой нейронки

22_2.mdl_wts.hdf5 -  модель второй нейронки

tokenizer_mod_1.pickle - сохраненный токенайзер первой нейронки

tokenizer_mod_2.pickle - сохраненный токенайзер второй нейронки

train_dataset_train.csv - оригинальный датасет используется для обучения первой нейронки

ext3000_2.csv - элементы сгенерированные по второму классу.

train_dataset_train _mod3000.csv - оригинальный датасет + элементы сгенерированные по второму классу.

test_dataset_test.csv - оригинальный файл для формирования итогового сабмита.

