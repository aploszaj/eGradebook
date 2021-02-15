#  **Wymagania**

## **Feature:** Usunięcie ucznia z listy

**Given:** Nauczyciel jest na stronie swoich uczniów\
**When:** klikam przycisk Zarządzaj uczniami\ 
**And** klikam przycisk Usuń\
**Then:** uczeń zostaje usunięty z list

--------------------------------------------------------------------

## **Feature:** Dodanie ucznia do listy

**Given:** Nauczyciel jest na stronie swoich uczniów\
**When:** klikam przycisk Zarządzaj uczniami\ 
**And:** klikam przycisk Dodaj ucznia\
**And** wypełniam dane
**Then:** uczeń zostaje dodany do list

--------------------------------------------------------------------

## **Feature:** Edycja ucznia

**Given:** Nauczyciel jest na stronie swoich uczniów\
**When:** klikam przycisk Zarządzaj uczniami\ 
**And:** klikam przycisk Edytuj\
**And** zmienię dane ucznia
**Then** dane ucznia zostają zmienione

--------------------------------------------------------------------

## **Feature:** Wyświetlenie danych ucznia

**Given:** Nauczyciel jest na stronie swoich uczniów\
**When:** klikam przycisk Zarządzaj uczniami\ 
**And:** klikam przycisk Dane ucznia\
**Then:** dane ucznia zostają wyświetlone

--------------------------------------------------------------------

## **Feature:** Usunięcie oceny

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam na ocenę\
**And** klikam Usuń\
**Then:** ocena zostaje usunięta

--------------------------------------------------------------------

## **Feature:** Edycja oceny

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam na ocenę\
**And** klikam Edytuj\
**And** wybieram inną ocenę\
**Then:** ocena zostaje zmieniona

--------------------------------------------------------------------

## **Feature:** Dodanie oceny

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam na kolumnę\
**And** klikam rozwijaną listę\
**And** wybiorę ocenę\
**Then:** ocena zostaje dodana

--------------------------------------------------------------------

## **Feature:** Dodanie grupy ocen

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam przycisk Grupy ocen\
**And** klikam przycisk Dodaj\
**And** wypełnię pola\
**Then:** grupa ocen zostaje dodana

--------------------------------------------------------------------

## **Feature:** Usunięcie grupy ocen

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam przycisk Grupy ocen\
**And:** klikam przycisk Usuń\
**Then:** grupa ocen zostaje usunięta

--------------------------------------------------------------------

## **Feature:** Edycja grupy ocen

**Given:** Nauczyciel jest na stronie klasy, którą uczy\
**When:** klikam przycisk Grupy ocen\
**And** klikam przycisk Edytuj\
**And** zmienię dane w polach\
**Then:** grupa ocen zostaje zmieniona


--------------------------------------------------------------------

# **Mockupy**

![Mockup zarządzania uczniam](/docs/img/mockub_zarzadzanie_uczniami.jpg "Mockup zarządzania uczniami")
![Mockup oceny](/docs/img/mockup_oceny.jpg "Mockup dodawania ocen przez nauczyciela przedmiotowego")
![Mockup oceny_wychowawca](/docs/img/mockup_oceny_wychowawca.jpg "Mockup dodawania ocen przez nauczyciela wychowawcę")


--------------------------------------------------------------------

# **Projektowanie bazy**

![Schemat bazy danych](/docs/img/dbSchema_v3.jpg "Schemat BD v. 3")
