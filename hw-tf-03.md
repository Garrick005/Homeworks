# Домашнее задание к занятию «Управляющие конструкции в коде Terraform»

### Задание 1
<img width="576" height="334" alt="task1" src="https://github.com/user-attachments/assets/ed781283-a7e8-40ea-b99f-aae827658e12" />





### Задание 7
{  network_id = local.vpc.network_id,  subnet_ids = concat(slice(local.vpc.subnet_ids, 0, 2), slice(local.vpc.subnet_ids, 3, length(local.vpc.subnet_ids))),  subnet_zones = concat(slice(local.vpc.subnet_zones, 0, 2), slice(local.vpc.subnet_zones, 3, length(local.vpc.subnet_zones)))}

### Задание 8
В строке внутри цикла не хватает закрывающей фигурной скобки } для выражения ${i["network_interface"][0]["nat_ip_address"], плюс есть лишний пробел в ключе "platform_id "

### Задание 9
1. [for i in range(0,99,1) : format("rc-%02d", i)]
2. [for i in range(0,99,1) : format("rc-%02d", i) if contains([0,7,8,9], i % 10) ? i == 19 : true]
