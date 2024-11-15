# Übung: Erstellen einer Unterhaltungsaktion

In dieser Übung erstellen Sie eine Konversationsaktion, die Informationen über ein fiktives Organisationsprojekt mit dem Titel „Projekt ABC“ bereitstellt.

Übungsaufgaben:

- Erstellen einer Unterhaltungsaktion in Copilot Studio
- Veröffentlichen einer Unterhaltungsaktion in Microsoft Copilot
- Testen der Unterhaltungsaktion in Microsoft Copilot

## Aufgabe 1: (Optional) Testen der Standardbenutzerfreundlichkeit

Stellen Sie zunächst eine Frage zu Projekt ABC in Microsoft 365 Copilot.

1. Öffnen Sie **Microsoft Teams** und melden Sie sich mit Ihrem Arbeits- oder Schulkonto an.

1. Wählen Sie **Chat** in der Seitenleiste.

1. Wählen Sie **Copilot** im Chatmenü.

1. Geben Sie in das Feld zum Verfassen der Nachricht `Who should I contact for questions about Project ABC?` ein.

1. Beachten Sie, dass Microsoft 365 Copilot derzeit keine Informationen zu Project ABC enthält.

## Aufgabe 2: Erstellen einer neuen Unterhaltungsaktion

Konfigurieren Sie zunächst den Namen, die Lösung und das Schema für eine neue Unterhaltungsaktion in Microsoft Copilot.

1. Navigieren Sie in Ihrem Webbrowser zu [Copilot Studio](https://copilotstudio.microsoft.com) und melden Sie sich mit Ihrem Geschäfts-, Schul- oder Unikonto an, wenn Sie dazu aufgefordert werden.  Wählen Sie **Überspringen**, um etwaige Begrüßungsnachrichten zu überspringen.

    **Hinweis:** Wenn Sie Copilot Studio zum ersten Mal öffnen, wird möglicherweise eine Chatschnittstelle angezeigt, um Ihren ersten Copiloten zu erstellen. Wählen Sie in diesem Fall die Option **...**. Wählen Sie oben rechts im Menü (neben der Schaltfläche **Erstellen**) die Option **Erstellung des Copiloten abbrechen** und dann **Verlassen**, um die Chat-Oberfläche zu verlassen und die Startseite von Copilot Studio aufzurufen.
1. Wählen Sie in der linken Navigation **Bibliothek** aus. Hier können Sie eine Liste der vorhandenen Aktionen und Connectors anzeigen und eine neue erstellen.
1. Wählen Sie oben **Artikel hinzufügen** aus.  In einem Menü werden zwei Optionen für die Erweiterung von Copilot für Microsoft 365 aufgeführt.
:::image type="content" source="../Media/extend copilot options.png" alt-text="Das Fenster bietet zwei Optionen zur Erweiterung von Copilot: Erstellen eines Copiloten oder eined Aktion.":::
1. Wählen Sie **Neue Aktion** aus.

1. Wählen Sie **Konversation**, um eine Konversationsaktion zu erstellen.

1. Geben Sie in das Feld **Name** `Project ABC` ein und akzeptieren Sie die Standardlösung und das Schema.

1. Wählen Sie **Erstellen** aus, um fortzufahren. Ihre neue Unterhaltungsaktion wird erstellt. Dies wird einige Sekunden dauern. Wenn sie fertig ist, werden Sie zum Erstellungsbereich weitergeleitet, um die Konfiguration Ihrer Aktion fortzusetzen.

## Aufgabe 3: Konfigurieren des Themas

Konfigurieren Sie als Nächstes den Namen und den Trigger für das Thema.

1. Navigieren Sie im Erstellungsbereich für Konversationsaktionen zur Registerkarte **Themen**.

1. Wählen Sie das Textfeld **Themenname** am oberen Rand des Fensters aus, das standardmäßig den Namen `"Untitled"` enthält, und geben Sie `Project ABC info` ein, um das Thema zu benennen.

1. Wählen Sie im Knoten **Trigger** innerhalb des Themas das Textfeld unter dem Text „Beschreiben, was das Thema bewirkt“ aus und geben Sie `Answers questions and provides information about Project ABC, including questions about objectives, points of contact, and rollout timeline.` ein.

## Aufgabe 4: Senden einer Nachricht

Fügen Sie als Nächstes dem Thema einen Knoten hinzu, um eine Nachricht über das Projekt ABC zu senden.

1. Wählen Sie unter dem Triggerknoten das Symbol **+** aus, um einen neuen Knoten hinzuzufügen.

1. Wählen Sie im angezeigten Menü die Option **Nachricht senden** aus.  Ein neuer Nachrichtenknoten wird erstellt.

1. Wählen Sie im Nachrichtenknoten das Textfeld aus und geben Sie `Project ABC is an initiative aimed at improving the culture and engagement within the company.  Objectives of the project include improved morale, increased employee survey results, and improved culture ratings.  For more information about Project ABC, contact Devon Torres.` ein.

1. Wählen Sie **Speichern** über dem Erstellungsbereich aus, um die Änderungen zu speichern.

## Aufgabe 5: Veröffentlichen der Aktion

Als Nächstes veröffentlichen Sie die Aktion zur Verwendung in Microsoft 365 Copilot.

1. Klicken Sie oben auf der Seite auf **Veröffentlichen**.

1. Wählen Sie auf der Seite **Plug-In veröffentlichen** die Option **Veröffentlichen**.

1. Vergewissern Sie sich auf der Seite **Neueste Inhalte veröffentlichen?**, dass das Projekt ABC-Info-Plug-In aktiviert ist und wählen Sie **Veröffentlichen**.  Die Veröffentlichung kann einige Minuten in Anspruch nehmen.  Wenn die Veröffentlichung abgeschlossen ist, wird oben im Fenster eine Benachrichtigung angezeigt.

## Aufgabe 6: Aktivieren und Testen der Aktion

Testen Sie die Aktion schließlich in Microsoft 365 Copilot.

1. Öffnen Sie **Microsoft Teams**.

1. Wählen Sie **Chat** in der Seitenleiste.

1. Wählen Sie **Copilot** im Chatmenü.

1. Wählen Sie im Bereich zum Verfassen der Nachricht die Schaltfläche **Copilot-Antwort verwalten**.

1. Suchen Sie im Flyout nach **Copilot Studio** und wählen Sie dann **Hinzufügen**, um Copilot Studio hinzuzufügen.
 
2. Die Aktion **Projekt ABC-Info** sollte jetzt im Flyout aufgeführt sein.  Bestätigen Sie, dass **Projekt ABC-Info** aktiviert ist und schließen Sie das Flyout.

:::image type="content" source="../Media/projectABCInfo-action-enabled.png" alt-text="Screenshot der Projekt ABC-Info-Aktion, die unter "Manage Copilot response" flyout in Teams."::: aufgelistet ist.

3. Geben Sie in das Feld zum Verfassen der Nachricht `Who should I contact for questions about Project ABC?` ein.

4. Beachten Sie, dass Microsoft 365 Copilot Informationen zu Project ABC zurückgibt, indem es die Unterhaltungsaktion aufruft.

Sie können diese Konversationsaktion mit zusätzlichen Knotenpunkten anpassen oder erweitern.  Sie könnten zum Beispiel einen neuen **generativen Antwort**-Knoten erstellen und eine Datei hochladen, um das für die Aktion verfügbare Wissen zu erweitern.

**Hinweis:** Beachten Sie Folgendes beim Testen Ihrer Aktion in Copilot:
- Copilot wird Ihre Antworten immer in seinem eigenen Stil umformulieren. In dieser Vorschau ist es nicht möglich, den Inhalt unverändert an die Benutzenden weiterzugeben.
- Die Beschreibung Ihrer Unterhaltungsaktion ist entscheidend dafür, wie zuverlässig sie aufgerufen wird. Durch die Beschreibung erfährt der Orchestrator, was Ihre Aktion kann und welche Antworten sie liefern kann. Achten Sie beim Verfassen der Beschreibung darauf, dass Sie eine klare Sprache verwenden und experimentieren Sie mit Änderungen, um das beste Ergebnis zu erzielen.
- Wenn Sie diese Schritte ausführen, wird nicht garantiert, dass Copilot jedes Mal die erwarteten Ergebnisse zurückgibt.  Copilot bestimmt, wann Sie Ihr Plug-In aufrufen und wie die Ergebnisse zurückgegeben werden.

## (Optional) Herausforderung: Eigene Aktion erstellen!

Wenden Sie das Gelernte an, um eine neue Konversationsaktion für ein Szenario Ihrer Wahl zu erstellen, zu veröffentlichen und zu testen.  Wiederholen Sie die Schritte in dieser Übung nach Bedarf.