- sudo ansible-playbook -e @/home/nlv/WORK/secrets.yml --ask-vault-pass file.yml

- set_hostname
- nginx
- install_certbot
- nginx_rssbridge
- obtain_certificates



- nginx_options_ssl







- make_zone_templates
- внести записи DNS вручную
- пользователя не создаем (admin_user.yml)- уже создан - потом разбиремся с этим
- пока не запрещаем заход по ssh root (better_sshd.yml)
- опции sshd наверное нужны будут 
- obtain_certificates
- nginx




- почему admin_email в секретах?
- obtain_certificates пришлось останавливать nginx - он уже был там. почему? 
- надо тогда в сценариях учесть и отдельно отключать или требовать чтобы не было его


- nginx_discourse honstname
- nginx_discourse там же и для mock
