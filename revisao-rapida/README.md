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
    - [Tipos de Linhas\\Setas gerais](#tipos-de-linhassetas-gerais)
      - [Linha\\Setas sem estilo](#linhasetas-sem-estilo)
      - [Linha\\Setas com estilo](#linhasetas-com-estilo)
      - [Exemplo](#exemplo)
        - [Código](#código)
        - [Diagrama](#diagrama)
    - [🧭 Direção dos elementos](#-direção-dos-elementos)
    - [🖌️ Design](#️-design)
      - [Cores](#cores)
      - [Exemplo de aplicação de cores](#exemplo-de-aplicação-de-cores)
        - [Código](#código-1)
        - [Diagrama](#diagrama-1)
      - [Skinparam](#skinparam)
      - [Skinparam UML](#skinparam-uml)
        - [UML 1 E 2](#uml-1-e-2)
      - [Skinparam nativo](#skinparam-nativo)
      - [Themes](#themes)
      - [Icons](#icons)
        - [Logos](#logos)
  - [🗂️ Diagramas](#️-diagramas)
    - [📚 Class](#-class)
    - [🔲 Retângulo](#-retângulo)
      - [Retângulo: Principais sintaxes](#retângulo-principais-sintaxes)
    - [📦 Component](#-component)
      - [Component: Principais sintaxes](#component-principais-sintaxes)
      - [Linhas | Setas](#linhas--setas)
  - [⏰ Dicas de produtividade](#-dicas-de-produtividade)
    

## 🌐 Comandos gerais 

### HTML

| Estilo de texto |  Tags                                          |
|:----------------|:-----------------------------------------------|
|`Negrito`        | `<b>texto</b>`                                 |
|`Sublinhado`     | `<u>texto sublinhado</u>`                      |
|`Tachado`        | `<s>texto tachado</s>`                         |
|`size`           | `<size:20>Aumenta o tamanho da fonte</size:20>`|
|`font`           | `<font color=red>Warning:</font>`              |

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

### Tipos de Linhas\Setas gerais

#### Linha\Setas sem estilo

| Linhas \ Setas                  |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Linha simples`                  | `- ou --`                      |
|`Linha tracejada`                | `. ou ..`                      |
|`Linha negrito`                  | `= ou ==`                      |
|`Linha com seta`                 | `<-- ou -->`                   |
|`Linha com seta vazia`           | `<|-- ou --|>`                 |
|`Esconde a Linha`                | `-[hidden]-`                   |
|`Defini a largura da Linha`      | `-[thickness=4]-`              |

---

#### Linha\Setas com estilo

Tipos de linhas: `bold, dashed e dotted`.

| Linhas \ Setas                  |  Sintaxe                       |
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

### 🖌️ Design

#### Cores

As cores podem ser aplicadas usando nomes predefinidos (como Red, Blue, Green) ou utilizando códigos hexadecimais (como #FF5733).

- [Cores com códigos hexadecimais ](https://www.w3schools.com/colors/colors_names.asp)

![Imagem cores](../img-geral/img-revisao-rapida/img-cores.png)


#### Exemplo de aplicação de cores
##### Código
##### Diagrama

####  Skinparam

É um comando utilizado para personalizar a aparência de elementos no diagrama, permitindo ajustes em cores, fontes, tamanhos, estilos de borda e outras propriedades visuais.

- [Link do skinparam](https://plantuml-documentation.readthedocs.io/en/latest/diagrams/index.html)

####  Skinparam UML

##### UML 1 E 2

| Temas                           |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`skinparam componentStyle uml1`  | `xxx`                          |
|`skinparam componentStyle uml2`  | `xxx`                          |

####  Skinparam nativo

| Temas                           |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`skin rose`                      | `rose`                         |
|`skinparam handwritten true`     | `handwritten true`             |
|`skinparam shadowing true`       | `sombra`                       |
|`skinparam shadowing false`      | `sombra`                       |

####  Themes

- [Temas](https://the-lum.github.io/puml-themes-gallery/)


| Temas                           |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`!theme crt-amber`               | `-[#red,dashed]-`              |
|`!theme sketchy`                 | `-[#blue,dotted]-`             |
|`!theme crt-green`               | `<-[#blue,bold]->`             |
|`!theme cyborg-outline`          | `<|-[#blue,bold]-|>`           |

####  Icons 

#####  Logos

- [Logos](https://github.com/plantuml/plantuml-stdlib/tree/master/logos)


| Logos                                   |  Sintaxe                       |
|:----------------------------------------|:-------------------------------|
|`!include <logos/django.puml>`           | `-[#red,dashed]-`              |
|`!include <logos/android-vertical.puml>` | `-[#blue,dotted]-`             |
|`!include <logos/java.puml>`             | `<-[#blue,bold]->`             |

---


## 🗂️ Diagramas
### 📚 Class
### 🔲 Retângulo

#### Retângulo: Principais sintaxes

```
@startuml

skinparam backgroundcolor #cdcdcd

caption \n\nFigure 1 - Retangle

rectangle Restaurante #gold

' rectangle simples sem STEREOTYPE
rectangle cliente

' rectangle Usando alias
rectangle restaurante <<BR>> as br #green/yellow

' rectangle sem alias
rectangle restaurante <<USA>> #red/white;text:white

rectangle "<:hotdog:> comida americana" as comidaAmericana#white


''=========================  RELACOES  ==================================

Restaurante .. restaurante
Restaurante .. br :\t\t\t
restaurante --> comidaAmericana : **serve**
comidaAmericana  <-right- cliente : **escolhe**


@enduml

```

Figure 1 - Retangle

![rectangle-principais-sintaxes](../img-geral/img-revisao-rapida/rectangle-principais-sintaxes.png)

### 📦 Component


#### Component: Principais sintaxes

#### Linhas | Setas

| Linhas \ Setas                  |  Sintaxe                       |
|:--------------------------------|:-------------------------------|
|`Linha simples`                  | `- ou --`                      |
|`Linha tracejada`                | `. ou ..`                      |
|`interface fornecida`            | `-0)-`                         |
|`interface requerida`            | `-(0-`                         |
|`Dependência`                    | `<-- ou -->`                   |
|`Realização \ seta vazia`        | `<|-- ou --|>`                 | 
|`Esconde a Linha`                | `-[hidden]-`                   |
|`Defini a largura da Linha`      | `-[thickness=4]-`              |


## ⏰ Dicas de produtividade

- Crie primeiramente os objetos e depois faça as relações.
- Deixe a estilização por úlitmo ou utilize Skinparam que tem opções prontas a sua escolha.


