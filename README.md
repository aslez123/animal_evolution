# Projekt - Ewolucja zwierząt

Głównym celem projektu jest stworzenie wirtualnego świata, który składa się ze stepów lub z dżungli, zamieszkałego przez zwierzęta. Zwierzęta poruszają się, szukają pożywienia, jedzą i rozmnażają się. 

Świat, który tworzymy, składa się z prostokątnej mapy podzielonej na kwadratowe pola. W zależności od wariantu, obszar może być porośnięty przez stepy, gdzie rośnie niewiele roślin lub dżunglę, gdzie rośliny rosną szybciej i są bardziej liczne. 

Zwierzęta w projekcie są roślinożerne i poruszają się po mapie w poszukiwaniu pożywienia. Każde zwierzę ma określoną energię, która każdego dnia stopniowo się zmniejsza. Dodatkowo energia wykorzystywana jest do tworzenia potmostwa. Znajdowanie i jedzenie roślin zwiększa poziom energii zwierzęcia.

Aby śledzić zachowanie zwierząt, musimy monitorować kilka ich cech. Po pierwsze, musimy znać współrzędne x i y, które określają położenie zwierzęcia na mapie. Musimy również mieć informację o energii zwierzęcia, która jest wskaźnikiem jego stanu zdrowia i przetrwania. Kierunek, w którym zwierzę jest zwrócone, również jest ważny, ponieważ wpływa na jego ruch. Zwierzę może być zwrócone w jednym z ośmiu możliwych kierunków, które mogą być zmieniane za pomocą genów. Geny to kolejna cecha, którą musimy śledzić. Każde zwierzę ma zestaw genów, które opisują ich zachowanie. Podczas ruchu, zwierzę korzysta z aktywnego genu, który wpływa na jego orientację i kierunek poruszania się. Geny są cyklicznie aktywowane.
