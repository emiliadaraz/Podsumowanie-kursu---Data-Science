# Podsumowanie-kursu---Data-Science
# Lending Club to firma pożyczkowa typu peer-to-peer, która łączy pożyczkobiorców z inwestorami za pośrednictwem platformy internetowej. Obsługuje osoby, które potrzebują pożyczek osobistych w wysokości od 1000 do 40 000 USD. Pożyczkobiorcy otrzymują pełną kwotę udzielonej pożyczki pomniejszoną o opłatę początkową, która jest uiszczana firmie. Inwestorzy kupują weksle zabezpieczone osobistymi pożyczkami i płacą Lending Club opłatę za usługę. Firma Lending Club udostępnia dane o wszystkich pożyczkach udzielonych za pośrednictwem swojej platformy w określonych okresach.
# Zadanie to zbudowanie modelu klasyfikacyjnego, który na podstawie  danych będzie przewidywał z określoną dokładnością, czy potencjalny pożyczkobiorca spłaci swój dług z tytułu zaciągniętej pozyczki. 
# Analiza polegała na:
# - obróbce danych (Data Processing),
# - EDA,
# - Feature Engineering,
# - Modelowanie:
# -- klasteryzacja danych (3 metody),
# -- wytrenowanie 5 różnych modeli, wykorzystując do każdego inny algorytm, a następnie porówanie ich działanie, za metrykę oceny jakości modelu przyjęto AUROC score,
# -- weryfikacja powyższych wytrenowanych modeli na skompresowanych danych za pomocą PCA, wyniki porównano (AUROC score) z modelami wytrenowanymi w poprzednim podpunkcie,
# -- zbudowanie finalnego modelu, gdzie AUROC score był >= 80%, następnie kroswalidacja oraz dostrojenie parametrów modelu, dodatkowo wykonano zbalansowania klas.
