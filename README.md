# baikal_test
##Установка OpenVPN клиента на ubuntu xenial
openvpn_client_etc_dir: путь до каталога конфигурационных файлов и файлов сертификатов  openvpn client на удаленной машине
openvpn_client_key_arch_base_name:  название архива содержащего ключи и сертификаты клинета. архив должен быть *.tar.gz 
openvpn_client_pers_keys: общий архив клюей на всех клиентов или индивидуальный
openvpn_client_protocol: протокол openvpn клиента
openvpn_client_server_host: ip адрес, на который будет подключаться openvpn клиент
openvpn_client_server_port: порт, на который будет подключаться openvpn клиент

Ключи и сертификаты должны быть упакованы в архив tar.gz в формате openvpn_client_key_arch_base_name[индекс от 1 до максимального ].tar.gz В директорию /roles/openvpn_client/files/, где Host_Name идентично тому, что описано в инвентори inventories\prod\vpn_clients.yml


