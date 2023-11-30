# ComputacaoGrafica
KCF e CSRT

## KCF (Kernelized Correlation Filter)

Finalidade: KCF é um algoritmo de rastreamento de objetos que visa acompanhar a posição de um objeto ao longo do tempo em um vídeo.
Características Principais: 
Rastreamento robusto: Pode rastrear objetos em sequências de vídeo.
Utiliza técnicas de filtragem correlacionada para estimar a posição do objeto.
Uso Típico: Aplicações que exigem rastreamento contínuo de objetos em vídeos, como rastreamento de veículos em um vídeo de trânsito.

O algoritmo KCF (Kernelized Correlation Filter) é projetado para rastreamento de objetos individuais ao longo do tempo. Ele não é, por padrão, otimizado para rastrear múltiplos objetos simultaneamente em um único quadro de vídeo. Portanto, se você estiver lidando com uma cena que envolve o rastreamento de vários carros em uma única imagem ou quadro de vídeo, o KCF pode não ser a escolha mais adequada para essa tarefa específica.

## CSRT (Discriminative Correlation Filter with Channel and Spatial Reliability)

Finalidade: CSRT é um algoritmo de rastreamento de objetos que visa melhorar o rastreamento em cenas desafiadoras, incluindo mudanças de iluminação e oclusões.
Características Principais: Inclui informações de confiança espacial e de canal para melhorar a precisão. Lida bem com variações de escala, rotação e mudanças de aparência.
Uso Típico: Aplicações que requerem rastreamento robusto em condições desafiadoras, como rastreamento de objetos em ambientes dinâmicos e variáveis.


<br> ![obg](https://github.com/nandinhaaa/ComputacaoGrafica/assets/91507393/b81dcf29-7b7b-41fd-8d85-a23404b0a055) 
