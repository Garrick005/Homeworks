# Домашнее задание к занятию «Введение в Terraform»

### Чек-лист готовности к домашнему заданию
<img width="287" height="53" alt="check-1" src="https://github.com/user-attachments/assets/263bf9df-b1b4-47ea-bf32-300b833df681" />

### Задание 1
2. Личную и секретную информацию допустимо хранить в файле personal.auto.tfvars. Это оптимальный подход для локального хранения секретов, которые не должны попадать в общий репозиторий.
3. "result": "VdyRdmy6uXfojo9u"
4. В блоке ресурса Terraform обязательно нужно указать тип ресурса и имя ресурса (2 лейбла). Имя ресурса не может начинаться с цифры. random_string_FAKE - ошибка в лейбле ресурса. resulT - опечатка в аргументе. В имени контейнера будет отображаться созданный пароль. (это небезопасно, но на правильность кода это не влияет).


5.
<img width="422" height="343" alt="task1" src="https://github.com/user-attachments/assets/db5f0235-9cbf-4c53-a6cd-be38a6c621f5" />
<img width="710" height="54" alt="task1-1" src="https://github.com/user-attachments/assets/614ed544-c3b4-4a94-8d30-92b1b6d3b667" />

6. Команда terraform apply -auto-approve выполняет автоматическое применение изменений, без запроса подтверждения от пользователя. Её применение может привести к удалению важных ресурсов, если в коде были допущены неточности. Данныя команда может применяться при автоматизации CI/CD когда Terraform запускается из скриптов, пайплайнов, GitHub Actions и пр., в тестовых средах и при отладке кода.

<img width="709" height="52" alt="task1-6" src="https://github.com/user-attachments/assets/a5e75792-9397-470f-8a11-a8e01578327e" />

7.
<img width="483" height="373" alt="task1-7" src="https://github.com/user-attachments/assets/cfaf9a57-7b32-4fee-8ad6-d159199c501a" />

8. Параметр "keep_locally = true" не позволяет удалять Docker‑образ из локального хранилища при выполнении команды terraform destroy. Образ останется в Docker-кэше.

<img width="229" height="72" alt="task1-8-1" src="https://github.com/user-attachments/assets/66fc4810-8b62-4409-8b27-49aa30912257" />

<img width="420" height="70" alt="task1-8-2" src="https://github.com/user-attachments/assets/9430f3c8-0416-4c03-bae9-a65cd6286712" />


### Задание 2*

https://github.com/Garrick005/ter-homeworks/blob/main/01/src/main.tf
