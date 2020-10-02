# CraftbeerPi3 Plugin Brau Steps Kollektion

## SimpleSteps

Eine Kollektion von nützlichen Brau-Steps für CraftbeerPi3.

### SimpleManualStep

Dieser Step zeigt eine Nachricht an und optional wird der Brauprozess pausiert. Dies ermöglicht während des Brauen manuelle Schritte zu erledigen. Mit Klick auf den Button Continue wird der Brauprozess fortgesetzt.

### SimpleTargetStep

Setzt für ein Kettle den Auto Mode auf on und die Zieltemperatur, ohne auf das Erreichen der Zieltemperatur zu warten. Mit diesem Step kan bspw. das Aufheizen Nachguss während des Maischens gestartet werden.

### SimpleActorTimer

Dieser Step schaltet einen Aktor für die angegebene Zeitdauer ein.

### SimpleChillToTemp

Dieser Step schaltet einen solange Aktor ein, bis die Temperatur auf die angegebene Zieltemperatur gesunken ist. Dieser Step kann mit einem Kühlaggregat, einem Plattenwärmetauscher oder eine Kühlspirale, einem Magnetventil und einer Pumpe die Würze auf eine Zieltemperatur abkühlen.

### SimpleClearLogsStep

Dieser Step wird als erster Step in einem Brauprozess eingetragen und löscht alle Logs. Die Charts von CraftbeerPi enthalten dann nur Daten vom aktuellen Brauprozess.

### SimpleSaveLogsStep

Speichert die Protokolldateien unter dem vorgegebenen Namen ab.

### SimpleToggleStep

Dieser Step schaltet wahlweise einen Aktor ein oder aus bzw. setzt die Leistung fest und fährt sofort mit dem nächsten Step im Brauprozess fort.
Beispiel 1: Beim Start des Brauprozesses schalte das Rührwerk ein und fahre fort.
Beispiel 2: Beim Start vom Step Kochen schalte das Ringheizelement mit 30% Leistung ein.

### SimpleMashStep

Dieser Maischen-Step schaltet das Rührwerk zum Step-Start automatisch ein und am Ende wieder aus.

### SimpleMashInStep

Dieser Einmaischen Step schaltet während der Phase Aufheizen das Rührwerk ein. Wenn die Zieltemperatur erreicht ist, wird das Rührwerk automatisch ausgeschaltet.

### SimpleBoilStep

Dieser Step erweitert das Kochen mit Nachrichten. Sowohl vor dem Erreichen der Kochtemperatur, als auch vor jedem der maximal 8 Hopfenzugaben wird eine Nachricht angezeigt.

### SimpleMashOutStep

Dieser Step ist ein einfach Abmaischen Step. Es wird die Abmaischtemperatur vorgegebene und die Dauer, wie lange die Abmaischtemperatur gehalten werden soll.

### SimpleWhirlpoolStep

Dieser Step kombiniert die Vorbereitung einer Kühlspirale in der kochenden Würze und den zeitlichen Ablauf für einen Whirlpools mit anschließender Trubkegelbildung.
