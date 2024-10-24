# 📋 Tabela de revisão rápida ⚡

![](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExeGUwY281MXptb3h5Y2lnaXVlZmxjdHByYjBlcjZ1Mmlhd3NleXp3cyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/W8OfQ8S1PXWKY/giphy.gif)

Aqui está uma tabela de revisão sobre as principais sintaxes do plantUML.


- [📋 Tabela de revisão rápida ⚡](#-tabela-de-revisão-rápida-)
  - [🌐 Comandos gerais](#-comandos-gerais)
    - [HTML](#html)
    - [Markdown](#markdown)
    - [Comentários](#comentários)
    - [Caracteres Especiais](#caracteres-especiais)
    - [Funções](#funções)
    - [Tipos de Linhas gerais](#tipos-de-linhas-gerais)
      - [Linha sem estilo](#linha-sem-estilo)
      - [Linha com estilo](#linha-com-estilo)
      - [Exemplo](#exemplo)
        - [Código](#código)
        - [Diagrama](#diagrama)
    - [🧭 Direção dos elementos](#-direção-dos-elementos)
  - [📚 Class](#-class)
    

## 🌐 Comandos gerais

### HTML

| Estilo de texto |  Tags                        |
|:----------------|:-----------------------------|
|`Negrito`        | `<b>texto</b>`               |
|`Sublinhado`     | `<u>texto sublinhado</u>`    |
|`Tachado`        | `<s>texto tachado</s>`       |

### Markdown

| Estilo de texto |  Sintaxe                       |
|:----------------|:-------------------------------|
|`Itálico`        | ``//italics//``                |
|`Sublinhado`     | `__Texto sublinhado__`         |
|`Tachado`        | `--texto tachado--`            |
|`Sublinhado`     | `~~Sublinhado ondulado~~`      |
|`Negrito`        | `**Sublinhado ondulado**`      |

### Comentários

| Tipo de comentário |  Sintaxe                       |
|:-------------------|:-------------------------------|
|`Linha única`       |' Comentário                    |
|`Múltiplas linhas`  |/' Comentários '/               |

### Caracteres Especiais

| Caracteres Epeciais             |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Quebra de linha`                | \n                             |
|`Espaço`                         | \t                             |
|`Retorno`                        | \r                             |

### Funções

| Funções                         |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Formato de data`                | %date("dd/mm/yyyy HH:mm")      |
|`Aumenta o tamanho do diagrama`  | scale 1.5                      |

### Tipos de Linhas gerais

#### Linha sem estilo

| Linhas                          |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Linha simples`                  | `- ou --`                      |
|`Linha tracejada`                | `. ou ..`                      |
|`Linha negrito`                  | `= ou ==`                      |
|`Linha com seta`                 | `<-- ou -->`                   |
|`Linha com seta vazia`           | `<|-- ou --|>`                 |
|`Esconde a Linha`                | `-[hidden]-`                   |
|`Defini a largura da Linha`      | `-[thickness=4]-`              |

---

#### Linha com estilo

Tipos de linhas: `bold, dashed e dotted`.

| Linhas                          |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Linha bold`                     | `-[#green,bold]-`              |
|`Linha dashed`                   | `-[#red,dashed]-`              |
|`Linha dotted`                   | `-[#blue,dotted]-`             |
|`Linha bold com seta`            | `<-[#blue,bold]->`             |
|`Linha bold com seta vazia`      | `<|-[#blue,bold]-|>`           |


#### Exemplo 

##### Código 

```
@startuml

title Exemplo de diagrama com linha estilizada

rectangle restaurante as rt
rectangle cliente as cl

rt <|-[#blue,dashed,thickness=5]--|> cl

@enduml
```
##### Diagrama
![Exemplo de diagrama com linha estilizada](https://www.planttext.com/api/plantuml/png/JOwn3i8m34JtV8KbrcPa0zI5hq0C9hOQ2oT5ZYDLg1zFX1XOtztJtTmSpNlH45nS6QuRbvUkG0mak1WMXBGMKAaPWPkBoXi9Gp1EZdKPZWsCtR0w0pOm_ykI2lzu6YFcSDhZxV3GpXDXoqoJPqdFogsTZ_SOzyktE7EbSUi3)


---

### 🧭 Direção dos elementos

Representa o eixo conforme a escolha.


| Direção                                         |  Sintaxe                       |
|:------------------------------------------------|:-------------------------------|
|`Elementos alinhados da esquerda para direita`   | `left to right direction`      |
|`Elementos alinhados de cima para baixo`         | `top to bottom direction`      |


## 📚 Class


