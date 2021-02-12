# В папке проекта, в консоли:
git init
# добавляем пару файлов, потом: 
git add .
git commit -m 'initial commit'

# Далее, создаем ключ
ssh-keygen
# Идем в папку /твойПользователь/.ssh 
# Копируем содержимое /твойПользователь/.ssh/id_rsa.pub 

# Идем на github.com, регистрируемся под вашим акком @inueco.ru
# Добавляем ключ ssh в настройках > ssh ключи > новый
# Создаем новый репозиторий 
https://github.com/new

# Снова в консоли с папкой проекта следуем инструкциям
# "…or push an existing repository from the command line"
git remote add origin ваш-адрес-репозитория
git branch -M main
git push -u origin main