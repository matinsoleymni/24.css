# 24.css Version => 1.1.1
## This is a CSS3 Library
-------
# Getting Stated 
- [Why Use 24.css ?](#Why-Use-24css)
- [How To Use ?](#How-To-Use)
- [Features](#Features)
1. [Display](#Display)
2. [Flex Setting](#Flex-Setting)
    - [Justify Content](#Justify-Content)
    - [gap](#gap)
    - [Align Item](#Align-Item)
    - [Flex Direction](#Flex-Direction)
3. [Padding](#padding)
4. [Margin](#margin)
6. [Border Radius](#border-radius)
    - [Border None](#border-none)
7. [Text Align](#text-align)
8. [Font Size](#font-size)
9. [Width & Height](#width--height)
9. [User Zoom & User Select](#user-zoom--user-select)
10. [Cursor](#cursor-setting)
11. [position](#position)
12. [color](#color--backgroundcolor)

# Why-Use-24.css?

1. Very Esey
2. Very Fast
3. Low Size
4. Very Simple to Use
5. It Reduces Your Code
6. and more...

# How-To-Use?

<p>Just add this CDN to HEAD of HTML project file <p>

```HTML
    <link rel="stylesheet" href="https://blokchainology.com/CDN/min24.css">
```

# Features

## Display

| Class Name         | In CSS                               |  Example                     |
|--------------------|:------------------------------------:|-----------------------------:|
| d-none             |    `css => display:none;`            | `<button class="d-none">`    |
| d-flex             |    `css => display:flex;`            | `<button class="d-flex">`    |
| d-block            |    `css => display:block;`           | `<button class="d-block">`   |
| d-grid             |    `css => display:grid;`            | `<button class="d-grid">`    |
| d-in-block         |    `css => display:inline-block;`    | `<button class="d-in-block">`|
| d-in-flex          |    `css => display:inline-flex;`     | `<button class="d-in-flex">` |
| d-in-grid          |    `css => display:inline-grid;`     | `<button class="d-in-grid">` |

--------------------------------------------------------------------------------------------

## Flex-Setting


### Justify-Content
**You must have a display FLEX (d-flex) to use it**    

| Class Name         | In CSS                                   |  Example                                       |
|--------------------|:----------------------------------------:|-----------------------------------------------:|
| j-center           |  `css => justify-content: center;`       |  `<div class="d-flex j-center">Zmat24</div>`   |
| j-between          |  `css => justify-content: space-between;`|  `<div class="d-flex j-between">Zmat24</div>`  |
| j-around           |  `css => justify-content: space-around;` |  `<div class="d-flex j-around">Zmat24</div>`   |
| j-evenly           |  `css => justify-content: space-evenly;` |  `<div class="d-flex j-evenly">Zmat24</div>`   |
| j-fstart           |  `css => justify-content: flex-start;`   |  `<div class="d-flex j-fstart">Zmat24</div>`   |
| j-fend             |  `css => justify-content: flex-end;`     |  `<div class="d-flex j-fend">Zmat24</div>`     |
| j-right            |  `css => justify-content: right;`        |  `<div class="d-flex j-right">Zmat24</div>`    |
| j-left             |  `css => justify-content: left;`         |  `<div class="d-flex j-center">Zmat24</div>`   |
<br>
-----------------------------------------------------------------------------------------------------------

### gap
**You must have a display FLEX (d-flex) to use it**  

| Class Name         | In CSS                |  Example                                   |
|--------------------|:---------------------:|-------------------------------------------:|
| gap-5              |  `css => gap:5px;`    |  `<div class="d-flex gap-5">Zmat24</div>`  |
| gap-10             |  `css => gap:10px;`   |  `<div class="d-flex gap-10">Zmat24</div>` |
| gap-15             |  `css => gap:15px;`   |  `<div class="d-flex gap-15">Zmat24</div>` |
<br>
--------------------------------------------------------------------------------------

### Align-Item
**You must have a display FLEX (d-flex) to use it**    

| Class Name         | In CSS                                   |  Example                                           |
|--------------------|:----------------------------------------:|---------------------------------------------------:|
| align-item-c       |  `css => align-items:center;`            |  `<div class="d-flex align-item-c">Zmat24</div>`   |
| align-item-fs      |  `css => align-items:flex-start;`        |  `<div class="d-flex align-item-fs">Zmat24</div>`  |
| align-item-fe      |  `css => jalign-item:flex-end`           |  `<div class="d-flex align-item-fe">Zmat24</div>`  |
<br>
----------------------------------------------------------------------------------------------------------------

### Flex-Direction
**You must have a display FLEX (d-flex) to use it**    

| Class Name         | In CSS                                   |  Example                                           |
|--------------------|:----------------------------------------:|---------------------------------------------------:|
| f-dir-col          |  `css => flex-direction:column;`         |  `<div class="d-flex align-item-c">Zmat24</div>`   |
| f-dir-col-r        |  `css => flex-direction:column-reverse;` |  `<div class="d-flex align-item-fs">Zmat24</div>`  |
| f-dir-row          |  `css => flex-direction:row`             |  `<div class="d-flex align-item-fe">Zmat24</div>`  |
| f-dir-row-r        |  `css => flex-direction:row-reverse;`    |  `<div class="d-flex align-item-fe">Zmat24</div>`  |
<br>
----------------------------------------------------------------------------------------------------------------

## Padding
### 5 to 20 px (p-5 => 5px | p-10 => 10px | p-15 => 15px | p-20 => 20px) for every (top | bottom | left | right)

| Class Name         | In CSS                                   |  Example                           |
|--------------------|:----------------------------------------:|-----------------------------------:|
| p-5                |  `css => padding:5px;`                   |  `<div class="p-5">Zmat24</div>`   |
| pt-5               |  `css => padding-top:5px;`               |  `<div class="pt-5">Zmat24</div>`  |
| pb-5               |  `css => padding-bottom:5px;`            |  `<div class="pb-5">Zmat24</div>`  |
| pl-5               |  `css => padding-left:5px;`              |  `<div class="pl-5">Zmat24</div>`  |
| pr-5               |  `css => padding-right:5px;`             |  `<div class="pr-5">Zmat24</div>`  |


| Class Name         | In CSS                                   |  Example                           |
|--------------------|:----------------------------------------:|-----------------------------------:|
| p-10               |  `css => padding:10px;`                  |  `<div class="p-10">Zmat24</div>`  |
| pt-10              |  `css => padding-top:10px;`              |  `<div class="pt-10">Zmat24</div>` |
| pb-10              |  `css => padding-bottom:10px;`           |  `<div class="pb-10">Zmat24</div>` |
| pl-10              |  `css => padding-left:10px;`             |  `<div class="pl-10">Zmat24</div>` |
| pr-10              |  `css => padding-right:10px;`            |  `<div class="pr-10">Zmat24</div>` |


| Class Name         | In CSS                                   |  Example                           |
|--------------------|:----------------------------------------:|-----------------------------------:|
| p-15               |  `css => padding:15px;`                  |  `<div class="p-15">Zmat24</div>`  |
| pt-15              |  `css => padding-top:15px;`              |  `<div class="pt-15">Zmat24</div>` |
| pb-15              |  `css => padding-bottom:15px;`           |  `<div class="pb-15">Zmat24</div>` |
| pl-15              |  `css => padding-left:15px;`             |  `<div class="pl-15">Zmat24</div>` |
| pr-15              |  `css => padding-right:15px;`            |  `<div class="pr-15">Zmat24</div>` |


| Class Name         | In CSS                                   |  Example                           |
|--------------------|:----------------------------------------:|-----------------------------------:|
| p-20               |  `css => padding:20px;`                  |  `<div class="p-20">Zmat24</div>`  |
| pt-20              |  `css => padding-top:20px;`              |  `<div class="pt-20">Zmat24</div>` |
| pb-20              |  `css => padding-bottom:20px;`           |  `<div class="pb-20">Zmat24</div>` |
| pl-20              |  `css => padding-left:20px;`             |  `<div class="pl-20">Zmat24</div>` |
| pr-20              |  `css => padding-right:20px;`            |  `<div class="pr-20">Zmat24</div>` |

----------------------------------------------------------------------------------------------------------------

## Margin
### 5 to 20 px (m-5 => 5px | m-10 => 10px | m-15 => 15px | m-20 => 20px) for every (top | bottom | left | right)

| Class Name         | In CSS                                  |  Example                           |
|--------------------|:---------------------------------------:|-----------------------------------:|
| m-5                |  `css => margin:5px;`                   |  `<div class="m-5">Zmat24</div>`   |
| mt-5               |  `css => margin-top:5px;`               |  `<div class="mt-5">Zmat24</div>`  |
| mb-5               |  `css => margin-bottom:5px;`            |  `<div class="mb-5">Zmat24</div>`  |
| ml-5               |  `css => margin-left:5px;`              |  `<div class="ml-5">Zmat24</div>`  |
| mr-5               |  `css => margin-right:5px;`             |  `<div class="mr-5">Zmat24</div>`  |


| Class Name          | In CSS                                   |  Example                            |
|---------------------|:----------------------------------------:|------------------------------------:|
| m-10                |  `css => margin:10px;`                   |  `<div class="m-10">Zmat24</div>`   |
| mt-10               |  `css => margin-top:10px;`               |  `<div class="mt-10">Zmat24</div>`  |
| mb-10               |  `css => margin-bottom:10px;`            |  `<div class="mb-10">Zmat24</div>`  |
| ml-10               |  `css => margin-left:10px;`              |  `<div class="ml-10">Zmat24</div>`  |
| mr-10               |  `css => margin-right:10px;`             |  `<div class="mr-10">Zmat24</div>`  |


| Class Name          | In CSS                                   |  Example                            |
|---------------------|:----------------------------------------:|------------------------------------:|
| m-15                |  `css => margin:15px;`                   |  `<div class="m-15">Zmat24</div>`   |
| mt-15               |  `css => margin-top:15px;`               |  `<div class="mt-15">Zmat24</div>`  |
| mb-15               |  `css => margin-bottom:15px;`            |  `<div class="mb-15">Zmat24</div>`  |
| ml-15               |  `css => margin-left:15px;`              |  `<div class="ml-15">Zmat24</div>`  |
| mr-15               |  `css => margin-right:15px;`             |  `<div class="mr-15">Zmat24</div>`  |


| Class Name          | In CSS                                   |  Example                            |
|---------------------|:----------------------------------------:|------------------------------------:|
| m-20                |  `css => margin:20px;`                   |  `<div class="m-20">Zmat24</div>`   |
| mt-20               |  `css => margin-top:20px;`               |  `<div class="mt-20">Zmat24</div>`  |
| mb-20               |  `css => margin-bottom:20px;`            |  `<div class="mb-20">Zmat24</div>`  |
| ml-20               |  `css => margin-left:20px;`              |  `<div class="ml-20">Zmat24</div>`  |
| mr-20               |  `css => margin-right:20px;`             |  `<div class="mr-20">Zmat24</div>`  |
<br>

----------------------------------------------------------------------------------------------------

## Border-Radius

### border radius (5 to 30 px & 10% , 20% , 30% , 50% || -- => %)

| Class Name   | In CSS                            |  Example                      |
|--------------|:---------------------------------:|------------------------------:|
| radius-5     |  `css => border-radius:5px;`      |  `<input class="radius-5">`   |
| radius-10    |  `css => border-radius:10px;`     |  `<input class="radius-10">`  |
| radius-15    |  `css => border-radius:15px;`     |  `<input class="radius-15">`  |
| radius-20    |  `css => border-radius:20px;`     |  `<input class="radius-20">`  |
| radius-25    |  `css => border-radius:25px;`     |  `<input class="radius-25">`  |
| radius-30    |  `css => border-radius:30px;`     |  `<input class="radius-30">`  |
| radius--50   |  `css => border-radius:50%;`      |  `<input class="radius--50">` |
| radius--30   |  `css => border-radius:30%;`      |  `<input class="radius--30 ">`|
| radius--20   |  `css => border-radius:20%;`      |  `<input class="radius--20 ">`|
| radius--10   |  `css => border-radius:10%;`      |  `<input class="radius--10 ">`|

----------------------------------------------------------------------------------------------------

##  Border-none 

| Class Name    | In CSS                  |  Example                    |
|---------------|:-----------------------:|----------------------------:|
| border-n      |  `css => border:none;`  |  `<input class="border-2">` |

<br>
----------------------------------------------------------------------------------------------------

## Text-Align

| Class Name      | In CSS                        |  Example                                    |
|-----------------|:-----------------------------:|--------------------------------------------:|
| t-align-center  |  `css => text-align:center;`  |  `<div class="t-align-center">Zmat24</div>` |
| t-align-left    |  `css => text-align:right;`   |  `<div class="t-align-left">Zmat24</div>`   |
| t-align-right   |  `css => text-align:right;`   |  `<div class="t-align-right">Zmat24</div>`  |
<br>
----------------------------------------------------------------------------------------------------

## Font-Size

| Class Name      | In CSS                      |  Example                             |
|-----------------|:---------------------------:|-------------------------------------:|
| f-size15        |  `css => font-size:15px;`   |  `<p class="f-size15">Zmat24</p>`    |
| f-size20        |  `css => font-size:20px;`   |  `<p class="f-size20">Zmat24</p>`    |
| f-size25        |  `css => font-size:25px;`   |  `<p class="f-size25">Zmat24</p>`    |
| f-size30        |  `css => font-size:30px;`   |  `<p class="f-size30">Zmat24</p>`    |
| f-size35        |  `css => font-size:35px;`   |  `<p class="f-size35">Zmat24</p>`    |
| f-size-large    |  `css => font-size:large;`  |  `<p class="f-size-large">Zmat24</p>`|


-----------------------------------------------------------------------------------------------------

## Width-&-Height
### In 24.css All Width and Height are based on percentages (%)

| Class Name | In CSS                 |  Example                              |
|------------|:----------------------:|--------------------------------------:|
| w--25      |  `css => width:25%;`   |  `<div class="w--25">Zmat24</div>`    |
| w--50      |  `css => width:50%;`   |  `<div class="w--50">Zmat24</div>`    |
| w--75      |  `css => width:75%;`   |  `<div class="w--75">Zmat24</div>`    |
| w--100     |  `css => width:100%;`  |  `<div class="w--100">Zmat24</div>`   |
| h--25      |  `css => height:25%;`  |  `<div class="h-25">Zmat24</div>`     |
| h--50      |  `css => height:50%;`  |  `<div class="h-50">Zmat24</div>`     |
| h--75      |  `css => height:75%;`  |  `<div class="h-75">Zmat24</div>`     |
| h--100     |  `css => height:100%;` |  `<div class="h-100">Zmat24</div>`    |

----------------------------------------------------------------------------------------------------

## User-Zoom-&-User-Select

| Class Name  | In CSS                      |  Example                             |
|-------------|:---------------------------:|-------------------------------------:|
| zoom-off    |  `css => user-zoom:none;`  |  `<body class="zoom-off"></body>`    |
| select-off  |  `css => user-select:none;` |  `<body class="select-off"></body>`  |


-----------------------------------------------------------------------------------------------------

## Cursor-Setting
### Custom User Cursor

| Class Name  | In CSS                      |  Example                                 |
|-------------|:---------------------------:|-----------------------------------------:|
| cursor-p    |  `css => cursor:pointer;`   |  `<div class="cursor-p">Zmat24</div>`    |
| cursor-a    |  `css => cursor:auto;`      |  `<div class="cursor-a">Zmat24</div>`    |
| cursor-d    |  `css => cursor:defult;`    |  `<div class="cursor-d">Zmat24</div>`    |
| cursor-off  |  `css => cursor:none;`      |  `<div class="cursor-off">Zmat24</div>`  |

---------------------------------------------------------------------------------------------------

## Position

| Class Name    | In CSS                        |  Example                                   |
|---------------|:-----------------------------:|-------------------------------------------:|
| position-ab   |  `css => position:absolute;`  |  `<div class="position-ab">Zmat24</div>`   |
| position-fix  |  `css => position:fixed; `    |  `<div class="position-fix">Zmat24</div>`  |
| position-rel  |  `css => position:relative;`  |  `<div class="position-rel">Zmat24</div>`  |
| position-st   |  `css => position:static;`    |  `<div class="position-st">Zmat24</div>`   |

--------------------------------------------------------------------------------------------------

## Color-&-backgroundcolor

### For Use Color and Background color Just add this class name for ```ELEMENT```
### Background Color => {
    back-red 
    back-green
    back-blue
    back-black
    back-brown
    back-yellow
    back-gray
    back-tan
    back-purple
    back-pink
    back-olive
    back-cadetblue
    back-cyan
    back-dmagenta

### }

### Color {
    white
    red
    green
    blue
    black
    brown
    yellow
    gray
    tan
    purple
    pink
    olive
    cadetblue
    cyan
    dmagenta
### }
