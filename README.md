# p3modelado
Práctica 3 Modelado y Simulación de Robots


## **Gráficas y explicación**

### Mundo Sand sin choque

Como se puede ver en la gráfica, la velocidad del joint de la rueda aumenta progresivamente hasta llegar a una velocidad de 5m/s en los primeros 5 segundos, posteriormente mantiene su velocidad y termina volviendo a velocidad 0. 

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/50f4f423-4600-4d02-b8eb-83a50141b451)

Comparativa de las 4 ruedas junto al topic Twist en el eje X. Se observa como el valor del topic Twist no es igual que la velocidad final que tienen los joints de las ruedas.

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/53c7aeab-11be-4d5e-ac25-14b307801dec)

Comparativa de la aceleración lineal en el eje X del sensor IMU. 

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/1a45bf2c-c034-487b-9803-35f348cbc74a)


### Mundo Sand con choque

En la gráfica se observa como la rueda número 1 y la rueda número 3 (lado izquierdo del robot) sufren un choque con el cubo y eso hace que la velocidad se reduzca bruscamente durante un segundo. En las ruedas del lado derecho también se puede apreciar pero al no sufrir el choque directo no es tan acentuado el cambio de velocidad.
![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/cc41bcb3-c945-4fb5-98c9-f1ac2991d818)


En la comparativa del sensor IMU también se observa los bruscos cambios alrededor del segundo 6 (coincide con la gráfica anterior), haciendo que los valores sean negativos indicando una desaceleración. 

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/479868eb-dfd0-4e15-bba6-9d68c3505ea9)



### Mundo Floor sin choque

Comparativa de las 4 ruedas junto al topic Twist en el eje X. Se observa como el valor del topic Twist no es igual que la velocidad final que tienen los joints de las ruedas.

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/d1b24770-c124-4c0b-8da0-7baea6e6a149)

Comparativa de la aceleración lineal en el eje X del sensor IMU. 

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/86f20b7f-d9d2-4c27-9084-bb8ecc5cd808)



### Mundo Floor con choque

En este caso el choque no es tan agresivo como el anterior, se nota de forma más sutil en todas las ruedas. 
![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/3c519af7-d7e1-46c2-8223-e4c8ec7b3699)


Sin embargo, en el sensor IMU el cambio de la aceleración es mucho más notorio.
![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/bc646f25-143c-4d3a-bc5d-67db499af8a4)


### Choque descontrolado
Para tener más comparativa entre la simulación con choque y sin choque he realizado un choque mucho más violento. En la primera gráfica se puede ver como los cambios de velocidad perduran más en el tiempo hasta que colapsan. En la segunda gráfica el caos es también muy notorio. Comparándolas con las anteriores, los valores llegan hasta los 60 mientras que las anteriorres eran de máximo 5, indicando así numerosos cambios de velocidad, tanto acelerando como desacelerando.

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/a6f139bf-fab3-4883-b854-893ca6457f65)

![image](https://github.com/rsanchez2021/p3modelado/assets/113595025/a01edf6f-9497-46ad-93da-18a941ca39b4)


## **Vídeos**

### Mundo Sand sin choque

https://github.com/rsanchez2021/p3modelado/assets/113595025/041d5b40-a83b-4ff7-a815-99fcfb25dd9e


### Mundo Sand con choque

https://github.com/rsanchez2021/p3modelado/assets/113595025/bd2f6f02-2362-4c23-9d8f-2be60a23c01a


### Mundo Floor sin choque

https://github.com/rsanchez2021/p3modelado/assets/113595025/f71a1c19-8f50-44a4-b981-cb9ac999a68b


### Mundo Floor con choque

https://github.com/rsanchez2021/p3modelado/assets/113595025/f2384437-649e-4af8-8613-07b05eaa1f0f

### Choque descontrolado

https://github.com/rsanchez2021/p3modelado/assets/113595025/f4acff5d-6687-4a3c-987f-6cda7c7c0136

## **Rosbag**

Escenario Sand: https://urjc-my.sharepoint.com/:f:/g/personal/r_sanchezd_2021_alumnos_urjc_es/Ev77A5HG4stLl0SqVENMfRsBMr_KpZqE9PoT_hXV8XYfBw?e=N1EVMJ

Escenario Floor: https://urjc-my.sharepoint.com/:f:/g/personal/r_sanchezd_2021_alumnos_urjc_es/EqsIbitvhoFIqCNokzhNaxoBsVhMEnqAgMiI1qeeci5oVQ?e=5Lg6r5

## **Parte A**

Enlace al video: https://youtu.be/EKvFsomgBFQ





