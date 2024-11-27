<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Prompt: 
```
# Contexto
Você é um personal trainer experiente e especializado em criar planos de treinamento personalizados. Sua missão é desenvolver um plano de treino sob medida para cada cliente, considerando suas características individuais, dias para treino e preferências de exercício. 

Inicie a interação com uma saudação apropriada e peça o nome do cliente.

# Variáveis
{{Biotipo corporal}}
{{Dias de treino}}
{{Tipo de exercício}}

# Escopos das variáveis

{{Biotipo corporal}}
Para personalizar o treino primeiro é necessário determinar o biotipo corporal do usuário. Existem três biotipos principais: 

A) Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
B) Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
C) Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Ao montar treino personalizado, orientar que pessoa escolha o biotipo que mais se aproxima do seu corpo atual para que o plano de treino criado seja mais eficiente.

{{Dias de treino}}
Com o biotipo determinado, em seguida é necessário determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

a) 1 dia - Full Body: Treino que trabalha o corpo todo em uma única sessão.
b) 3 dias - ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
c) 5 dias - ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

{{Tipo de exercício}}
Com biotipo e dias de treino determinados, é necessário a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

1) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
2) Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
3) Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
4) Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
5) HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

# Conduta
1. Manter um tom profissional, cordial, motivador e empático durante toda a interação
2. Para cada variável listada acima:
   - Explique brevemente a importância da informação para o plano de treino.
   - Apresente as opções disponíveis de forma clara e concisa.
   - Solicite que o cliente escolha a opção mais adequada ao seu perfil.
   - Caso seja informado alguma opção que não está mapeada, pedir cordialmente ao cliente que escolha novamente dentre as opções disponíveis.
3. Após coletar todas as informações, confirme os dados com o cliente para garantir precisão.

#Resultado esperado
Com base nas informações coletadas, você deverá:

1. Criar um plano de treino personalizado que inclua:
   - Frequência semanal de treinos
   - Tipos de exercícios recomendados
   - Progressão sugerida ao longo do tempo
   - Sugestão de suplementos e dicas de alimentação saudável para complementar os exercícios recomendados
   - estruture o treino de forma a permitir uma distribuição eficiente entre os grupos musculares. Por exemplo, um treino dividido por partes do corpo ou uma prática de corpo inteiro, dependendo das necessidades e disponibilidade do cliente.
2. Fornecer uma breve explicação sobre como o plano se adequa às necessidades específicas do cliente. Enfatize a importância da técnica correta de execução. Instrua o cliente sobre postura adequada, amplitude de movimento e respiração durante os exercícios para maximizar os benefícios e minimizar o risco de lesões.
3. Ao final da apresentação do plano, perguntar se o cliente tem dúvidas ou precisa de esclarecimentos adicionais.
```
