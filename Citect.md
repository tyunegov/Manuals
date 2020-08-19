## 1. Citect.ini

   -[BlockExec](#BlockExec)

   -[Language](#Language)

## 2. Видео

  -[Excel с помощью ODBC/DSN](#Excel)

## 3. Авторизация
-[Настройка авторизации Windows Group](#WinAuth)
-[Настройка окна входа пользователя](#PageLogin)

------

# Citect.ini

## Language<a name="BlockExec"></a>	BlockExec

  По умолчанию установленно - 1.

  - 0 - Запуск Exec разрешен для пользователей или групп с разрешением Allow Exec, установленным на TRUE.

  - 1 - Запуск Exec запрещен.

## <a name="Language"></a>	Language
### LocalLanguage
  - 0 - Russian(Russia)
### LocalLanguageOnly
   - 0 - language drop-down list displays 

   - 1 - language drop-down list does not display

     ------

     

# Видео

## <a name="Excel"></a> Excel с помощью ODBC/DSN

https://www.youtube.com/watch?v=j8W5O7N1SFo

------

# Авторизация

 ## <a name="WinAuth"></a>Настройка авторизации Windows group
- Необходимо сопоставить  группу Windows с группой в Vijeo Citect (Citect Project Editor->System->Roles) и зайти  в Vijeo Citect под любой учетной записью Windows пользователя принадлежадего связанной Windows группе

------

## <a name="PageLogin"></a>Настройка окна входа пользователя
- Настройка выпадающего списка окна входа происходит в функции _SxwLogin_DspDefaultMenu проекта Sxw_Style_Include