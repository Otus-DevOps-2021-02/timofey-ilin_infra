# timofey-ilin_infra
timofey-ilin Infra repository

# для подключения используется команда
ssh -i ~/.ssh/id_ed25519 -A appuser@178.154.206.183 ssh 10.130.0.31

# для создания алиаса
alias someinternalhost='ssh -i ~/.ssh/id_ed25519 -A appuser@178.154.206.183 ssh 10.130.0.31'

bastion_IP = 178.154.206.183
someinternalhost_IP = 10.130.0.31