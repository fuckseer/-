# ThreadPoolExecutor и ProcessPoolExecutor 

## время проверки ссылок при 1 потоке:
![image](https://user-images.githubusercontent.com/75948025/144116734-c244f245-919a-4f41-8735-c93272512c69.png)

## ThreadPoolExecutor с 5 воркерами
![image](https://user-images.githubusercontent.com/75948025/144118478-b2febd79-7a0e-4228-9b8c-1cb91c3768b5.png)
![image](https://user-images.githubusercontent.com/75948025/144118633-1da131ed-5008-4cd3-877d-1803350a5b0a.png)

## ThreadPoolExecutor с 10 воркерами
![image](https://user-images.githubusercontent.com/75948025/144119293-e3e8722e-c8ac-47d2-a4d9-5c180bde023a.png)
![image](https://user-images.githubusercontent.com/75948025/144118899-8e24c341-fd71-4a81-85ed-704f9b015377.png)

## ThreadPoolExecutor с 100 воркерами
![image](https://user-images.githubusercontent.com/75948025/144119747-7cc405a9-f3de-4f50-bf0c-a8f53398aedc.png)
![image](https://user-images.githubusercontent.com/75948025/144119550-c83f55cc-2f57-4968-bae5-d6108384cf20.png)

### Вывод: загрузка памяти не зависит от количества воркеров. Загрузка увеличивается, как и загрузка интернета, но время работы программы уменьшается в несколько раз.Нет смысла делать больше воркеров, так как прирост становится незначительным.

## генерация 1 ядра
![image](https://user-images.githubusercontent.com/75948025/144127280-0a6abfc7-eace-4fc4-aa69-c01ef8c21000.png)
![image](https://user-images.githubusercontent.com/75948025/144121579-93ba3a8f-7c4a-4eab-a292-a1bfa389a73d.png)


## ProcessPoolExecutor c 2 воркерами
![image](https://user-images.githubusercontent.com/75948025/144128640-9020d6d3-5b23-4cbf-8e43-63154d63c559.png)
![image](https://user-images.githubusercontent.com/75948025/144128432-3e9e55e0-d042-44f1-93b3-212b893ed69e.png)

## ProcessPoolExecutor c 4 воркерами
![image](https://user-images.githubusercontent.com/75948025/144128994-bff25d9d-8199-404f-8d51-a3242f255df2.png)
![image](https://user-images.githubusercontent.com/75948025/144128821-1018653f-b371-4f72-b537-d45e37c26674.png)


## ProcessPoolExecutor c 5 воркерами
![image](https://user-images.githubusercontent.com/75948025/144127816-21c7b59b-48be-47df-9089-a39c20286c48.png)
![image](https://user-images.githubusercontent.com/75948025/144127560-aeff655b-698d-419c-ade6-13569722a9bc.png)

##ProcessPoolExecutor c 10 воркерами
![image](https://user-images.githubusercontent.com/75948025/144128123-361896b8-e1ad-471a-b061-42d9f5d9e44d.png)
![image](https://user-images.githubusercontent.com/75948025/144128043-3ef17fa6-07cc-4afd-997a-b692cceab2b6.png)

## ProcessPoolExecutor c 61 воркерами

![image](https://user-images.githubusercontent.com/75948025/144129262-6d7148d1-4275-4a7f-9c17-9c7a3e7f6fb9.png)
![image](https://user-images.githubusercontent.com/75948025/144129516-60e1d8ca-70fc-4f95-86c9-31ad64f6ca6b.png)

### Вывод: загрузка памяти не зависит от количества воркеров. Загрузка увеличивается, но когда число воркеров достигает числа ядер процессора - не изменяется





