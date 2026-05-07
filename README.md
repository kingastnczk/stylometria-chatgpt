# stylometria-chatgpt

To repozytorium zawierające pliki z mojej pracy licencjackiej pt. _Językowe cechy tekstów wygenerowanych przez sztuczną inteligencję. Analiza stylometryczna na podstawie korpusu recenzji filmowych_. Repozytorium zostało utworzone z myślą o publikacji pracy.

# Korpus

Corpus znajduje się w folderze "corpus". Pliki zostały zapisane w formacie .txt. Nazwy plików mają następujący format:

W przypadku tekstów wygenerowanych przez ChatGPT:
CHATGPT_(tytuł filmu).txt
W przypadku tekstów napisanych przez ludzi:
(nazwa serwisu)_(tytuł filmu)_(inicjały autora/autorki).txt

Dokładne informacje bibliograficzne na temat każdego z tekstów napisanych przez ludzi znajdują się w arkuszu CHARAKTERYSTYKA_KORPUSU.xls

# Modele 

Dwa z wytrenowanych przeze mnie modeli zostały udostępnione w folderze "modele". 
rf_all.joblib - model lasu losowego trenowany na wszystkich metrykach
rf_graminfl1.joblib - model lasu losowego trenowany na metrykach gramatycznych i fleksyjnych

# Metryki

Dane na temat tekstów wyliczone za pomocą metryk StyloMetriksa: metryki/metrics_final.csv
Dane uwzględniające metrykę MATTR: metryki/metrics_with_mattr.csv

Kod, za pomocą którego wyliczona została metryka MATTRL: moving_average_TTR.ipynb


