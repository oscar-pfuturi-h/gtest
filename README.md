# GTest on Windows
Se ha integrado GTest en el IDE de Visual Studio Code para realizar la siguiente prueba unitaria

## Códigos

### triangle.cpp
Código que se utilizará en la prueba \
![Alt text](https://github.com/oscar-pfuturi-h/gtest/blob/main/images/code.JPG)

### triangle.h
![Alt text](https://github.com/oscar-pfuturi-h/gtest/blob/main/images/header.JPG)

### triangle_test.cpp
Código que realizará las pruebas del archivo triangle.cpp
![Alt text](https://github.com/oscar-pfuturi-h/gtest/blob/main/images/testcode.JPG)

## Prueba
Compilamos los códigos:\
> g++ triangle.cpp -c \
> g++ triangle_test.cpp -c \
\
Luego ejecutamos el siguiente comando para realizar el test: \
> g++ triangle.o triangle_test.o -lgtest -lgtest_main -lpthread \
![Alt text](https://github.com/oscar-pfuturi-h/gtest/blob/main/images/testingcode.JPG)
