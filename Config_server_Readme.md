# Config Server
[GitHub](https://github.com/hamitmizrak/offline_microservis_2_config_server)
---

## Config Server
- Mikroservislerin konfigürasyonlarını merkezi bir yerde yönetmek için kullanıdğımız yapıdır.
- Bu config-server yapısı: Merkezi bir alan içinde Config Server üzerinden yapılandırmaları dinamik olarak alabilir.

# Spring Cloud(Config Client)
- Spring Cloud Serverdan konfigürasyonları almak için kullanılan istemcidir.
- Mikroservisler genellikle Config Client olarak yapılandırılır.
- Config Client Config Server'a bağlanır ve merkezi oalrak yönetilen konfigürsayon dosylarını alır
- Eğer uygulamamız merkezi olarak yönetilen konfigürasyonları almak için Spring Cloud Config server'a bağlancaksa biz Config Client ekliyoruz.


# Spring Cloud(Config Server)
- Merkerzi bir konfigürasyon yönetim sunuculuğunu yapar.
- Bir veya daha fazla mikroservislerin konfigürasyon dosyalarını merkezi bir yerde sunar.