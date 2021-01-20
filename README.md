## **Feature:** Wyświtlenie listy uczniów
### **Scenario:** jako nauczyciel (wychowawca) chcę wyświetlić listę uczniów

**Given:** jestem na stronie Lista uczniów\
**Then:** wyświetla się lista dodanych uczniów\
**And:** obok danych każdego ucznia pojawia się przycisk Szczegóły

--------------------------------------------------------------------

## **Feature:** Dodanie ucznia do listy
### **Scenario:**  jako nauczyciel (wychowawca) chcę dodać ucznia do listy

**Given:** jestem na stronie Lista uczniów\
**When:** klikam przycisk Dodaj ucznia\
**Then:** wyświetla się formatka Dane ucznia\
**When:** wpisuję w pole Nazwisko nazwisko ucznia\
**And:** wpisuję w pole Imię imię ucznia\
**And:** klikam <przycisk>

#### **Examples:**

|    PRZYCISK	 |	    OPERACJA		|
|:--------------:|:----------------------------:|
|Zatwierdź	 |dodanie ucznia do listy	|
|Anuluj		 |brak dodania ucznia do listy	|

**Then:** formatka zamyka się\
**And:** wyświetla się strona Lista uczniów

--------------------------------------------------------------------

## **Features:** Edycja ucznia
### **Scenario:** jako nauczyciel (wychowawca) chcę edytować dane ucznia

**Given:** jestem na stronie Lista uczniów\
**When:** klikam przycisk Szczegóły obok danych ucznia, którego chcę edytować\
**Then:** wyświetla się formatka Szczegóły\
**When:** klikam przycisk Edytuj\
**Then:** wyświetla się formatka Edytuj ucznia z danymi ucznia do edycji\
**When:** klikam <przycisk>

#### **Examples:** 

|   PRZYCISK	| 	    OPERACJA		|
|:-------------:|:-----------------------------:|
|Zatwierdź	|zapisanie zmian dla ucznia	|
|Anuluj		|porzucenie zmian dla ucznia	|

**Then:** wyświetla się formatka Szczegóły


## **Feature:** Usunięcie ucznia
### **Scenario:**  jako nauczyciel (wychowawca) chcę usunąć ucznia z listy

**Given:** jestem na stronie Lista uczniów\
**When:** klikam przycisk Szczegóły obok danych ucznia, którego chcę usunąć\
**Then:** wyświetla się formatka Szczegóły\
**When:** klikam Usuń\
**Then:** wyświetla się komunikat „Czy na pewno chcesz usunąć ucznia?” posiadający dwa <przyciski>

#### **Examples**

|   PRZYCISK	|		OPERACJA		|
|:-------------:|:-------------------------------------:|
|Ok		|uczeń zostaje usunięty z listy		|
|Anuluj		|uczeń nie zostaje usunięty z listy	|


**Than:** zamyka się formatka z komunikatem

--------------------------------------------------------------------

## **Feature:** Wyświetlenie szczegółów
### **Scenario:** jako nauczyciel (wychowawca) chcę wyświetlić szczegóły dotyczące danego ucznia

**Given:** jestem na stronie Lista uczniów\
**When:** klikam przycisk Szczegóły\
**Then:** wyświetla się formatka Szczegóły\
**When:** kliknę <przycisk>

#### **Examples:**

|   PRZYCISK	|		OPERACJA		|
|:------------: |:-------------------------------------:|
|Cofnij		|wyświetlenie strony Lista uczniów	|
|Usuń		|usunięcie ucznia			|
|Edytuj		|edycja ucznia				|

![Schemat bazy danych wersja uposzczona](/docs/img/dbSchema_v1.jpg "Schemat BD v. 1")

![Schemat bazy danych wersja rozszerzona](/docs/img/dbSchema_v2.jpg "Schemat BD v. 2")

![Mockup zarządzania uczniam](/docs/img/mockup.jpg "Mockup zarządzania uczniami")
