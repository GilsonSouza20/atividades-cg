# Computação Gráfica - Gilson Junior

## Visualizador de Cenas 3D

## Configurações Globais

### Câmera

São definidos os valores de posição e inclinação da câmera de acordo com as variáveis: cameraPos, cameraFront e cameraUp. Cada uma recebe 3 coordenadas equivalentes à posição no eixo X, Y e Z respectivamente.

Exemplo:

```
cameraPos 0.0 0.0 3.0
cameraFront 0.0 0.0 -1.0
cameraUp 0.0 1.0 0.0
```

### Iluminação

São definidos os valores de posição da iluminação e cor da luz de acordo com as seguintes variáveis:

- lightPos: 3 coordenadas equivalentes à posição no eixo X, Y e Z
- lightColor: 3 coordenadas equivalentes às cores R, G e B

Exemplo:

```
lightPos -2.0 100.0 2.0
lightColor 1.0 1.0 1.0
```

## Configurações de OBJ

## Interações na cena

A cena começa com o primeiro OBJ da lista selecionado. Todos os comandos serão aplicados individualmente apenas para o objeto selecionado.

### Comandos

- ENTER -> Seleciona próximo Objeto da lista
- \- e + -> Controla a escala
- 8 e 9 -> Controla o ângulo
- X -> Rotaciona no eixo X
- Y -> Rotaciona no eixo Y
- Z -> Rotaciona no eixo Z
- Movimentar mouse -> controla rotação da câmera
- WASD -> controla posição da câmera

