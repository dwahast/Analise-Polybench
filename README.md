# CIC - Análise dos dados obtidos para apresentação no Congresso de Iniciação Ciêntifica da UFPel (2018 - 2019)

## Analise Polybench em questões de Latência e Potência

### Analise do Benchmark Polybench-GPU na GPU Mali T628. Aplicado a variadas configurações de frequência da GPU (Device).
  - (Analise Latência Mali) Analise de Latência dos Kernels da aplicação executação na Mali T628.
  - (Analise Energia Mali) Analise de Potência relacionada a frequência de Operação da Mali T628.

### Analise do Benchmark Polybench-GPU nos Devices Disponíveis na Odroid-Xu3 (A15, A7, Mali T628)
  - (Analise Energia Idle.ipynb) Analise da execução das aplicações em todos os dispositivos buscando a dissipação de potência, considerando a frequência de operação dos dispositivos em Idle.

# SIM19 - Análise dos dados obtidos para apresentação no Simpósio Sul de Micro-eletrônica 2019

## Polybench/GPU evaluation for (Emicro) SIM 2019

### This repository contain codes for the tests of latency and energy consumption (polybench and polybench-energy directories respectively) in the Polybench/GPU applications.

 - All code and scripts were made to fit in the execution tests on the platform Odroid-XU3.
 - All app experiment data is separated in files, 1 to 15, respectively: 2DCONV, 3DCONV, 2MM, 3MM, ATAX, BICG, GEMM, GESUMMV, GRAMSCHM, MVT, SYR2K, SYRK, CORR, COVAR, and FDTD-2D.
 - Polybench/GPU source code: http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/GPU/index.html