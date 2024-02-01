# Laboratorio 1 CVDS 
## Por David Leonardo Piñeros Cortés

* Edad 21 años
* 7 **semestre**
* Ingenieria de _Sistemas_

![alt](xd.jpg)\
Obtenido de [Pinterest](https://co.pinterest.com)

El siguiente codigo es una práctica de html y css, consiste en hacer lo botones de algunas redes sociales como:
1. Youtube
2. Twitter
3. Otras mas

```
<style>
    .sub {
        background-color: rgb(194, 7, 7);
        color: white;
        border: none;
        height: 35px;
        width: 110px;
        border-radius: 5px;
        cursor: pointer;
        margin-right: 10px;
        transition: opacity 0.15s;
    }

    .sub:hover {
        opacity: 0.5;
    }

    .sub:active {
        opacity: 0.8;
    }

    .join{
        background-color: white;
        color: rgb(8, 8, 184);
        border-color: rgb(8, 8, 184);
        height: 35px;
        width: 100px;
        border-radius: 5px;
        border-width: 1px;
        border-style: solid;
        cursor: pointer;
        transition: background-color 1s, color 1s;
    }

    .join:hover {
        background-color: rgb(8, 8, 184);
        color: white;
    }

    .join:active{
        opacity: 0.5;
    }

    .tweet{
        background-color: rgb(36, 124, 255);
        color: white;
        border: none;
        height: 35px;
        width: 100px;
        font-weight: bold;
        font-size: 15px;
        border-radius: 17px;
        cursor: pointer;
        margin-left: 10px;
        transition: box-shadow 1s;
    }

    .tweet:hover {
        box-shadow: 5px 5px 10px rgba(0,0,0, 0.15);
    }

    .stretch {
        background-color: rgb(6, 75, 6);
        color: white;
        border: none;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 5px;
        padding-bottom: 5px;
        transition: padding-left 1s, padding-right 1s, padding-top 1s, padding-bottom 1s;
        margin-top: 5px;
        margin-left: 5px;
    }

    .stretch:hover {
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 10px;
        padding-bottom: 10px;
    }

</style>



<button class="sub">SUBSCRIBE</button>
<button class="join">JOIN</button>
<button class="tweet">Tweet</button>
<button class="stretch">Stretch</button>
```
## Parte 3

![pantallazo1](Pantallazo1.png)
![pantallazo2](Pantallazo2.png)