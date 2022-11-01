## Worum geht es?

Wir betrachten hier SSH-Log-Daten. Per SSH ist es möglich, auf einen entferntes System über das Netztwerk zuzugreifen. Zur Authentifizierung wird oftmals ein Benutzername und ein Passwort verwendet.

## Wo kommen die Daten her?

Die Daten wurden von einem öffentlich aus dem Internet erreichbaren Server gesammelt. 

## Wann wurden die Daten erhoben?

Erhebungszeitraum liegt zwischen dem 24. - 30 Oktober 2022.

## Anfragen nach Land

Im folgenden betrachten wir Länder, aus denen die meisten Zugriffe kamen.

![World map access](/images/map.png)

## Zeitliche Betrachtung

Zuerst einen Blick auf Verteilung über eine Woche hinweg. 

![Access by date](/images/access_by_date.png)

Wie wir sehen, gibt es Unterschiede zwischen den einzelnen Wochentagen. Montag und Mittwoch bilden die Tage, an welchen die meisten Zugriffe stattfanden. Jetzt können wir die Daten noch granularer betrachten und uns einzelne Tage anschauen. In diesem Fall wählen wir uns Montag und Sonntag aus. 

![Access by time](/images/access_by_time.png)

Der Montag steht hier nur als Repräsentant eines Wochentags. Es fällt auf, dass die meisten Anfragen um die Mittagszeit herum kommen. 

## Verwendete Benutzernamen

Beim Loginversuch wird auch der versuchte Benutzername übertragen. Nicht überraschend ist der häufigste Benutzername ```root```, da diese standardmäßig die höchsten Rechte unter einem Uni* System hat. Interressant ist zu sehen, dass auch viele Programmnamen versucht werden, wie ```postgres``` oder ```git```.

![Usernames](/images/usernames.png)
