# baikal_test
## Установка OpenVPN клиента на ubuntu xenial

openvpn_client_ca_crt_file_name:   - Имя файла корневого сертификата

openvpn_client_client_crt_file_name:  - Имя файла сертифаката клиента

openvpn_client_client_key_file_name:  - Имя файла ключа клиента

openvpn_client_etc_dir: /etc/openvpn - путь до каталога конфигурационных файлов и файлов сертификатов  openvpn client на удаленной машине

openvpn_client_pers_keys:  - true|false Используется общий ключ или персональный, в случае использования персональных ключей файлы 

openvpn_client_client_crt_file_name и openvpn_client_client_crt_file_name должны быть проиндексированы, например client.crt1, client.key1 в том количестве, сколько будет клиентов. В случае использования общего ключа за основу будет взят параметр 

openvpn_client_client_crt_file_name  и openvpn_client_client_crt_file_name без индекса.

openvpn_client_protocol:  - протокол openvpn клиента

openvpn_client_server_host:  - ip адрес сервера для подключения клиента

openvpn_client_server_port: - порт для подключения клиента

openvpn_client_ta_file_name: -  ключ сервера

Клиентские сертификаты размещаются в каталоге роли ./files/clients

Серверные ключи и корневые сертификаты в каталоге роли ./files




