# Übung: Erstellen eines Prompt-Plug-Ins

Diese Übung umfasst Folgendes:

- Schreiben eines guten Prompts
- Erstellen des Prompts in Copilot Studio
- Testen des Prompts im Prompt Builder
- Verwendung des Prompt-Plug-Ins in Microsoft 365 Copilot

## Schreiben eines guten Prompts

Zu Beginn dieses Moduls haben Sie bereits einige Grundlagen des Prompt Engineering erfahren. Eine großartige Ressource, um mehr über Prompt Engineering zu erfahren, ist der Prompt Engineering-Leitfaden des AI Builder-Teams. Den Prompt Engineering-Leitfaden finden Sie [hier](https://aka.ms/learn-ai-builder-prompting-guide).

## Elemente eines guten Prompts

Der Prompt-Engineering-Leitfaden des AI-Builder-Teams enthält eine Reihe großartiger Elemente, die Teil Ihres Prompts sein sollten.

Wie Sie sehen können, enthält er die folgenden Elemente:

- **Aufgabe**: eine **Anweisung**, die dem generativen vortrainierten Transformatormodell (GPT) mitteilt, welche Aufgabe ausgeführt werden soll.
- **Kontext**: Beschreibung der **Daten**, die bearbeitet werden, zusammen mit allen **Eingabevariablen**.
- **Erwartungen**: Vermittlung der **Ziele** und **Erwartungen** von GPT an die Antwort.
- **Ausgabe**: hilft GPT, die **Ausgabe** nach Ihren Wünschen zu formatieren.

![Ein Screenshot der Prompt-Zutaten-Seite des Prompt-Engineering-Leitfadens von AI Builder. Die Aufgaben, der Kontext, die Erwartungen und die Ausgabe werden als Prompt-Zutaten hervorgehoben.](../Media/4-prompt-engineering-guide.png)

## Aufgabe 1: Entwerfen eines Prompts

In dieser Aufgabe entwerfen Sie einen Prompt, der Ihnen bei der Erstellung eines professionellen Entwicklungsplans auf der Grundlage von Karriere-Meilensteinen hilft.

> [!IMPORTANT]
> Beim Erstellen eines Prompts müssen Sie nicht von Grund auf neu beginnen. Obwohl es sehr hilfreich ist zu wissen, wie man einen guten Prompt schreibt, kann es hilfreich sein, mit etwas zu beginnen, das einen schon auf halbem Weg zum Ziel bringt.
> Prompt-Beispiele sind bereits in der [Microsoft Adoption Sample Solution Gallery](https://aka.ms/power-prompts) verfügbar. In dieser Übung verwenden wir das [Beispiel eines professionellen Entwicklungsplan-Prompts](https://adoption.microsoft.com/sample-solution-gallery/sample/pnp-powerplatform-prompts-professional-development/).

Fügen wir alle Prompt-Zutaten hinzu:

- **Aufgabe**: Entwerfen eines professionellen Entwicklungsplans.
- **Kontext**: Für jemanden, der die folgenden Karriereziele [Meilensteine] erreichen möchte.
- **Erwartungen**: Der Plan sollte Ziele und Ziele, Ressourcen und Tools sowie eine Zeitachse für Aktivitäten umfassen.
- **Ausgabe**: Gestalten Sie den Plan so, dass er prägnant und umsetzbar ist, und präsentieren Sie die Informationen auf klare und leicht verständliche Weise, die für Mitarbeitende auf Junior-Ebene geeignet ist.

Zusammen ergibt das den folgenden Prompt:

*Erstellen Sie einen professionellen Entwicklungsplan für jemanden, der die folgenden Karriereziele erreichen möchte. Der Plan sollte Ziele und Vorgaben, Ressourcen und Tools sowie einen Zeitplan für Aktivitäten enthalten. Gestalten Sie den Plan so, dass er prägnant und umsetzbar ist, und präsentieren Sie die Informationen auf klare und leicht verständliche Weise, die für Mitarbeitende auf Junior-Ebene geeignet ist.*

## Aufgabe 2: Erstellen einer Promptaktion in Copilot Studio

Nachdem Sie den Prompt fertiggestellt haben, können Sie ihn in Copilot Studio eingeben.

1. Navigieren Sie in Ihrem Webbrowser zu [Copilot Studio](https://copilotstudio.microsoft.com) und melden Sie sich mit Ihrem Geschäfts-, Schul- oder Unikonto an, wenn Sie dazu aufgefordert werden.  Wählen Sie **Überspringen**, um etwaige Begrüßungsnachrichten zu überspringen.

    **Hinweis:** Wenn Sie Copilot Studio zum ersten Mal öffnen, wird möglicherweise eine Chatschnittstelle angezeigt, um Ihren ersten Copiloten zu erstellen. Wählen Sie in diesem Fall die Option **...**. Wählen Sie oben rechts im Menü (neben der Schaltfläche **Erstellen**) die Option **Erstellung des Copiloten abbrechen** und dann **Verlassen**, um die Chat-Oberfläche zu verlassen und die Startseite von Copilot Studio aufzurufen.
1. Wählen Sie in der linken Navigation **Bibliothek** aus. Hier können Sie eine Liste der vorhandenen Aktionen und Connectors anzeigen und eine neue erstellen.
1. Wählen Sie oben **Artikel hinzufügen** aus.  In einem Menü werden zwei Optionen für die Erweiterung von Copilot für Microsoft 365 aufgeführt.
:::image type="content" source="../Media/extend copilot options.png" alt-text="Das Fenster bietet zwei Optionen zur Erweiterung von Copilot: Erstellen eines Copiloten oder eined Aktion.":::
1. Wählen Sie **Neue Aktion** aus.
1. Wählen Sie auf dem Bildschirm *Neue Aktion* die Option **Prompt**. Dadurch wird der Prompt Builder von AI Builder geöffnet.
1. Auf der Seite **Aktionsdetails** geben Sie als **Aktionsname** „Professioneller Entwicklungsplan“ ein.
1. Geben Sie die folgende **Beschreibung** ein: „Erstellt einen umsetzbaren professionellen Entwicklungsplan auf der Grundlage der gewünschten Karrieremeilensteine.“
1. Wählen Sie **Weiter** aus.
1. Geben Sie im Abschnitt **Prompt** auf der Seite **Promptaktion hinzufügen** Folgendes ein: „Erstelle einen professionellen Entwicklungsplan für jemanden, der die folgenden Karriereziele erreichen möchte [Meilensteine]. Der Plan sollte Ziele und Vorgaben, Ressourcen und Hilfsmittel sowie einen Zeitplan für die Aktivitäten enthalten. Gestalte den Plan so, dass er prägnant und umsetzbar ist, und präsentiere die Informationen auf eine klare, leicht verständliche Weise, die für Mitarbeitende auf Junior-Ebene geeignet ist.“ (Als **Prompt**.)

    > [!NOTE]
    > Beachten Sie, dass sich oben eine Informationsleiste befindet, die anzeigt, dass Ihr Prompt mindestens einen dynamischen Wert haben sollte.

1. Öffnen Sie unter **Prompt-Einstellungen** in der rechten Seitenleiste den Abschnitt **Eingabe**.
1. Wählen Sie die Schaltfläche **Eingabe hinzufügen**, um eine Eingabe hinzuzufügen.
1. Geben Sie `milestones` als Namen für Ihre Eingabe ein.
1. Fügen Sie den folgenden Text als Beispieldaten hinzu:

      ```text
      * Become medior in 3 years
      * Have 3 top reviews in a row
      * Become a manager in 10 years
      ```

1. Wählen Sie im Promptbereich mit dem Cursor **[Meilensteine]** aus.
1. Wählen Sie **Einfügen** aus.
1. Wählen Sie **Meilensteine** aus.

      Dies wird **[Meilensteine]** in einem dynamischen Wert ändern.

1. Als Nächstes sind wir bereit, unseren Prompt zu testen!

## Aufgabe 3: Testen des Prompts im Prompt Builder

1. Wählen Sie **Prompt testen** unterhalb des Promptbereichs. Dadurch wird der Prompt mit den zuvor hinzugefügten Beispieldaten getestet.

    > [!NOTE]
    > Dadurch wird der Prompt an das KI-Modell gesendet und die Antwort im Abschnitt „KI-Antwort“ angezeigt. So können Sie sehen, wie das LLM reagiert, und feststellen, ob Sie mit den Ergebnissen zufrieden sind.

1. Wenn Sie mit der KI-Antwort zufrieden sind, wählen Sie **Benutzerdefinierten Prompt speichern**, um den Prompt zu speichern.

    Im nächsten Fenster können Sie die Beschreibung des Plug-Ins und die Beschreibung der Eingaben überprüfen.

1. Auf der Seite **Aktionsparameter auswählen** ändern Sie die Eingabebeschreibung von **Meilensteine** in:

      ```text
      The career milestones that the user wants to achieve
      ```

1. Wählen Sie **Weiter** aus.

1. Wählen Sie **Veröffentlichen**, um Ihre Aktion in Microsoft 365 Copilot zu veröffentlichen.  Dies kann einige Minuten dauern.

## Aufgabe 4: Verwenden des Prompt-Plug-Ins in Microsoft 365 Copilot

Nachdem Sie Ihre Promptaktion erstellt und getestet haben, fahren Sie mit der nächsten Aufgabe fort, um in Microsoft 365 Copilot darauf zuzugreifen.  Es kann 5 Minuten oder länger dauern, bis Ihr Plug-In in Microsoft 365 Copilot angezeigt wird.

1. Öffnen Sie [Microsoft Teams](https://teams.microsoft.com).
1. Wählen Sie in der linken Navigation die Schaltfläche **Copilot** aus.
1. Wählen Sie das Symbol **Copilot-Antwort verwalten** am unteren Rand des Bildschirms (neben der Stelle, an der Sie Nachrichten an Copilot senden können).
1. Suchen Sie **Copilot Studio** im angezeigten Flyout-Menü und stellen Sie sicher, dass es aktiviert ist.  
1. Wählen Sie **das Caretsymbol**, um die Liste der Aktionen unter Copilot Studio zu erweitern.

    > [!NOTE]
    > Es könnte sein, dass Copilot Studio nicht sichtbar ist. Dafür kann es zwei Gründe geben: Entweder hat Ihr Admin die integrierte Copilot Studio-App noch nicht bereitgestellt oder das Plug-In wurde noch nicht indiziert – in diesem Fall sollten Sie noch etwas warten.

2. Suchen Sie in der Liste der Aktionen im Abschnitt „Copilot Studio“ nach der Aktion mit dem Namen **Professioneller Entwicklungsplan** und aktivieren Sie sie, indem Sie auf den Schalter daneben klicken.

    > [!NOTE]
    > Wenn Sie den professionellen Entwicklungsplan nicht in der Liste der Plug-Ins unter Copilot Studio sehen, kann es etwas länger dauern, bis er angezeigt wird. Es kann etwas länger dauern, bis es in Microsoft 365 Copilot angezeigt wird.

3. Nachdem Sie die Aktion des professionellen Entwicklungsplans aktiviert haben, können Sie sie nun in Copilot verwenden. **Probieren Sie es aus**, indem Sie die folgende Nachricht an Copilot in Teams senden: „Ich möchte einen beruflichen Entwicklungsplan erstellen, um die folgenden Karriereziele zu erreichen: 1. besser in meiner Arbeit als Marketingfachkraft zu werden und 2. bessere Chancen auf eine Beförderung zur leitenden Marketingfachkraft zu haben.“

**Tipp:** Um den Entwicklermodus in Copilot zu aktivieren, geben Sie `-developer on` im Chat ein.  So können Sie beobachten, wann Copilot ein Plug-In verwendet hat, um im Chat zu antworten.
