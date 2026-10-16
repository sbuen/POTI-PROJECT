## DOCUMENTACAO DO PROJETO


git status - verifica os status dos arquivos

git add . - adicionado todos os arquivos em stage de envio 

git commit -m "comentario" adiciona um comentario para seu projeto 

git push - envia as aleterações para seu github 

git pull - recebe as alteracoes do github

```mermaid
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly<br>can swim<br>can dive<br>can help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }

```
