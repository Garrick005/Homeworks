# Домашнее задание к занятию «Основы Terraform. Yandex Cloud»

### Задание 1

4. Допущены синтаксическая ошибка в строке platform_id standart вместо standard. Минимальные параметры ВМ - 2 ядра, 1 Gb RAM, standard-v2. Preemptible = true и core_fraction=5 в параметрах ВМ позволяют экономит ресурсы.
<img width="319" height="33" alt="task1-5" src="https://github.com/user-attachments/assets/af7e700e-e907-4dab-a777-323e8b8f9480" />
<img width="418" height="142" alt="task1-5-1" src="https://github.com/user-attachments/assets/003628c3-2519-4abe-8720-d57b31d4c533" />

### Задание 4
<img width="398" height="173" alt="task4" src="https://github.com/user-attachments/assets/9f180292-192b-4f36-be1a-5beb5dba1d6e" />

### Задание 7
1. local.test_list[1] - в HCL индексация начинается с нуля.
2. length(local.test_list)
3. local.test_map["admin"] или local.test_map.admin
4. "${local.test_map.admin} is ${keys(local.test_map)[0]} for ${local.test_list[2]} server based on OS ${local.servers.production.image} with ${local.servers.production.cpu} v${keys(local.servers.develop)[0]}, ${local.servers.production.ram} ${keys(local.servers.stage)[3]} and ${length(local.servers.production.disks)} virtual ${keys(local.servers.stage)[1]}"
<img width="762" height="152" alt="task7" src="https://github.com/user-attachments/assets/d0775f75-462d-479e-8afe-1b3f4c8e2e89" />

### Задание 8
<img width="403" height="291" alt="task8" src="https://github.com/user-attachments/assets/4ea76e79-0bac-439d-a39b-edd1ffbb5b19" />
