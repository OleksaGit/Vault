# Vault
Docker compose file for starting vault in non dev mode

docker exec -it vault vault operator init

get simply token
vault token create -policy="<name_policy.hcl>" -orphan

