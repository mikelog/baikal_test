# baikal_test
##Установка OpenVPN клиента на ubuntu xenial

openvpn_client_etc_dir - путь до каталога конфигурационных файлов и файлов сертификатов  openvpn client
openvpn_client_protocol - используемый протокол
openvpn_client_server_host - адрес  VPN сервера
openvpn_client_server_port - порт подключения VPN сервера

Ключи и сертификаты должны быть упакованы в архив tar.gz в формате Host_Name.tar.gz В директорию /roles/openvpn_client/files/, где Host_Name идентично тому, что описано в инвентори inventories\prod\vpn_clients.yml


