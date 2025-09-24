## Тест-кейс 1: Успешный вход с standard_user  
**Цель**: Проверить успешную авторизацию с валидными учетными данными.  
**Предусловия**: Пользователь находится на странице входа **Swag Labs** с полями для ввода имени пользователя и пароля.  
**Шаги**:  
* Ввести логин: standard_user в поле ввода "Username"  
* Ввести пароль: secret_sauce в поле ввода "Password"  
* Нажать кнопку "Login".  
**Ожидаемый результат**:  
* Пользователь успешно входит.  
* Отображается страница каталога товаров "Swag Labs".  

  selector #user-name  
input class="input_error form_input" placeholder="Username" type="text" data-test="username" id="user-name" name="user-name" autocorrect="off" autocapitalize="none" value=""  
  input class="input_error form_input"  
  placeholder="Username"  
  type="text"  
  data-test="username"  
  id="user-name"  
  name="user-name"  
  autocorrect="off"  
  autocapitalize="none"   
  value="standard_user"  
  
  selector #password  
input class="input_error form_input" placeholder="Password" type="password" data-test="password" id="password" name="password" autocorrect="off" autocapitalize="none" value=""  
  input class="input_error  
  form_input" placeholder="Password"  
  type="password" data-test="password"  
  id="password"  
  name="password"  
  autocorrect="off"  
  autocapitalize="none"  
  value=""  
  
  selector #login-button  
input type="submit" class="submit-button btn_action" data-test="login-button" id="login-button" name="login-button" value="Login"  
  input type="submit"  
  class="submit-button btn_action"  
  data-test="login-button"  
  id="login-button"  
  name="login-button"  
  value="Login"  



  



    
