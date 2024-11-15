# Übung: Erstellen einer Connectoraktion

In dieser Übung führen Sie die folgenden Schritte aus:

- Erstellen einer Connector-Aktion in Copilot Studio
- Testen der Connectoraktion in Microsoft Teams
- Speichern und Veröffentlichen der Connectoraktion

## Aufgabe 1: Erstellen einer Connectoraktion in Copilot Studio

In dieser Aufgabe konfigurieren Sie eine Connectoraktion für den MSN Wetter-Connector.

1. Navigieren Sie zu [Copilot Studio](https://copilotstudio.microsoft.com) und melden Sie sich mit Ihrem Arbeits- oder Schulkonto an, wenn Sie dazu aufgefordert werden. Überspringen Sie alle Begrüßungsnachrichten.

    **Hinweis:** Wenn Sie Copilot Studio zum ersten Mal öffnen, wird möglicherweise eine Chatschnittstelle angezeigt, um Ihren ersten Copiloten zu erstellen. Wählen Sie in diesem Fall die Option **...**. Wählen Sie oben rechts im Menü (neben der Schaltfläche **Erstellen**) die Option **Erstellung des Copiloten abbrechen** aus, um die Chat-Oberfläche zu verlassen und die Startseite von Copilot Studio aufzurufen.
1. Wählen Sie in der linken Navigation **Bibliothek** aus. Hier können Sie eine Liste der vorhandenen Aktionen und Connectors anzeigen und eine neue erstellen.
1. Wählen Sie oben **Artikel hinzufügen** aus.  In einem Menü werden zwei Optionen für die Erweiterung von Copilot für Microsoft 365 aufgeführt.
:::image type="content" source="../Media/extend copilot options.png" alt-text="Das Fenster bietet zwei Optionen zur Erweiterung von Copilot: Erstellen eines Copiloten oder eined Aktion.":::
2. Wählen Sie **Neue Aktion** aus.
3. Wählen Sie **Connector**, um den Assistenten für Connectoraktionen zu öffnen.
4. Wählen Sie **MSN Wetter** als Connector aus.
5. **Überprüfen** Sie die Beschreibung.

    > [!IMPORTANT]
    > Diese Beschreibung ist sehr wichtig, da Copilot sie verwendet, um die Nachricht der Benutzenden mit Ihrem Plug-In abzugleichen. Wenn Sie keine gute Beschreibung haben, löst Copilot ihre Connectoraktion möglicherweise nicht aus.

1. Wählen Sie **Weiter** aus.
1. Wählen Sie die Aktion **Aktuelles Wetter abrufen** aus.
1. **Überprüfen Sie** die Aktionsbeschreibung.

    > [!IMPORTANT]
    > Überprüfen Sie die Aktionsbeschreibung auf dem folgenden Bildschirm. Diese Beschreibung der Aktion ist sehr wichtig, da Copilot sie verwendet, um die Nachricht der Benutzenden mit Ihrer Aktion abzugleichen. Wenn Sie keine gute Aktionsbeschreibung haben, löst Copilot möglicherweise die falsche Aktion aus.

1. Wählen Sie **Weiter** aus.
1. **Überprüfen Sie** die Beschreibungen aller Eingaben und Ausgaben.

    > [!IMPORTANT]
    > Überprüfen Sie die Eingabe- und Ausgabebeschreibungen auf dem folgenden Bildschirm. Diese Eingabe- und Ausgabebeschreibungen sind sehr wichtig, da Copilot diese zum Auslösen des Connectors (Eingaben) und zum Schreiben einer guten Antwort (Ausgaben) für Sie verwendet. Wenn Sie keine guten Eingabe- und Ausgabebeschreibungen haben, löst Copilot den Connector möglicherweise nicht richtig aus, oder er sendet keine gute Antwort zurück.

1. Wählen Sie **Weiter** aus.
1. Als Nächstes sehen Sie einen Bildschirm, auf dem Sie weitere Aktionen hinzufügen können, wenn Sie möchten. In diesem Fall überspringen wir dies jedoch und wählen **Weiter** aus.

## Übung 2: Testen einer Connectoraktion in Microsoft Teams

In dieser Aufgabe testen Sie die in Aufgabe 1 in Microsoft 365 Copilot konfigurierte Verbindungsaktion in Microsoft Teams.

![Überprüfen, testen und veröffentlichen Sie Ihren Aktionsabschnitt im Aktionsassistenten des Connectors.](../Media/connect-test.png)

1. Wählen Sie eine vorhandene Verbindung aus, falls vorhanden, oder wählen Sie **Neue Verbindung**, um eine neue Verbindung für den MSN Wetter-Connector zu erstellen.
1. Wählen Sie im Menü **Neue Verbindung** die Option **Erstellen** aus.
1. Unter **Ausgewählte Verbindung** können Sie nun Ihre neue Verbindung aus dem Dropdownmenü auswählen.
1. Wählen Sie die Schaltfläche **Aktion testen**.

    > [!NOTE]
    > Dadurch wird ein Prozess ausgelöst, bei dem Ihre Connectoraktion in Microsoft Teams bereitgestellt wird, damit Sie sie testen können.

1. Wählen Sie **Zum Test öffnen**, um zu testen.

    > [!NOTE]
    > Dadurch wird eine neue Browserregisterkarte geöffnet, und es wird versucht, Microsoft Teams zu starten.

1. Sie können jederzeit **Abbrechen** im Pop-up-Fenster auswählen, wenn versucht wird, Microsoft Teams zu starten.
1. Wählen Sie **Stattdessen die Web-App verwenden**.

    > [!NOTE]
    > Dadurch wird Microsoft 365 Copilot in Microsoft Teams geöffnet.

1. Wählen Sie im Bereich zum Verfassen von Nachrichten in Copilot in Teams das Symbol **für das Plugin** neben dem Symbol zum Senden aus.
1. Suchen Sie das Plug-In **Test-MSN Weather** und aktivieren Sie es mit dem Schalter.

    > [!NOTE]
    > Dadurch wird die folgende Meldung angezeigt.

    ![Die Meldung zeigt an, dass das Test-MSN Weather-Plug-In aktiviert ist.](../Media/test-msn-weather.png)


1.  Senden Sie die folgende Nachricht an Microsoft 365 Copilot und geben Sie die Werte für Ihren gewünschten Standort und die Einheiten ein.

    ```text
    What is the current weather in <your location> in <celsius/fahrenheit> according to MSN Weather?
    ```

1. Wenn alles gut gegangen ist, sollte Copilot mit einer Nachricht mit dem Plug-In antworten.  

   ![Ein Screenshot einer Beispielnachricht und -antwort. Das Plug-In antwortet mit dem aktuellen Wetter in Utrecht, Niederlande, in Celsius.](../Media/msn-weather-result.png)

   **Hinweis:** Copilot kann Sie vor der Verwendung des Plug-Ins zur Erlaubnis auffordern.  Wählen Sie **Immer erlauben**, um Copilot die Verwendung des Plug-Ins zu ermöglichen.

   :::image type="content" source="../Media/test-msn-weather-allow.png" alt-text="Screenshot von Copilot, der zur Berechtigung zur Verwendung des Plug-Ins auffordert.":::

## Aufgabe 3: Speichern und Veröffentlichen der Connectoraktion

In dieser Aufgabe speichern und veröffentlichen Sie die Connectoraktion.

Lassen Sie uns dort weitermachen, wo wir in Copilot Studio aufgehört haben.

1. Wählen Sie **Weiter** im Assistenten und die Connectoraktion wird veröffentlicht.

    > [!NOTE]
    > Auf dem nächsten Bildschirm können Sie zum Detailbildschirm wechseln oder speichern und schließen. Wie in der Nachricht angegeben, kann es einige Minuten dauern, bis die Aktion in der Copilot-Benutzeroberfläche angezeigt wird.

      ![Screenshot des Veröffentlichungsbildschirms im Connectoraktions-Assistenten.](../Media/connector-action-finished.png)
   
1. Wählen Sie **Speichern und Schließen**.

Sie haben jetzt Ihre Connectoraktion konfiguriert und veröffentlicht.
