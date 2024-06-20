![image](https://github.com/Geheneeike/1/assets/161126818/afc73773-7dbb-4ffd-933e-04d7e51a5c3b)




@startuml
actor Пациент as a
package Поликлиника {
  usecase "Постановка на учёт" as UC1
  usecase "Снятие с учёта" as UC2
  usecase "Запись к врачу" as UC3
  usecase "Просмотр медицинской карты" as UC4
  usecase "Заполнение анкеты" as UC5
}
a --> UC1
a --> UC2
a --> UC3
a --> UC4
a --> UC5

@enduml
@enduml
