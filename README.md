# Criando usuário no Centos com permissão de sudo utilizando Ansible

## Passos:

Alterar os IPs/hostname dos servidores alvos no arquivo hosts

Executar o playbook:

```bash
ansible-playbook -i hosts --ask-pass criarUsuario.yml
```

Nesse exemplo utilizei o --ask-pass pois realizei o acesso utilizando senha. Se no ambiente tiver conexão aos servidores via chave públicas/privadas, não precisa passar esse parâmetro.

## License
[MIT](https://choosealicense.com/licenses/mit/)
