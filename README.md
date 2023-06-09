# WalkThrough OpenUI5
In diesem Tutorial werden alle wichtigen Entwicklungsparadigmen von OpenUI5 vorgestellt.

## Step 1: Hello World!
Wie Sie wissen, dreht sich bei OpenUI5 alles um HTML5. Beginnen wir mit dem Aufbau einer ersten �Hello World� nur mit HTML.

## Step 2: Bootstrap
Bevor wir etwas mit OpenUI5 machen k�nnen, m�ssen wir es laden und initialisieren. Dieser Vorgang des Ladens und Initialisierens von OpenUI5 wird Bootstrapping genannt. Sobald dieses Bootstrapping abgeschlossen ist, zeigen wir einfach eine Warnung an.

## Step 3: Controls
Jetzt ist es an der Zeit, unsere erste kleine Benutzeroberfl�che zu erstellen, indem wir den �Hello World�-Text im HTML-Body durch das OpenUI5-Steuerelement sap.m.Text ersetzen. Zu Beginn verwenden wir die JavaScript-Steuerschnittstelle, um die Benutzeroberfl�che einzurichten. Anschlie�end wird die Steuerinstanz in den HTML-Body eingef�gt.

## Step 4: XML Views
Das Einf�gen unserer gesamten Benutzeroberfl�che in die Datei index.html wird sehr bald zu einem chaotischen Setup f�hren und es liegt noch einiges an Arbeit vor uns. F�hren wir also eine erste Modularisierung durch, indem wir das sap.m.Text-Control in eine dedizierte Ansicht einf�gen.

## [Step 5: Controllers](Step_5_Controllers.md)
In diesem Schritt ersetzen wir den Text durch eine Schaltfl�che und zeigen die Meldung �Hallo Welt� an, wenn die Schaltfl�che gedr�ckt wird. Die Behandlung des Druckereignisses der Schaltfl�che ist im Controller der Ansicht implementiert.

## [Step 6: Modules](Step_6_Modules.md)
In OpenUI5 werden Ressourcen oft als Module bezeichnet. In diesem Schritt ersetzen wir den Alert aus der letzten �bung durch einen richtigen Message Toast aus der sap.m-Bibliothek. Die erforderlichen Module k�nnen asynchron geladen werden.

## [Step 7: JSON Model](Step_7_JSON_Model.md)
Nachdem wir nun die Ansicht und den Controller eingerichtet haben, ist es an der Zeit, �ber das M in MVC nachzudenken.