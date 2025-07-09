# Gerador de Casos para o SimSEP ⚡

Este repositório contém os simuladores desenvolvidos para resolver o fluxo de potência com controle de tensão por injeção de potência reativa em barras PV dos sistemas IEEE (9, 14, 30 e 118 barras). O objetivo principal é auxiliar os módulos do SimSEP e gerar casos representativos dos limites operativos dos sistemas elétricos, possibilitando análise de estabilidade de tensão e construção de curvas PV.

Este projeto foi documentado e descrito no Trabalho de Conclusão de Curso "Gerador de Casos para o SimSEP" – Universidade Federal Fluminense, 2025. Consulte o arquivo tcc.docx para mais detalhes teóricos, modelos matemáticos e exemplos gráficos.

## 🔧 Requisitos

Antes de executar os scripts `.py` ou o executável `.exe`, certifique-se de que as seguintes bibliotecas estejam instaladas (em caso de uso via Python):

```bash
pip install numpy scipy matplotlib pandas
```
## 📂 Estrutura dos Executáveis
Usando o executável .exe: Execute diretamente os arquivos.
```bash
GoSimul.exe (Tela 1 – Simulador com visualização de fluxo)
GoCases.exe (Tela 2 – Geração de casos com limites)
GoCurvs.exe (Tela 3 – Geração de curvas PV com controle reativo)
Os arquivos .exe já estão prontos para uso, sem necessidade de instalação de bibliotecas.
```

## 📂 Estrutura dos Gráficos e Arquivos Salvos
```bash
plot/GenOfSimul: arquivos CSV com estruturas para os casos críticos.
plot/GenOfCases: arquivos TXT e logs dos casos.
plot/GenOfCurvs: arquivos de curvas PV.
plot/cdfsGerados/G_TELA2: CDFs gerados.
*.cdf: arquivos de entrada padrão IEEE.
```


## 👨‍💻 Autor
Emanoel Gecildo Albuquerque Garcia – www.linkedin.com/in/emanoel-gecildo-albuquerque-garcia-004b9013a

