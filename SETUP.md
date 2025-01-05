#Narzedzie_Analizujace_Opinie_Klientow.rmp

#Polski

Opis (Polski):
Ten proces służy do analizy opinii na temat produktów na podstawie danych pobieranych z platformy internetowej Trustpilot w czasie rzeczywistym. Proces wykorzystuje skrypt Python do pobierania danych recenzji z witryny internetowej i ich przetwarzania w celu wygenerowania szczegółowych analiz.

Instrukcja użycia:
1. Uruchom Altair Studio na swoim komputerze, zainstaluj poniższe rozszerzenia w Altair Studio:
- Operator Toolbox
- Python Scripting (wymaga Anacondy jako środowiska Pythona, wymagane biblioteki: requests, pandas, beautifulsoup4, html5lib)
- Text Processing

2. Skonfiguruj parametry procesu klikając w pierwszy operator o nazwie "WebScraper":
- Wskaż adres URL strony, z której mają być pobrane dane.
- Określ liczbę stron do pobrania.

3. Użyj operatora "Write Excel", aby określić docelowy folder oraz nazwę pliku, w którym zostaną zapisane pobrane dane.

4. Uruchom proces analizy opinii klientów.

Wynik:
Po zakończeniu analizy dane wyjściowe zostaną udostępnione w systemie Altair Studio, a poszczególne pliki wynikowe zapisane zostaną w folderze, w którym znajduję się narzędzie.


#English

Description (English):
This process is used for analyzing product reviews based on data retrieved in real-time from the Trustpilot online platform. The process utilizes a Python script to fetch review data from the website and process it to generate detailed analyses.

Usage Instructions:

1. Launch Altair Studio on your computer, install the following extensions in Altair Studio:
- Operator Toolbox
- Python Scripting (requires Anaconda as the Python environment, required libraries: requests, pandas, beautifulsoup4, html5lib)
- Text Processing
2. Configure the process parameters by clicking on the first operator named "WebScraper":
- Specify the URL of the website from which data will be fetched.
- Set the number of pages to scrape.

3. Use the "Write Excel" operator to specify the destination folder and file name where the retrieved data will be saved.

4. Run the customer review analysis process.

Output:
Once the analysis is complete, the output data will be available in the Altair Studio system, and the resulting files will be saved in the folder where the tool is located.
