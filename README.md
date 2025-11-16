# Lgpd-
# Importe a biblioteca de conformidade
from conformidade import Conformidade

# Creat um objeto de conformidade
conformidade = Conformidade()

# Defina os dados pessoais
dados_pessoais = {
    "nome": "João",
    "sobrenome": "Silva",
    "email": "joao.silva@example.com"
}

# Obtenha o consentimento do titular
consentimento = conformidade.obter_consentimento(dados_pessoais)

# Trate os dados pessoais
conformidade.tratar_dados(dados_pessoais, consentimento)

# Armazene os dados pessoais
conformidade.armazenar_dados(dados_pessoais)
