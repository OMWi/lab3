# ConfigModel
Содержит все настройки необходимые для работы службы
# EncryptionOptions
Содержит настройки шифрования
# ConfigProvider
Содержит интерфейс IParsable с методом GetConfig и ConfigProvider который вызывает парсеры xml или json реализующие интерфейс IParsable.
ParserJson использует JsonSerializer; ParserXml ищет рекурсивно в xml файле поля класса, для которого вызываается GetConfig 
# Service1
Сама служба
# FileManager
Библиотека содержащая функции для службы
# Config
Содержит настройки службы в json и xml формате, xsd схему для валидации xml файла

# Изменения по сравнению со второй лабой
Теперь служба получает настройки с помощью ConfigProvider, проводится валидация xml файла при запуске
