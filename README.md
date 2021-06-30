# Создание токена
1. Подтвердите свой адрес электронной почты , если он еще не подтвержден.

1. В правом верхнем углу любой страницы щелкните фотографию своего профиля, затем нажмите **Settings** (Настройки). 

    <img src="userbar-account-settings.png" width="250" alt="Значок настроек на панели пользователя">

1. На левой боковой панели нажмите **Developer settings** (Настройки разработчика). ![Настройки разработчика](developer-settings.png)


1. На левой боковой панели щелкните **Personal access tokens** (Личные токены доступа).
![Токены личного доступа](personal_access_tokens_tab.png)


1. Щелкните **Generate new token** (Создать новый токен).
![Кнопка создания нового токена](generate_new_token.png)


1. Дайте вашему токену описательное имя (любое, удобное Вам).
![Поле описания токена](token_description.png)


1. Выберите области или разрешения, которые вы хотите предоставить этому токену. Чтобы использовать свой токен для доступа к репозиториям из командной строки, выберите **repo**.
![Выбор областей действия токенов](token_scopes.gif)


1. Щелкните **Generate token** (Создать токен).
![Кнопка создания токена](generate_token.png)


1. Щелкните кнопку ![Недавно созданный токен](personal_access_tokens.png), чтобы скопировать токен в буфер обмена. По соображениям безопасности после того, как вы покинете страницу, вы больше не сможете увидеть токен. Сохраните его в удобном/надёжном месте, чтобы не потерять.
![Недавно созданный токен](personal_access_tokens1.png)


1. В дальнейшем, при запросе учетных данных (логина и пароля), вместо пароля указывайте этот токен.

`Предупреждение: относитесь к своим токенам как к паролям и держите их в секрете. При работе с API используйте токены в качестве переменных среды вместо того, чтобы жестко кодировать их в своих программах.`

<a href="https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token">Оригинал</a>