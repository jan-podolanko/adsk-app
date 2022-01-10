# instalacja
1. "eval \`ssh-agent\`" w terminalu
2. "ssh ec2-user@<ip_maszyny> -i id_student" dla obu adresow ip
3. "ssh-add id_student"
4. "ansible-playbook -i hosts.ini scrapper.yaml -e DB_PW='hasło'" wlaczenie samej aplikacji
5. i działa :)

![]screenek.png()
