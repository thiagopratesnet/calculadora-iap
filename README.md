# Calculadora IAP — Java e Algoritmos

Calculadora acadêmica para acompanhamento de notas da disciplina **Introdução a Algoritmos e Programação — IAP**, com foco em **Java, lógica de programação e algoritmos**.

## Objetivo

O projeto calcula a pontuação total da disciplina com base em fóruns, laboratórios, listas de exercícios e avaliações presenciais.

A disciplina possui **500 pontos** no total:

- **240 pontos** em atividades.
- **260 pontos** em avaliações presenciais.
- **350 pontos** necessários para aprovação, equivalente à média **7,0**.

## Correção aplicada

A avaliação presencial agora é lançada separadamente, conforme aparece no Moodle:

- Avaliação Presencial I Unidade: até **60 pontos**.
- Avaliação Presencial II Unidade: até **100 pontos**.
- Avaliação Presencial III Unidade: até **100 pontos**.

Também existe um simulador opcional para converter uma nota de prova de **0 a 16** pela regra proporcional:

```text
AP1 = (nota / 16) × 60
AP2 = (nota / 16) × 100
AP3 = (nota / 16) × 100
```

Exemplo:

```text
Nota da prova: 10

AP1 = 37,50
AP2 = 62,50
AP3 = 62,50

Total presencial = 162,50
```

## Funcionalidades

- Lançamento de notas por atividade.
- Lançamento separado de AP1, AP2 e AP3.
- Simulador proporcional da nota 0 a 16.
- Cálculo automático do total geral.
- Cálculo de percentual por etapa.
- Situação final: aprovado ou pendente.
- Impressão do resultado.
- Exportação para PDF.
- Envio por e-mail via `mailto`.
- Compartilhamento por WhatsApp.
- Armazenamento local das notas no navegador.
- Interface responsiva estilo dashboard.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- JavaScript
- html2pdf.js
- Git
- GitHub Pages
- GitHub Actions
- PowerShell

## Publicação

Site publicado via GitHub Pages:

https://thiagopratesnet.github.io/calculadora-iap/

## Autor

**Thiago Ferreira Prates Neves**  
Aluno da **UESB — Universidade Estadual do Sudoeste da Bahia**  
Curso: **ADS — Análise e Desenvolvimento de Sistemas**  
E-mail: **thiagopratesnet@gmail.com**  
Site: **https://thiagoprates.com.br**

## Licença

Projeto acadêmico desenvolvido para fins de estudo e portfólio.
