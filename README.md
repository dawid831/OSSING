# Projekt z kursu Optymalizacja systemów i sieci informatycznych nowej generacji
Kurs zrealizowany na kierunku Informatyka Stosowana - 2. stopień w trakcie semestru letniego 2025/2026 na Politechnice Wrocławskiej. Skład grupy projektowej:  
- Dawid Nowak  
- Jan Narożny  
- Adrian Czubaty  

Etapy wykonania projektu:
1. Do konca marca zrozumiec model matematyczny.
2. zastosować narzędzia - solvery - do podawania rozwiązania na podstawie zadanego modelu. 
	np optymalizacja liniowa:

$$
\begin{aligned}
\max \left( C^T X \right) \\
Ax \leq b \\
x \geq 0
\end{aligned}
$$
3. Zaimplementować algorytm opisany w artykule. 
4. Porównać rozwiązania z solvera i algorytmu.
5. Sprawozdanie, powyższe kroki opisane po jednym rozdziale. Termin oddania: ostatnie zajęcia.

Etapy sprawdzane w formie krótkiej prezentacji. Zajecia są jako konsultacje. 

Oceniane są:
- Terminowość: każde spóźnienie dowolnego etapu to pół oceny w dół (!!!!!) Nie jest oceniany stopień wykonania zadania, prowadzący udziela wskazówek dotyczących dalszych etapów.
- Sprawozdanie końcowe.

Opis plików projektu:  
- folder data/ - zawiera pliki json zawierające dane wejściowe (testowe)  
- can_cplex.py - implementacja rozwiązania z użyciem solvera  
- can_heuristic.py - (TODO) implementacja algorytmu rozwiązującego problem  
- ModelReaser.py - wczytywanie, weryfikacja i przechowywanie danych z plików  
- routing_viz.py - (TODO - zweryfikować działania) wizualizacja  

W celu uruchomienia programu wykonać polecenie `uv run projekt/can_cplex.py [ścieżka_do_pliku]`.
