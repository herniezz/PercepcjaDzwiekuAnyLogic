📌 Wersja Polska 🇵🇱

Symulacja Hybrydowa Percepcji Dźwięków (AnyLogic)

Ten projekt zawiera model symulacji hybrydowej procesu percepcji dźwięków i podejmowania decyzji przez agentów stworzony przy użyciu oprogramowania AnyLogic.

⚙️ Opis modelu

Model został podzielony na dwie główne części:

🔊 Dynamics Systems – Symulacja Eksperymentu

Model symuluje percepcję dźwięków przez różne osoby (agentów) oraz ich zdolność do rozróżniania tonów na podstawie parametrów:

    errorProbability – prawdopodobieństwo popełnienia błędu.
    reactionTime – czas reakcji agenta.
    thresholdPitch – próg częstotliwości umożliwiający rozróżnienie tonów.

🛠️ Najważniejsze funkcje agenta:

    decideAction() – podejmowanie decyzji przez agenta.
    evaluateSound() – ocena charakterystyk dźwięku.
    perceivePitch() – percepcja częstotliwości dźwięku.
    pressHighButton() / pressMediumButton() / pressLowButton() – symulacja wciskania odpowiednich przycisków.

🎶 Obsługa dźwięków (Java)

Do odtwarzania dźwięków wykorzystano dodatkową funkcję playSound(), której kod umieszczony jest bezpośrednio w modelu. Funkcja ta odtwarza pliki audio na podstawie wskazanej ścieżki.
📈 Flowchart – symulacja procesu decyzyjnego

Diagram przedstawia symulację procesu decyzyjnego uczestnika badania, począwszy od odbioru dwóch dźwięków po decyzję dotyczącą ich podobieństwa lub różnicy.

▶️ Jak uruchomić model?

    1.Pobierz i zainstaluj AnyLogic Personal Learning Edition (PLE) ze strony anylogic.com.
    2. Sklonuj to repozytorium

Uruchom AnyLogic, a następnie otwórz pobrany projekt (.alp):

File → Open → wybierz plik .alp

Po załadowaniu modelu możesz go uruchomić, klikając:

    Run → Run Model

📌 English Version 🇬🇧

Hybrid Simulation of Sound Perception (AnyLogic) 

This project includes a hybrid simulation model of sound perception and decision-making created with AnyLogic software.

⚙️ Model description

The simulation model consists of two main parts:

🔊 Dynamics Systems – Experiment Simulation

The model simulates sound perception by different agents and their ability to distinguish tones based on parameters:

    errorProbability – agent’s probability of making a mistake.
    reactionTime – agent’s reaction time.
    thresholdPitch – frequency threshold for distinguishing tones.

🛠️ Core agent functions:

    decideAction() – agent decision-making process.
    evaluateSound() – assessing sound characteristics.
    perceivePitch() – sound frequency perception.
    pressHighButton() / pressMediumButton() / pressLowButton() – simulation of pressing corresponding buttons.

🎶 Sound playback (Java)

The project includes the playSound() function coded directly into the model, enabling playback of audio files from a specified path.
📈 Flowchart – Decision-making Simulation

This diagram illustrates a simulated participant’s decision-making process, starting with hearing two sounds and concluding with a decision regarding their similarity or differences.

▶️ How to run this model?

    1. Download and install the AnyLogic Personal Learning Edition (PLE) from anylogic.com.
    2. Clone this repository.

Open AnyLogic, then load the downloaded project (.alp file):

File → Open → select .alp file

After loading, start the model simulation by clicking:

    Run → Run Model

✅ Done! You can now explore the simulation.
