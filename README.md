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
