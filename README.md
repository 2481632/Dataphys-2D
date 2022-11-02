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

## Example data

Im Folgenden ist ein kleiner Ausschnitt aus dem Datensatz zu sehen. Jede Zeile ist ein Anmeldeversuch der fehlgeschlagen ist. 

```
Oct 29 23:58:44 @host sshd[80922]: Failed password for invalid user demo from 167.86.69.67 port 41084 ssh2
Oct 29 23:58:47 @host sshd[80924]: Failed password for invalid user master from 34.75.26.147 port 45526 ssh2
Oct 29 23:58:50 @host sshd[80926]: Failed password for invalid user ubuntu from 167.86.69.67 port 35606 ssh2
Oct 29 23:59:16 @host sshd[80928]: Failed password for invalid user sammy from 187.188.206.106 port 39926 ssh2
Oct 29 23:59:16 @host sshd[80931]: Failed password for invalid user weblogic1 from 167.86.69.67 port 39024 ssh2
Oct 29 23:59:19 @host sshd[80933]: Failed password for invalid user terraria from 167.86.69.67 port 39026 ssh2
Oct 29 23:59:21 @host sshd[80935]: Failed password for invalid user web from 192.99.247.60 port 36190 ssh2
Oct 29 23:59:27 @host sshd[80937]: Failed password for invalid user test from 167.86.69.67 port 39608 ssh2
Oct 29 23:59:37 @host sshd[80939]: Failed password for invalid user user from 167.86.69.67 port 45062 ssh2
Oct 29 23:59:38 @host sshd[80941]: Failed password for invalid user oracle from 34.75.26.147 port 59324 ssh2
```
