# Gerador de Senhas Aleatórias

Este é um gerador de senhas aleatórias implementado em JavaScript para criar senhas seguras e personalizáveis. O código é destinado a ser utilizado em páginas da web e oferece as seguintes funcionalidades:

### Elementos Selecionados

- **Botão de Geração de Senha:** Identificado como `#generate-password`, este botão inicia o processo de geração de senhas.
- **Elemento de Senha Gerada:** Identificado como `#generated-password`, exibe a senha gerada para o usuário.

### Configuração da Geração de Senha

- **Botão "Clique Aqui" para Abrir/Fechando o Gerador:** Identificado como `#open-generate-password`, este botão permite abrir e fechar as opções de geração de senha.
- **Contêiner de Opções de Geração:** Identificado como `#generate-options`, contém opções para configurar a geração de senha, incluindo comprimento, uso de letras, números e símbolos.
- **Entrada de Comprimento da Senha:** Identificado como `#length`, permite ao usuário especificar o comprimento desejado da senha.
- **Opções de Seleção de Caracteres:** Identificadas como `#letters`, `#numbers` e `#symbols`, permitem ao usuário escolher quais tipos de caracteres incluir na senha.

### Funções de Geração

- **Funções de Geração de Caracteres:** `getLetterLowerCase`, `getLetterUpperCase`, `getNumber`, e `getSymbol` geram caracteres aleatórios do alfabeto, números e símbolos.
- **Função de Geração de Senha Principal:** `generatePassword` usa as funções de geração de caracteres selecionadas pelo usuário para criar senhas aleatórias personalizadas.

### Eventos

- **Evento de Clique no Botão de Geração de Senha:** Disparado quando o botão `#generate-password` é clicado, inicia o processo de geração de senha.
- **Evento de Clique no Botão "Clique Aqui":** Alterna a visibilidade das opções de geração quando o botão `#open-generate-password` é clicado.
- **Evento de Clique no Botão de Copiar Senha:** Copia a senha gerada para a área de transferência quando o botão `#copy-password` é clicado.

Este gerador de senhas fornece uma solução fácil e personalizável para criar senhas seguras, adaptadas às necessidades específicas do usuário.

### Imagens
![telainicial](https://github.com/KalineAzevedo/projeto-gerador-de-senha/assets/137228416/bc4b0fdf-1228-4fa7-ad9b-f3b760453242)
![telasenha](https://github.com/KalineAzevedo/projeto-gerador-de-senha/assets/137228416/fdf33b33-7668-4c5d-a17f-a7733615f6c1)




