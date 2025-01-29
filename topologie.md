  Sieci Fizyczne

1. Topologia magistrali (Bus)
Opis: Wszystkie urządzenia są połączone do jednej wspólnej linii transmisyjnej (kabel). Sygnalizacja przechodzi przez cały kabel, docierając do wszystkich urządzeń.
Wady: Kolizje danych, spadek wydajności przy dużej liczbie urządzeń, awaria kabla może zatrzymać całą sieć.
Zalety: Prosta konstrukcja, tania w budowie, łatwa do rozszerzenia.
Gdzie stosowane: Małe sieci LAN, starsze technologie.

2. Topologia pierścienia (Ring)
Opis: Urządzenia są połączone w zamknięty krąg, a dane krążą w jednym kierunku, przechodząc przez wszystkie urządzenia.
Wady: Awaria jednego urządzenia lub kabla powoduje przerwanie całej sieci.
Zalety: Brak kolizji danych, łatwiejsza synchronizacja.
Gdzie stosowane: Sieci Token Ring, starsze sieci LAN.

3. Topologia gwiazdy (Star)
Opis: Wszystkie urządzenia są połączone do centralnego urządzenia (np. przełącznika, hubu).
Wady: Awaria centralnego urządzenia powoduje przerwanie całej sieci, większe zużycie okablowania.
Zalety: Łatwość w rozbudowie, łatwa diagnoza i naprawa.
Gdzie stosowane: Większość współczesnych sieci LAN, w tym Ethernet i Wi-Fi.

  Sieci Logiczne

1. Punkt-punkt (Point-to-Point)
Opis: Połączenie bezpośrednie między dwoma urządzeniami, przesyłane dane trafiają tylko do nich.
Wady: Ograniczenie do dwóch urządzeń, awaria łącza przerywa komunikację.
Zalety: Prosta i szybka transmisja.
Zastosowanie: Połączenia między dwoma komputerami, łącza w sieciach WAN.

2. Przekazywanie żetonu (Token Passing)
Opis: Urządzenia przesyłają specjalny token, który daje prawo do transmisji.
Wady: Potrzebna synchronizacja urządzeń, ryzyko zagubienia tokenu.
Zalety: Brak kolizji, kontrola dostępu do medium.
Zastosowanie: Sieci Token Ring, systemy o dużym natężeniu ruchu.

3. Wielodostępowa (Multiple Access)
Opis: Urządzenia dzielą wspólny kanał transmisyjny, a dostęp do niego regulowany jest przez algorytmy.
Wady: Kolizje mogą wystąpić przy jednoczesnej transmisji wielu urządzeń.
Zalety: Efektywne wykorzystanie medium, skalowalność.
Zastosowanie: Sieci Ethernet, Wi-Fi, sieci mobilne.