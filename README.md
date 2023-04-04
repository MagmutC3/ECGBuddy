# ECG Buddy
!!! Most details relating project are in i::team Miro board !!!  
Ask MagmutC3 for access.
## basic flow
```mermaid
graph TD;
    2_tabelki --> Postgres;
    Postgres <--> Fast_API;
    ML --> Fast_API;
    trening.csv --> ML
    logowanie --> kni.uek.krakow.pl/ecgbuddy
    React <--> Fast_API
    React --> kni.uek.krakow.pl/ecgbuddy
```
## IDE setup and other suggestions
proposed tech stack:
* https://fastapi.tiangolo.com/
* PostgreSQL
* React.js
* Pytorch:
    * PyTorch 2.0, Python >=3.8,<=3.11, CUDA 11.7,CUDNN 8.5.0.96
