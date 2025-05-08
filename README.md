# **DESAFIO SUPER TRUNFO - PAÍSES - CADASTRO DAS CARTAS**

Bem-vindo ao desafio "**Super Trunfo - Países**"! No jogo Super Trunfo, os jogadores comparam os atributos das cartas para determinar a mais forte. O tema deste Super Trunfo é "**Países**", onde você comparará os atributos das cidades.

A empresa MateCheck contratou você para desenvolver a parte inicial do jogo, que consiste no cadastro das cartas.

O desafio está dividido em **três níveis**: **Novato**, **Aventureiro** e **Mestre**, com cada nível adicionando mais complexidade ao anterior.  **Você deve escolher qual desafio quer realizar.**

🚨 **ATENÇÃO:** O nível **Novato** do desafio é focado apenas no cadastro das cartas, utilizando as funções `scanf` para ler os dados e `printf` para exibi-los.

## **🎮 NÍVEL NOVATO: CADASTRO BÁSICO**

No nível **Novato**, você iniciará criando o sistema básico do jogo Super Trunfo com o tema "**Países**". As cartas serão divididas por estados, cada um com quatro cidades.  Imagine um país dividido em oito estados (A a H), e cada estado com quatro cidades (1 a 4).  A combinação forma o código da carta (ex: A01, B02).

🚩 **OBJETIVO:** Criar um programa em C que cadastra **duas** cartas com os seguintes atributos:

* **População** (`int`)
* **Área** (`float`)
* **PIB** (`float`)
* **Número de pontos turísticos** (`int`)

⚙️ **FUNCIONALIDADES DO SISTEMA:**

* O sistema permitirá ao usuário cadastrar os dados de **duas** cartas manualmente via terminal.
* Após o cadastro, o sistema exibirá os dados de cada cidade de forma organizada.

📥 **ENTRADA** e 📤 **SAÍDA DE DADOS:**

* O usuário insere os dados de cada carta interativamente via `scanf`.
* O programa exibe os dados cadastrados usando `printf`, com cada atributo em uma nova linha.

**SIMPLIFICAÇÕES PARA O NÍVEL NOVATO:**

* Cadastre apenas **duas** cartas.
* Concentre-se na leitura, armazenamento e exibição. Não implemente comparações ou outros recursos.
* **Não use** laços (`for`, `while`) ou condicionais (`if`, `else`).


## **🛡️ NÍVEL AVENTUREIRO: CÁLCULO DE ATRIBUTOS**

No nível **Aventureiro**, você expandirá o sistema para incluir o cálculo de dois novos atributos: **Densidade Populacional** e **PIB per Capita**.

🆕 **DIFERENÇA EM RELAÇÃO AO NÍVEL NOVATO:**

* **NOVOS ATRIBUTOS:**
    * **Densidade Populacional**: População / Área (`float`)
    * **PIB per Capita**: PIB / População (`float`)

⚙️ **FUNCIONALIDADES DO SISTEMA:**

* O sistema calculará automaticamente a **Densidade Populacional** e o **PIB per Capita**.
* Os novos atributos serão exibidos junto com os demais.

📥 **ENTRADA** e 📤 **SAÍDA DE DADOS:**

* Mesma entrada do nível **Novato**.
* A saída exibirá também os atributos calculados.

**SIMPLIFICAÇÕES PARA O NÍVEL INTERMEDIÁRIO:**

* Continue cadastrando apenas **duas** cartas.
* Continue **sem usar** laços (`for`, `while`) ou condicionais (`if`, `else`).



## **🏆 NÍVEL MESTRE: COMPARAÇÃO E SUPER PODER**

No nível **Mestre**, você implementará a comparação entre duas cartas e o cálculo do "**Super Poder**".

🆕 **DIFERENÇA EM RELAÇÃO AO NÍVEL AVENTUREIRO:**

* **COMPARAÇÃO DE CARTAS:** O usuário poderá comparar as duas cartas.
* **SUPER PODER:** Soma de todos os atributos (inclusive os calculados), com a densidade populacional *invertida* antes da soma (1/densidade). Tipo: `float`.

⚙️ **FUNCIONALIDADES DO SISTEMA:**

* Comparação atributo a atributo, mostrando qual carta venceu (1 se a Carta 1 vence, 0 se a Carta 2 vence).
* Para **Densidade Populacional**, vence a carta com o *menor* valor.
* Para os demais atributos (e o **Super Poder**), vence a carta com o *maior* valor.

📥 **ENTRADA** e 📤 **SAÍDA DE DADOS:**

* Mesma entrada dos níveis anteriores, mas a **População** agora é `unsigned long int`.
* A saída mostrará o resultado da comparação para cada atributo e o **Super Poder**.

**OBSERVAÇÃO:** Preste atenção à conversão de tipos ao calcular o **Super Poder**!


## **🏁 CONCLUSÃO**

Ao concluir qualquer um dos níveis, você terá dado um passo importante no desenvolvimento do **Super Trunfo - Países**. Boa sorte e divirta-se programando!
