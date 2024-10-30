# Gerador de Senhas Seguras

Este projeto é um gerador de senhas seguras desenvolvido com HTML, CSS e JavaScript. Ele permite que o usuário crie senhas fortes personalizadas com diferentes critérios de segurança, como comprimento, uso de letras maiúsculas, minúsculas, números e símbolos.

## Funcionalidades

- Defina o comprimento da senha (entre 4 e 20 caracteres).
- Opções para incluir letras maiúsculas, letras minúsculas, números e símbolos.
- Gera uma senha aleatória baseada nas preferências do usuário.
- Copie a senha gerada para a área de transferência com um clique.

## Importante

Atualizar a dependência `chromedriver` in `package.json` com sua versão do Chrome. O projeto é configurado com o Chrome 85..

## Demonstração

*Como Usar*

1. Escolha o comprimento desejado da senha.
2. Selecione os tipos de caracteres que deseja incluir (letras maiúsculas, minúsculas, números e/ou símbolos).
3. Clique em Gerar Senha para criar uma senha segura.
4. Clique em Copiar para salvar a senha na área de transferência.

## Exemplo de Código

*HTML (Estrutura)*

<label>
    Comprimento da senha:
    <input type="number" id="length" min="4" max="20" value="12">
</label>

*JavaScript (Lógica para gerar senha)*

function generatePassword() {
    const length = document.getElementById("length").value;
    let password = "";
    // Lógica para gerar senha segura...
    return password;
}

*Como Executar o Projeto*

git clone https://github.com/jean2001369/gerador_de_senhas_seguras.git

## Tecnologias Utilizadas

1. *HTML* - Estrutura da interface.
2. *CSS* - Estilos para a aplicação.
3. *JavaScript* - Lógica para gerar e copiar a senha.

## Recursos Futuros

1. Opção para mostrar a força da senha.
2. Salvamento de senhas em uma lista segura.


### Licença

Distribuído sob licença MIT
