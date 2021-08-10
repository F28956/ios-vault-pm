docker run --rm  -p 8200:8200  --cap-add=IPC_LOCK -d --name=dev-vault  -e VAULT_DEV_ROOT_TOKEN_ID=myroot  vault:1.8.1
